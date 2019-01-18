# Biquadris-Demo
This page to demonstrate the Private Biquadris Project.
The source code is available to view upon request, but is not open to the public due to Policy 71 of the University of Waterloo.

A total of 57 .cc and .h files are used in this game where in most cases the class performs exactly 1 action, thus the code can be reused for other games that are quite similar and it minimizes recompilation if we were to modify a certain action.

The games has a graphical interface and a terminal text interface. Below is the graphical interface of the game
<img src="images/1.png" width="300" >

The text interface will always show up because we need the terminal window to input commands, but we can disable the graphical window to remove X11 graphics and make the game go faster (if you are on slow internet).

<img src="images/3.png" width="450" >

There are 4 levels programmed to this game with different probability settings on what blocks are going to be spawned next.
Level 3 and 4 is unique because every move or rotation to the block will face 1 down effect and level 4 makes it harder by adding a 1x1 square in the middle of the game after 5 moves if no block is cleared. The 1x1 block is brown in the graphical display and it is an asterisk in the text display.
