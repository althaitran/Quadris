-------------
---Quadris---
-------------

Introduction
------------

This game is very similar to Tetris, except it is turn-based, and
is controlled via text commands. Thus, the blocks do not move faster
at any point during your progress, and you have as much time as you
want to plan your move.

Compilation
-----------
Simply execute "make" on the command-line to generate an executable
called "quadris". It is also recommended that you execute "make clean"
to clean up the object files created through compilation.

Command Line Arguments
----------------------

quadris [-text][-seed xxx]

-text runs the program in text-only mode. No graphics are displayed.
 The default behaviour (no -text) is to show both text and graphics
 (on XWindow).

-seed xxx sets the random number generator's seed to xxx. If you don't
 set the seed, you always get the same random sequence every time you
 run the program.

Commands
--------

During gameplay, you must issue the commands below in order to
make any kind of move in the game. The commands are not cap-sensitive,
and it is possible to just a portion of the actual command (eg, "ri"
for "right") if it is distinguishable from other commands.

LEFT - moves the current block one cell to the left. If this is not
       possible (left edge of the board, or block in the way), the
       command has no ect.

RIGHT - as above, but to the right.

DOWN - as above, but one cell downward.

CLOCKWISE - rotates the block 90 degrees clockwise, as described
            earlier. If the rotation cannot be accomplished without
            coming into contact with existing blocks, the command has
            no ect.

COUNTERCLOCKWISE - as above, but counterclockwise.

DROP - drops the current block. It is (in one step) moved downward as 
       far as possible until it comes into contact with either the bottom
       of the board or a block. This command also triggers the next block
       to appear. Even if a block is already as far down as it can go (as a
       result of executing the down command), it still needs to be dropped
       in order to get the next block.

LEVELUP - Increases the diculty level of the game by one. The block showing
          as next still comes next, but subsequent blocks are generated
          using the new level. If there is no higher level, this command
          has no ect.

LEVELDOWN - Decreases the dicultyculty level of the game by one. The block
            showing as next still comes next, but subsequent blocks are
            generated using the new level. If there is no lower level, this
            command has no ect.

RESTART - Clears the board and starts a new game.

