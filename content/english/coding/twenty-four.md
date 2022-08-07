+++
author = "Arthur Gao"
title = "24 Game"
date = "2021-01-08"
description = "A foray into Kotlin App Development"
tags = [
    "coding",
]
+++

To make a long story short, my family has a family loves road trips and one of the things we love to do on these trips is a game called twenty-four. The basic premise of the game is taking a deck of cards, a player draws four cards and everyone races to use basic operations to make the four numbers equal to twenty-four. For example if someone drew the cards 2, 4, 9, 7 from the deck, a possible solution would be $$(9 + 7 - 4) \times 2$$. Sounds boring, I know, but in practice, it actually becomes quite competitive. As a result, a deck of cards was always packed when we set off on a road trip.

Unfortunately for me, a fatal flaw of the game is, although almost always possible, there *are* combinations of cards that just do not have a solution. As a result, we would sometimes give up on a set, not knowing if it was us who had just overlooked an obvious solution, or just that the set of cards was not possible. I endeavoured, on a partarcuarily long road trip to find a solution to this problem, coding a 24 solver in Java. 

The code for the solver is [linked here](https://github.io/Affixrevy/twenty-four-solver).

Once I finished the solver, I realized that I could wrap the solver with a GUI interface with the solver written in Java and the front end written in Kotlin, that would always present four numbers with a solution. Ever since, using my app, the 24 game has become even more competitive and we have been stretched to find even more unique solutions as we know that a solution *is* possible. 

The code for the app is [linked here](https://github.io/Affixrevy/twenty-four-app).

Some screenshots of the app:

TODO: insert screenshots.