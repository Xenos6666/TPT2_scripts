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
goto(loopstart)
```

And if you want to ensure that your action runs in its entierty in a single frame :
```
loopstart:
executesync("turbo start")
gis("turbo.cycles.max", max(gig("turbo.cycles.max"), gig("turbo.cycle") + number_higher_then_the_number_of_cycles_your_script_will_take))
; What you want your script to do
executesync("turbo stop")
goto(loopstart)
```
