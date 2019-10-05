# Frickin Atomic Space Helicopters #

---

## Intro ##

You are tasked with writing the control software for the new Titan Space Helicopters.

The world is harsh and has huge pillars of stone that are to large to fly over.

* [Example fields](fields/)
* [User-contributed code](solutions/)

---

## Part 1 ##

You start with the copters x and y position and it's current heading.

You must give the copter basic commands to fly from the start position to an end position using only the commands:
* Forward
* Turn Left
* Turn Right

If the copter encounters an obstacle, it stops and returns an error to the controller.

---

## Part 2 ##

Having the heli controlled by a human on earth is to slow.
We need you to implement the [A* path finding algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm) to find a path from a start co-ordinate to an end co-ordinate (eg. top-left to bottom-right).

```
X X # . # . # . # . . . . . . # . # . . . . . # . 
c X X # . . . . . . . # # . # . # . # . . . . . # 
c c X X X X X X X c # . . # . . . # . . . # # # . 
c # c c c . # . X X X c # # # . . . . . . . . . # 
c c c # c c c c . c X # # . . . # . . . # . # . . 
# c c . c c # c # # X X # . . # . . . . . # . . . 
# c # . c c c c # . # X c c c # . . # . . . . . . 
# . # . # # # c c c # X c # # . . . . # . # . . . 
. . # . . . . . c # . X # . . . . . . . # . . . . 
. . # . . # . # # . # X X c c c c c # . . . . # . 
. # . . . . . # # . . c X # # # # c # . . # . . # 
. . . . . . . # . . . # X . . # # # . . . # . . . 
# . . . . # . # # . . . X X X # . . . . # . . . # 
# # . # # # # . . . . . c # X X X X X . . . # # . 
. . . . . . # # . . . . . # c c . # X c c c c . # 
. # . . . . # . # . # . # . # # . # X . c c . . # 
. . . # . # # . . . # . . # # . . # X X c # . # . 
. # . # . . . . . # . . # . # # # # . X c # . . # 
# . . . . . . . . . . . . . # . . . . X c . . . # 
. # . # . # . # # # . . . # . . . # . X c # . # . 
. . . . # . . . . . # . # . . # . . . X # . . . . 
. . . # . . # . . . . . # # . . . . # X X X . . . 
# . . . . . . . # . . . # . . . . . . . . X . # # 
. # . . # . . # # # . . # . # # . # . # . X X X X 
. . . . . . . . # . . . # . . . # # . . . # . # X
```

---

Visitor@Tu5par!c
