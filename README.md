# Breakout Game In Javascript

A version of the MDN's official tutorial: MDN 2D Breakout Game Using Pure JavaScript at https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript with some of my extensions.

# Official Solution
Official solution initial code can be found [here](https://github.com/end3r/Gamedev-Canvas-workshop/blob/gh-pages/lesson10.html) and
interactive demo [here](http://breakout.enclavegames.com/lesson10.html).

# My Solution
My solution code and interactive demo can be found [here](https://codepen.io/DaveWork26/pen/xxVgMqW?editors=1000). The following changes were made:

1. - [x] Added hitpoints to each block, so that it needs to be hit several times before it's destroyed.
1. - [x] Change the colour of the blocks each time they are hit.
1. - [x] Tutorial suggestion: prevent the bat from moving partially off the sides of the canvas.
1. - [x] Improved object collision detection so that the ball reduces the number of bricks destroyed. It now compares against the ball's new position not its current one.
1. - [x] Refactored ball coordinates variable name and moved brick drawing and wall initialisation into separate functions.
1. - [x] Bug fix? Subsequent ball speeds are now the same as at game start - it was 50% faster.

## Screenshot
![JS Breakout](./../Screenshots/jsBreakout.JPG?raw=true "JS Breakout")

## Game Instructions
Use the keyboard left & right arrow/cursor keys or the mouse to move the bat left and right to hit the ball against the wall. Destroy the wall by hitting every brick 7 times, causing them to change colour.
