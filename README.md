# Swine-It-Out

LOGISTICS :
In this project, we developed a simulator and multiple strategies for the dice game Swine It Out.

In Swine It Out, two players alternate turns trying to be the first to end a turn with at least 100 total points. On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes.

To spice up the game, we will play with some special rules :

#RULE NO. 1: Hog Out
If any of the dice outcomes is a 1, then the current player's score for the turn is 1.

Scenario A: The current player rolls 7 dice, 5 of which are 1's. They score 1 point for the turn.
Scenario B: The current player rolls 4 dice, all of which are 3's. Since Pig Out did not occur, they score 12 points for the turn.

#RULE NO. 2: Free Bacon 
A player who chooses to roll zero dice scores one more than the largest digit in the opponent's total score.

Scenario A: If the opponent has 42 points, the current player gains 1 + max(4, 2) = 5 points by rolling zero dice.
Scenario B: If the opponent has 48 points, the current player gains 1 + max(4, 8) = 9 points by rolling zero dice.
Scenario C: If the opponent has 7 points, the current player gains 1 + max(0, 7) = 8 points by rolling zero dice.

#RULE NO. 3: Swap the Swine
After points for the turn are added to the current player's score, if both scores are larger than 1 and either one of the scores is a positive integer multiple of the other, then the two scores are swapped.

Scenario A: The current player has a total score of 37 and the opponent has 92. The current player rolls two dice that total 9. The opponent's score (92) is exactly twice the player's new total score (46). These scores are swapped! The current player now has 92 points and the opponent has 46. The turn ends.
Scenario B: The current player has 91 and the opponent has 37. The current player rolls five dice that total 20. The current player has 111, which is 3 times 37, so the scores are swapped. The opponent ends the turn with 111 and wins the game.

TECHNOLOGY USED: 
