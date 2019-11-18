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

Solution: 
A) Space = {(1,1),(1,2)...(6,6)} --> 12 outcomes in total
B) Sum of values = {2,3,4,...,12}
C) The maximum value obtained would be the resulting from getting (6,6), would be 12.

Describe the following events:
* Case A: Both values are greater than 5.
* Case B: The sum of values is even.
* Case C: The maximum is the value of both rolls.

A) The outcomes would be P(5,5)+ P(5,6)+ P(6,5)+ P(6,6)= 4/36
B) the outcomes would be repeated numbers (1,1) (2,2) (3,3) (4,4) (5,5) (6,6) or where the sum of the numbers = to an even number
C) ??

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
* A. The number of figures he picks.
* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
* C. The number of hearts or spades he picks.

Solution:
Poker deck has 52 cards (no replacement)
4 Aces: value = 15x4
3 figures x 4 cards : value = 3x4x10
There are 12 cards of each "palo".


Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
* Case B: The sum of card values is 17.
* Case C: The value of both cards is less than 8.

A) 3 figures per 4 'palos' P(1/3*1/4)/52+P(1/2*1/3)/51.
B) Apply n to k formula.
C) It could be done by adding (2,2)...(7,1) we have to find out the probabilities and sum them.


### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.
* B. The greatest score.
* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".
* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 

Solution: they are throwing the same dice outcomes are: {1...6}, the greatest score = 6, Earnings(player1|player1>player2), earnings player 1, +1 and earnings player 2, -1. earnings(winner)= score(winner) - score (loser), this is in money 

Describe the following events:
* Case A: The score of player A is 2.
* Case B: The greatest score is lower or equal than 2.
* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  * Player A loses more than 2 coins.
  * Player A neither wins nor loses coins.
A) P(Player A = 2) = 1/6
B) Either player one or two will have to get a 1.
C) 1) player A would have to get a 6 or a 5
    2) Player B should have a 3, 4, 5, 6 and Player 1 should get 1,2,3,4 respectively.


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