# cpe-40032-m4-16-

Objectives

Implement time addition on matches, such that scoring a match extends the timer by 1 second per tile in a match.
Ensure Level 1 starts just with simple flat blocks (the first of each color in the sprite sheet), with later levels generating the blocks with patterns on them (like the triangle, cross, etc.). These should be worth more points, at your discretion.
Create random shiny versions of blocks that will destroy an entire row on match, granting points for each block in the row.
Only allow swapping when it results in a match. If there are no matches available to perform, reset the board.
(Optional) Implement matching using the mouse. (Hint: you’ll need push:toGame(x,y); see the push library’s documentation here for details!
