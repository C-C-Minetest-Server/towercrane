# Tower Crane Mod
In order to simplify the construction of buildings, the crane forms a working area in which the player can fly (similar to fly privs).

The crane can be completely assembled by setting only the base block.
The size of the crane (which is the working area) can be configured.

![Tower Crane](https://github.com/joe7575/Minetest-Towercrane/blob/master/towercrane640.png)


## Introduction
* Place the crane base block.
  The crane arm will later be build in the same direction you are currently looking 

* Right-click the crane base block and set the crane dimensions in height and width (between 8 and 24 by default).
  The crane will be build according to this settings.

* Right-click the crane switch block to place the hook in front of the crane mast

* Enter the hook by right-clicking the hook

* "Fly" within the working area (height, width) by means of the (default) controls
  - Move mouse: Look around
  - W, A, S, D: Move
  - Space: move up
  - Shift: move down

* Leave the hook by right-clicking the hook or right-clicking the crane switch node

* To destroy the crane, destroy the base block.


## To Do:
- crafting recipe
- automatically give the crane owner area protection  (based on the areas mod)
- output the crane hook position somehow(?) relative to a predefined reference position


# License
Copyright (C) 2017 Joachim Stolberg
Licensed under the GNU LGPL version 2.1 or later. See LICENSE.txt and http://www.gnu.org/licenses/lgpl-2.1.txt
