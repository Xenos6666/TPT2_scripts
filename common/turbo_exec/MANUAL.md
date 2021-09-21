# Turbo exec manual

Once you imported that package and enabled all the scripts, you can request turbo from any script by doing the following :
```
executesync("turbo start")
; What you want your script to do
executesync("turbo stop")
wait(0.0) ; This is a no-op, because "executesync("turbo stop")" must never be on the last line
```

It's important for multiple reasons that you use `executesync` and not just `execute` here (more is explained in the source codes of the various scripts.

If your script runs in a loop, you can do this :
```
loopstart:
executesync("turbo start")
; What you want your script to do
executesync("turbo stop")
gotoif(loopstart, should_keep_running)
```
You don't need an extra no-op in this case, as long as the `should_keep_running` condition will stay false at the end.

And if you want to ensure that your action runs in its entierty in a single frame :
```
:global int turbo.cycles.max
:global int turbo.cycles

loopstart:
executesync("turbo start")
turbo.cycles.max = max(turbo.cycles.max, turbo.cycles + number_higher_then_the_number_of_cycles_your_script_will_take)
; What you want your script to do
executesync("turbo stop")
gotoif(loopstart, should_keep_running)
```
There's an extra cycle of turbo after `turbo stop`, so the `gotoif` will run in the last cycle of turbo and only one frame will be used for the whole body of the loop.

It's OK to specify more cycles than your script takes, because turbo will only run for as long as scripts are requesting it.
However, it's a good idea to not be excessive, because this might prevent you from finding unexpected issues.
