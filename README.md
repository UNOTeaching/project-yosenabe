# Project Yosenabe

In this assignment, you will develop a solver for the Japanese grid puzzle Yosenabe. To illustrate the rules of the game, consider the following grid.
<p align="center">
  <img src="img/yosenabe.png">
</p>
Given such a grid, initially without arrows, the task is to move each number surrounded by a frame into one of the gray areas along a straight line, respecting the following conditions:
<ul>
  <li> The straight lines of any two moved numbers must not cross or meet at any grid cell.</li>
  <li> Each gray area must be populated with at least one moved number.</li>
  <li> An area may be associated with a positive goal number, shown within it. If this is the case, then the numbers moved into the area must sum up exactly to the goal number.</li>
</ul>
The unique solution of the example, indicated by the arrows of the image, fulfills these conditions:
<ul>
  <li> The straight lines do not cross or meet.</li>
  <li> Some number is moved into each of the four gray areas.</li>
  <li> The bottom left area is associated with goal number 6, and the numbers 5 and 1, that add up to 6, are moved to it. The top right area is associated with goal number 4, and exactly number 4 is moved to it.</li>
</ul>
<p>
Note that the displayed solution is unique. One could try to move the two numbers 2 into the top right area, but that would leave the bottom right area unoccupied.
</p>
<p>
A number can be moved across an area. For instance, in our example the number 4 crosses the area in the middle. On the other hand, you may always assume that the move of a number stops at the first cell (with respect to its direction) of the area to which the number is moved. For instance, number 1 is moved to the cell (2,1), and there would be no solution if we moved it further into the area until the cell (1,1).
</p>
<p>
You can play the game <a href="https://github.com/Advanced-Concepts-Programming-Languages/github-starter-course">here</a>. It is fun and it will help you to get used to the rules.
</p>
