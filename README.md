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

The values are {(A,B) for A and B included in (1,2,3,4,5,6)}.

* B. The sum of the values obtained.

The sum would be {2,3,4,5,6,7,8,9,10,11,12}.

* C. The maximum value obtained after rolling both dices.

The maximum value would be 12.

Describe the following events:
* Case A: Both values are greater than 5.

Both A and B have to be included in {6}. It's 1/6 * 1/6 = 1/36

* Case B: The sum of values is even.

The event is included in {2,4,6,8,10,12}. It's 1/36 + 3/36 + 5/36 + 5/36+ 3/36 + 1/36 = 18/36 = 1/2

* Case C: The maximum is the value of both rolls.

The event can only be {12}. 1/36.

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
* A. The number of figures he picks.

The figures are included in {A,B: A,B in (A,J,Q,K) & (Hearts, Diamonds, Spades, Clubs)}.

* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.

The sum would be {4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,25,30}.

* C. The number of hearts or spades he picks.

He can pick {A,B: A,B in (A,2,3,4,5,6,7,8,9,10,J,Q,K) & (Hearts, Spades)}

Describe the following events:
* Case A: The number of figures in the cards the player picked is two.

16/52 * 15/51 =  240/2652 = 120/1326 = 60/663

* Case B: The sum of card values is 17.

A-2, F-7, 10-7, 9-8 : 96/2652 = 24/663 = 8/221

* Case C: The value of both cards is less than 8.
{A,B in {2,3,4,5,6,7}): 138/2652 = 69/1326 = 23/442

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.

Score of player A {1,2,3,4,5,6}.

* B. The greatest score.

Greatest score = {6}

* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".

if A > B, coin_A += 1

* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 

if A > B, coin_A += A - B

Describe the following events:
* Case A: The score of player A is 2.

A = {2}. 1/6

* Case B: The greatest score is lower or equal than 2.

A = {1,2}. 2/6

* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  
  A > B + 3. 3/36 = 1/12
  
  * Player A loses more than 2 coins.

  A < B + 1. 6/36 = 1/6

  * Player A neither wins nor loses coins.

  A = B. 6/36 = 1/6

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