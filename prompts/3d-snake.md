Make a 3d snake game in which:
* Your final result is a standalone HTML file with a <canvas> that takes the entire screen
* The game is like a snake that moves on a 3D sphere. Instead of sharp turns, the Left/Right arrows steer the snake direction slightly
* The snake is initially 4 circles long, and when eating a food it grows by 1 and another food appears in a random place
* When you hit yourself, you lose, and the game stops, showing the current score in the center of the screen. Pressing any key restarts it.
* The sphere is drawn as an opaque white circle with a black outline. You can use a red lattice over the circle to convey volume and movement.
* The camera is always centered on the snake head.
* Since all you're drawing are spheres, you can simply use carefully crafted 3d math projections instead of using WebGL

Do it in the following order:
1. Reason about all it will take and what math computations you need to use
2. Examine thoroughly them one by one, making a table of possible mistakes
3. Proceed to rewrite your math if need be
4. Think of how the code outline would look like without coding anything
5. Criticise your result
6. Rewrite the outline as code
7. Look at the code and spot inconsistencies and problems, if any
8. Rewrite the code for the last time. This time don't add comments, empty line breaks or unnecesary checks. Make the minimal piece necessary to produce the expected result.
