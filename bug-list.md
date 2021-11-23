# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Problem: UI wont update. The UI was stored as a variable. I expected it to update every time the variable was called upon, I haven had any similar problems before, but that is probably just me who havend used a variable in this way. I thought for a long time that the problem was the function looking for what variable withing the UI to update not working. With some help during a lesson I got the explanation of how variables work and update.


2. When pleayer 2 pawns are leaving the board by enter goal, old graphic stays. Need to see what is causing this. Fixed, not sure why, but presumably a similar issue like in bug 4,5 or 6 solved it.

3.Some times when a player rolls a 0, the graphics on the board dissappear, probably since the pawn did not move, and the program looks if there is a pawn on last active pawns toLovation, and hence removing said pawn. Soved by putting thePawn variable and toLocation updating functions if the roll is not 0

4. The graphic wont update when the pawn has moved 13 or 14 steps. This was caused by subtracting 14 from the pawns moved steps to find the correlating number in the array, this was causing the updUI function to "update outside the array". Solved by dubtracting 13 from the roll instead. so that 14 steps become index 1 in the array, and 13 steps becoming index 0 in the array.

5.Small error in knockOutPawn made pawns knock out the opposite pawn if both had taken 13 steps even though they're safe squares. This was caused by the function looking if the pawnLoc were less or equal to 13 where as it should be 12. Changed the number to 12 and it works.

6. The function updUI() replaced board[0][0] with the pawn that had entered goal with that pawns graphic. This was caused by the function having that as active square to replace with the active pawns graphic. By adding row 278, looking of the pawn has entered goal and then just simply not update it evnen tough the square is still "targeted".
