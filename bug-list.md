# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Problem: UI wont update. The UI was stored as a variable. I expected it to update every time the variable was called upon, I haven had any similar problems before, but that is probably just me who havend used a variable in this way. I thought for a long time that the problem was the function looking for what variable withing the UI to update not working. With some help during a lesson I got the explanation of how variables work and update.


2. When pleayer 2 pawns are leaving the board by enter goal, old graphic stays. Need to see what is causing this.  STILL AN ISSUE

3.Some times when a player rolls a 0, the graphics on the board dissappear, probably since the pawn did not move, and the program looks if there is a pawn on last active pawns toLovation, and hence removing said pawn. Soved by putting thePawn variable and toLocation updating functions if the roll is not 0
