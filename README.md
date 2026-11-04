# pivot arm game
Smaller 2d game based on inverse kinematics, collition detection, pathfinding and adversial search
-----------------------------------------------------------------------------------------------------
A puzzle game about a robot arm that walks by gripping. Grab a hold, swing over, and your old base becomes the new hand. Reach the flag in as few moves as you can.

Play: open pivot.html in a browser. No install, no build.

How to play
Click a dot to grip it.
Click a block to pick it up, click empty space to drop it. T turns a plank.
Reach the flag under par.

Hatched can't be gripped, cracked breaks after one use, greasy blocks can be carried but not climbed. A plate holds its door open while a block sits on it. In devil mode, the devil breaks a stone or greases a block after each of your moves.

Z undo, R restart,  H hint, M sound

Under the hood
Inverse kinematics to find the 3-joint arm's pose.
Breadth-first search for par and hints.
One-step minimax for the devil.
Generate-and-test for endless levels, built in a Web Worker.

One self-contained HTML file.
