# Turbo exec manual

Once you imported that package and enabled all the scripts, you can request turbo from any script by doing the following :
```
executesync("TE2.2:start")
; What you want your script to do
executesync("TE2.2:stop")
wait(0.0) ; This is a no-op, because "executesync("TE2.2:stop")" must never be on the last line
```

It's important for multiple reasons that you use `executesync` and not just `execute` here (more is explained in the source codes of the various scripts.

If your script runs in a loop, you can do this :
```
loopstart:
executesync("TE2.2:start")
; What you want your script to do
executesync("TE2.2:stop")
gotoif(loopstart, should_keep_running)
```
You don't need an extra no-op in this case, as long as the `should_keep_running` condition will stay false at the end.

And if you want to ensure that your action runs in its entierty in a single frame :
```
:global int turbo.cycles.max
:global int turbo.cycles

loopstart:
executesync("TE2.2:start")
turbo.cycles.max = max(turbo.cycles.max, turbo.cycles + number_higher_then_the_number_of_cycles_your_script_will_take)
; What you want your script to do
executesync("TE2.2:stop")
gotoif(loopstart, should_keep_running)
```
There's an extra cycle of turbo after `TE2.2:stop`, so the `gotoif` will run in the last cycle of turbo and only one frame will be used for the whole body of the loop.

It's OK to specify more cycles than your script takes, because turbo will only run for as long as scripts are requesting it.
However, it's a good idea to not be excessive, because this might prevent you from finding unexpected issues.

If you need compatibility with TEv2.1, you can also manipulate the underlying
variables directly, but this has some large caveats:
```
:global int turbo.register

loopstart:
turbo.register += 1
; If another script is using turbo, and it has already begun the turbo-stop
; process, turbo could stop somewhere in here unexpectedly before starting the
; next frame.
turbo.register -= 1
; Without an executesync, there is nothing synchronizing on the end-of-frame.
; End-of-frame *will* still occur, but at a time that is less predictable,
; unless you include additional code that basically duplicates what TE2.2:stop
; does.
gotoif(loopstart, should_keep_running)
```
