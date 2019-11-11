![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations
In this lab we are going to put into practice what we learned about the foundations of statistics. You won't need to use Python, just your brain and a little bit of *Markdown*. 

## Your task
Today you'll need to complete the challenges described below.

## Deliverables
You need to submit a markdown file with the solution to the following challenges. You can create a new *.md* file or directly edit the *README.md* to include your solutions.

## Challenges
### Challenge 1
One player rolls two dices. Describe the measurable space and the random variable for:
* A. The values that the player obtains.
* B. The sum of the values obtained.
* C. The maximum value obtained after rolling both dices.

**Solutions :** 
    A: S={(1,1),(1,2),(1,3)...,(6,5),(6,6)}
    B: Sum=2+3+4+5+6+7+8+9+10+11+12
    c: 12

Describe the following events:
* Case A: Both values are greater than 5.
* Case B: The sum of values is even.
* Case C: The maximum is the value of both rolls.

**Solutions :** 
    A: The sum value has to be: 12 because the only option with a number higher than 5 is 6. 
    B: The result of both dices have to be even or both even to obtain a even sum value.
    C: The maximum is 6 in each dices, so the result is (6,6) and sum value 12.

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
* A. The number of figures he picks.
* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
* C. The number of hearts or spades he picks.

**Solutions:** 
    A: He can pick 1 or 2 figures from the 16 of 52 cards in the deck.
    B: Sum = 4,5,6,7,8,9,10,11,12,13...,20,25,30
    C: He can pick 1 or 2 of the same type or 1 o both, hearth and picks, which 28 are both types of the 52 cards.

Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
* Case B: The sum of card values is 17.
* Case C: The value of both cards is less than 8.

**Solutions:**
    A: He was a sum of 20,25 or 30, depending if he get 2 As or 2 figures or mix.
    B: The cards that he has is the combination of 10 or any figure and a 7 or an As with a 2.
    C: The total result he can obtain as maximum will be 7 and only by cards between 2 to 5.

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.
* B. The greatest score.
* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".
* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 

**Solutions:**
    A: The result has to be between 1 and 6.
    B: the greatest score is 6
    C: If the result from player A is higher than the player B , player A obtain a coin from player B.
    D: If the differents between player A (with a 5) and the player B (with a 2) is 3, the player A obtain 3 coins from player B.

Describe the following events:
* Case A: The score of player A is 2.
* Case B: The greatest score is lower or equal than 2.
* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  * Player A loses more than 2 coins.
  * Player A neither wins nor loses coins.
  
**Solutions:**
    A: The player A has a 2. If player B has a higher result, then player B wins which is 4/6.
    B: It means, both players have a result of 1 or 2.
    C: If player A earn 4 coins, maybe the results are: A=(6,5) and B=(2,1).
       If A lose more than 2, it could be: A=(4,3,2,1) and B=(6,5,4,3)
       If player A does not win any coin, it means both players have the same result.
       
## Bonus challenges
### Bonus Challenge 1
Three players take balls from a box. Inside that box there are red, blue, green and black balls. The players can take three balls at mosts with the following rules:

* If the ball is blue, they can take another ball.
* If the ball is green, they get one point and they can take another ball.
* If the ball is red, they can’t take another ball.
* If the ball is black, they lose one point and they can’t take another ball.

Describe the measurable space and the random variable for:
* A. Player A wins. Do not consider ties as a win.
* B. Player A and B get the same points.
* C. All players get 0 points.

### Bonus Challenge 2
Consider the situation of bonus challenge 1 but now with four players. Does anything change in your solutions? What are the changes in each case?

### Bonus Challenge 3
One player takes three balls from a box. Inside the box there are 5 balls: two of them are black and the other three are white. 

Describe the measurable space and the random variable for:
* A. The number of white balls if every time we take a ball we keep it.
* B. The number of white balls if every time we take a ball we put it back again into the box.
* C. The number of black balls if every time we take a ball we keep it.
* D. The number of black balls if every time we take a ball we put it back into the box.