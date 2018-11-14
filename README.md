# Swine-It-Out

## Table of Contents
  * [Collaborators](#team-members)
  * [Introduction](#intro)
  * [Functionalities](#func)
  * [Project Demo](#proj-demo)
  * [Limitations](#lim)
  * [Future Prospects](#var)
  * [Appendix](#app)
  

## <a name ="team-members"></a> Collaborators
* [Muskaan Goyal]
* [Pranav Bhasin]

## <a name ="intro"></a> Introduction
Swine-It-Out is a dice game simulaton in which two players alternate turns trying to be the first one to have at least 100 total points. On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes. 

## <a name ="func"></a> Functionalities
Some of the twists and functions we used to spice up the simulation are:

### Rule 1: Hog Out
The current player's score for the turn is 1 if any of the dice outcomes is 1.
Scenario 1: If the current player rolls 6 dice, 4 of which are 1's, then the score for current player is 1.
Scenario 2: If the current player rolls 5 dice, all of which are 2's. As the rule 1: Hog out didnt occur, the score for the player is cummulative dice outcomes (here, it is 10).

### Rule 2: Free Points
If a player choses not to roll any dice , then the score for the player is sum of 1 and the largest digit in the opponent's total score.

Scenario: If the opponent has 32 points, the current player gains 1 

### Rule 3: Swap-It-Out
When a turn ends, if the points of both players are either multiple of each other or one score is larger than 1, then the two scores are swapped with each other.

Scenario: The current player has 91 and the opponent has 37. The current player rolls five dice that total 20. The current player has 111, which is 3 times 37, so the scores are swapped. The opponent ends the turn with 111 and wins the game.

## <a name ="proj-demo"></a> Project Demo

## <a name ="lim"></a> Limitations

## <a name ="var"></a> Future Prospects

## <a name ="app"></a> Appendix

[Pranav Bhasin]: https://github.com/PranavBhasin001
[Muskaan Goyal]: https://github.com/muskaangoyal
