# HappyCI

Use HappyCI to give your team positive feedback from the Travis CI.
Two things to remember:
* "Blue is the new red"
* "Always use avatars"

## Overview

HappyCI use different slides to inform the team about the different build(failures) statuses.
Based on the build states HappyCI rotates the different slides for each build status.


The following states are supported (API v2):

* errored (orange)
** Houston we have a problem
* failed (blue)
** [github user], [build] needs your attention!
** [github user] probably you made some little typo in [build]
** Let's pretend it didn't happen! [github user]@[build]
** Even if you fall on your face you’re still moving forward.
** Oeps, you did it again [github user]
** I've failed over and over again and that's why I succeed. [build]

* started
** [build] is started, fingers-crossed
** Some magic is happening overhere [build]

* passed
** Oh yeah, [build] passed, keep up the good work!
** [counter] minutes no failing builds.

* failed -> passed
** [user], thanks for fixing me! [build]
** [user], thanks for fixing me! [build]

## random slides
* clock functionality see [http://www.thisiswhyimbroke.com/qlocktwo-designer-clock]
* commit motivations (all blue)
** awesome commit by [user] detected