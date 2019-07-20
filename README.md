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
P(2), P(3), P(4), P(5), P(6), P(7), P(8), P(9), P(10), P(11), P(12). P(eachvalue) = 1/11

* B. The sum of the values obtained.
77*(1/11)=7

* C. The maximum value obtained after rolling both dices.
12

Describe the following events:
* Case A: Both values are greater than 5.
P(1:>5) and P(2:>5) P(10-12) = 3/11
* Case B: The sum of values is even.
P = 6/11
* Case C: The maximum is the value of both rolls.
1/11 * 1/11 = 1/121

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:

* A. The number of figures he picks.
P(2) = 4/52, P(3) = 4/52, P(4) = 4/52, P(5) = 4/52, P(6) = 4/52, P(7) = 4/52, P(8) = 4/52, P(9) = 4/52, P(10) = 4/52, P(10) = 4/52, P(10) = 4/52, P(10) = 4/52, P(15) = 4/52.


* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.


* C. The number of hearts or spades he picks.

Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
* Case B: The sum of card values is 17.
* Case C: The value of both cards is less than 8.

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:

* A. The score of player A.
Player A can get a score from 1 to 6 with equal probability. The random variable would be either of the 6 points represented on the sides of the dice.
The measurable space would look like this:
P(1) = 1/6, P(2) = 1/6, P(3) = 1/6, P(4) = 1/6, P(5) = 1/6, P(6) = 1/6. Sum of all is 1. 

* B. The greatest score.
Greatest score is 6 and thus: P(6) = 1/6.

* C. The earnings of player A if the game rules state that:
"The player with the greatest score gets a coin from the other player.".
Since the outcomes are completely random both players have an equal chance of winning. The probability that Player A wins is: P(A) = 15/36.
The probability that player B wins is: P(B) = 15/36. The probability that they draw  is: P(D) = 6/36, (1/36 probability that both roll a certain number summed by the possibilities)


* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 
The possible outcomes is that either player A or B wins 5, 4, 3, 2 or 1 coin. The probabiity is same for both players. Each randoms variables probability was outlined in part A. 
P(5C) = P(A:6) x P(B:1) = 1/36
P(4C) = P(A:6) x P(B:2) + P(A:5) x P(B:1) = 2/36
P(3C) = P(A:6) x P(B:3) + P(A:5) x P(B:2) + P(A:4) x P(B:1) = 3/36
P(2C) = P(A:6) x P(B:4) + P(A:5) x P(B:3) + P(A:4) x P(B:2) + P(A:3) x P(B:1) = 4/36
P(1C) = P(A:6) x P(B:5) + P(A:5) x P(B:4) + P(A:4) x P(B:3) + P(A:3) x P(B:2) + P(A:2) x P(B:1) = 5/36
P(0C) = P(A:6) x P(B:6) + P(A:5) x P(B:5) + P(A:4) x P(B:4) + P(A:3) x P(B:3) + P(A:2) x P(B:2) + P(A:1) x P(B:1) = 6/36
P(-1C) = P(B:6) x P(A:5) + P(B:5) x P(A:4) + P(B:4) x P(A:3) + P(B:3) x P(A:2) + P(B:2) x P(A:1) = 5/36
P(-2C) = P(B:6) x P(A:4) + P(B:5) x P(A:3) + P(B:4) x P(A:2) + P(B:3) x P(A:1) = 4/36
P(-3C) = P(B:6) x P(A:3) + P(B:5) x P(A:2) + P(B:4) x P(A:1) = 3/36
P(-4C) = P(B:6) x P(A:2) + P(B:5) x P(A:1) = 2/36
P(-5C) = P(B:6) x P(A:1) = 1/36

Describe the following events:
* Case A: The score of player A is 2.
P(B:2) = 1/6

* Case B: The greatest score is lower or equal than 2.
P(B:<=2) = P(1) + P(2) = 2/6

* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  P(A or B: >= 4C) = 1/36 + 2/36 + 1/36 + 2/36 = 6/36 = 1/6
  
  * Player A loses more than 2 coins.
  P(A:<=-2c) = 4/36 + 3/36 + 2/36 + 1/36 = 10/36 = 5/18
  
  * Player A neither wins nor loses coins.
  P(A:0) = 6/36

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