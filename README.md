# AMAZING-MAZES
My first program, that works properly...sort of.

All you need to do to get it to work is ensure you have the following Python3 libraries installed.

- PIL
- sys

Then run the app.py file. 

You will first need to generate a maze. 

Currently the RB (Revese Backtracking) can only make mazes up to about 50x50. Above that you will need to use my BT (binary tree algorithm). You can generate as many mazes as you like so long as they have unique names.

Then you can then either solve or load a maze from the database.

Solving will draw a path from the top left to bottom right, this will also save the solved maze to the database so it can be loaded later on, or on another day.

Loading will just load a maze unsolved and if it's been solved, then it will load the solved maze as well. Also it creates a popup of times to generate and solve.

Hope you enjoy, Billy.
