# Time Report

> Write about what you have done and how long you have worked on each part of the project.

**2021-10-24 **setting up basic vatiables and functions. Also making the gameplay loop so that I can activly test functions as soon as possible.
**4 hours in**

**2021-10-25** fixed dice roll function to work properly
**4½ hour in**

**2021-10-27** cleaned up some code, changed array name on pawns that were played and not longer in game.  
From p1PawnOff to p1Goal and p2PawnOff to p2Goal to shorten the names a bit and be clearer that they're in goal. Reordered som parts of the code and added rules.
**7 hrs in**

**2021-11-02** added an array with numbers correlating to amount of steps taken by each pawn. Making an alert telling the player what happened.

Instead of creating the win check variable "GameOver" at the start of the code, I decided it can be created at the play loop. More logical this way, and the function checking it is created earlier, is not running until after it is created.

Experimenting and trying out and decide how to pick pawns
and to make them move along the board.

added move function. This doesn't do anything as of yet, since it is(will) be dependent on the PickPawn function where you pick what pawn you want to move. As of yet it is not fully implemented, jsut some early test the MovePawn function doesn't do much, at least it is not crashing the program. ¯\_(ツ)_/¯
**12 hrs in**

**2021-11-05** Updated and fixed some issues regarding the movePawn and pickPawn functions.
**12½ hrs in**

**21-11-15** changed so that Instead of having one array representing all pawns, I decided to makit two separate arrays, one for each player. It'll be easier to compare whos pawn it is aswell as easier to iterate and add pawns later on.
**14 hrs in**

**21-11-16** Made the code better for iteration. Instead of hard coding numbers, I've tried to make it based on numbers of pawns for example. So, alot of code wont have to be changed later on if I decide to update how many pawns I have in the game. Made some code more efficient as well.

also added a function to se if the move the player want to do is valid as well as executing the move (not shown in UI as of yet.). Some variables changed to be global for use else -where. 
**16 hrs in**

**21-11-17** made a function that can find ouy what "graphics" to be used dependent on what pawn was moved. Aso ALOT of experimenting and trying to figure out how to update the UI. Alot of sitting in the sofa just trying to think how I want to approach the problem.
**20 hours in**

**21-11-18** changed the board UI variable to be a function that can be called upon for to update.

reduced the lines of code for the roll funciton. Instead of having lots of different dice, U just made it repeat a roll and add it to the final result. Much more efficient and super simple to change amount of die if I would desire to do so by simply chaining just one number. Since the dice arent used anywhere else there was no point int having them as separate variables.
added an option to show rules when picking a pawn to move.
The board UI updates when pawns moves across the board, and removes old grapgics when moving
**21:00 hrs in**

**21-11-19**

**22:30 hrs in**
