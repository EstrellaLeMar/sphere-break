Inspired by [Yevoc's sbreak programs](http://faqs.ign.com/articles/542/542518p1.html).

A solver for Final Fantasy X-2's Sphere Break mini-game.

Given a grid, the solver will return the "best" 3-coin (1 entry coin, 2 border coins) sequence for all core numbers from 2 to 9 (no multi-coin sequence is possible for a core number of 1).  The "best" sequence is one that maximizes the value of the 2 border coins, since higher-valued border coins tend to disappear first, so they should be used first whenever possible.
