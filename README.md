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
#### * A. The values that the player obtains.

S = For each roll {1 to 6}
x = ax, bx

####  * B. The sum of the values obtained.

S = {2 to 12}
x = a + b

####  * C. The maximum value obtained after rolling both dices.

S = {1 to 6}
x = max(a or b)

####  Describe the following events:
* Case A: Both values are greater than 5.
E = {6,6}
* Case B: The sum of values is even.
E = (D1x = D2x)
* Case C: The maximum is the value of both rolls.
E = The value of both rolls is the same.

### Challenge 2
#### One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
#### * A. The number of figures he picks.
S = {1/52}, {1/51}
X = x, y
#### * B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
S = {4 to 30}
X = x + y
#### * C. The number of hearts or spades he picks.
S = Hearts {0 to 2}, Spades {0 to 2}
X = The player picks from 0 to 2 hearts or spades. For every Heart or Spade picked, the range of the other diminishes for one.

#### Describe the following events:
#### * Case A: The number of figures in the cards the player picked is two.
E = Out of 52 cards the player picks one card. Out of the remaining 51, the player picks one.
#### * Case B: The sum of card values is 17.
17 = x + y
#### * Case C: The value of both cards is less than 8.
8 < x + y 

### Challenge 3
#### Two players roll a dice. Describe the measurable space and the random variable for:
#### * A. The score of player A.
S = {1 to 6}
X = X

#### * B. The greatest score.
S = {1 to 6}
X = the maximum value of the roll either of player A or player B.

#### * C. The earnings of player A if the game rules state that:  
#### "The player with the greatest score gets a coin from the other player.".
S = {1,-1}
X = If player's A roll is greater than player's B roll the first earns a coin. If it's the player B the one with a greater value, player A gives a coin to player B.

#### * D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 
S = {1 to 5}
X = If player A has a greater value than player B, he earns as many coins as the difference between both values

#### Describe the following events:
#### * Case A: The score of player A is 2.
E = 
#### * Case B: The greatest score is lower or equal than 2.
E =
#### * Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  E = Player A dice rolling is either 5 or 6.
  * Player A loses more than 2 coins.
  E = Player A dice rolling is between 1 and 3.
  * Player A neither wins nor loses coins.
  E = Player A dice rolling throws the same value as player's B.
  

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