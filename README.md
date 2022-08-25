# Project Yosenabe

In this assignment, you will develop a solver for the Japanese grid puzzle Yosenabe. To illustrate the rules of the game, consider the following grid.
<p align="center">
  <img src="img/yosenabe.png"/>
</p>
Given such a grid, initially without arrows, the task is to move each number surrounded by a frame into one of the gray areas along a straight line, respecting the following conditions:
* The straight lines of any two moved numbers must not cross or meet at any grid cell.
* Each gray area must be populated with at least one moved number.
* An area may be associated with a positive goal number, shown within it. If this is the case, then the numbers moved into the area must sum up exactly to the goal number.
