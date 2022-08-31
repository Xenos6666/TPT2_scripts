# Turbo exec FAQ

*If you have question that's not answered here, ask me on discord or in github issues, and I'll update the FAQ*

#### Q: How does turbo exec work?

A: The short answer is that when a script stops **itself**, it triggers a bug in the game that causes all scripts earlier in the execution list (the display in the upper-right) to get re-run.
By arranging for this to keep hapenning, processing of AI scripts never ends, and so the game never moves on to the next frame, until we decide to let it. (If you just kept running in turbo forever, the game would freeze.)

For more details, see the extensive comments in the source code.

#### Q: What side-effects does turbo exec have?

A: Firstly, the turbo exec behavior is ***global***. When it is active, **all** running scripts are running in turbo mode, whether or not they asked for it.

There is a bug with turbo exec and the last line of scripts, which is both annoying and also useful.
As long as turbo is active, a script will not be terminated by running off the end, but instead will keep re-executing its last line.
You can prevent this from being an issue by using a no-op like `wait(0.0)` as the last line.
However, you can also take advantage of it to create loops that re-execute an action every cycle, which is otherwise impossible to do.

Stopping a script will still terminate it completely (but remember, don't stop **yourself**.)
Also, `executesync` still functions correctly - it will return when the script reaches the end, even though that script won't terminate.
(And remember, `executesync` ***won't*** continue, but instead will stall, if you use `stop` to end the target script first.)

`wait()` does not function correctly with turbo. To wait a set amount of time with turbo, you have to record a timestamp with `now()`,
and then check when `timestamp + wait_time < now()`. You **could** do that check inside a `waituntil()`,
but it's not recommended to burn cycles like that while in turbo.

#### Q: Is using turbo exec cheating?

A: No. The developpers are aware of the existence of this bug, and are allowing it to exist as it's gonna get replaced by similar features in the future.

#### Q: Is turbo exec gonna be fixed?

A: Yes, when the devs rework the AI, they'll add more "legitimate" ways to do what turbo exec is doing, and they will then patch turbo exec.

#### Q: What's the purpose of making this package for turbo exec? Couldn't each script just use the bug directly?

A: The bug is pretty complicated and using it directly creates a lot of risk for the game freezing, especially if multiple scripts use it at the same time.
This package is aimed to make it is easy for multiple scripts to use turbo exec without interfeering with eachother.
