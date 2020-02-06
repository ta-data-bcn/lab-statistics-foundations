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
The measurable space is {(a,b): a,b elements in {1,2,3,4,5,6}}
The value of X can be any combination of the elements in {1,2,3,4,5,6}
P{X = {1,1}} {1,1} = 1/36
P{X = {1,2}} {1,2} = 1/36
P{X = {1,3}} {1,3} = 1/36
          .
          .
          .
P{X = {1,6}} {1,6} = 1/36
P{X = {2,1}} {2,1} = 1/36
          .
          .
          .
P{X = {6,1}} {6,1} = 1/36
          .
          .
          .
P{X = {6,6}} {6,6} = 1/36 


* B. The sum of the values obtained.
The measurable space is {(a): a element in {2,3,4,5,6,7,8,9,10,11,12}}
The value of X can fall between 2 to 12
P{X = 2}   {1,1} = 1/36
P{X = 3}   {1,2}, {2,1} = 2/36
P{X = 4}   {1,3}, {2,2}, {3,1} = 3/36
P{X = 5}   {1,4}, {2,3}, {3,2}, {4,1} = 4/36
P{X = 6}   {1,5}, {2,4}, {3,3}, {4,2}, {5,1} = 5/36
P{X = 7}   {1,6}, {2,5}, {3,4}, {4,3}, {5,2}, {6,1} = 6/36
P{X = 8}   {2,6}, {3,5}, {4,4}, {5,3}, {6,2} = 5/36
P{X = 9}   {3,6}, {4,5}, {5,4}, {6,3} = 4/36
P{X = 10}  {4,6}, {5,5}, {6,4} = 3/36
P{X = 11}  {5,6}, {6,5} = 2/36
P{X = 12}  {6,6} = 1/36


* C. The maximum value obtained after rolling both dices.
The measurable space is between 1 - 6 with the random varibale being the max of the outcome of two rolls.
The measurable space is {(a,b): a,b elements in {1,2,3,4,5,6}}
The value of X can be the max element in {1,2,3,4,5,6} which is {6}.

Describe the following events:
* Case A: Both values are greater than 5.
E = {(i,j) where i and j are greater than 5

* Case B: The sum of values is even.
E = {(i,j) where i + j is even}

* Case C: The maximum is the value of both rolls.
E = {(i,j) where i + j is 12}

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
* A. The number of figures he picks.
The measurable space is {(a,b): a,b elements in {2,3,4,5,6,7,8,9,10,J,Q,K,A}}
P{X = J} = 4/52
P{X = Q} = 4/52
P{X = K} = 4/52

* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
The measurable space is {(a): a elements in {2,3,4,5,6,7,8,9,10,J,Q,K,A}}
P{X = random variables} where the combination of cards sum up to a maximum of 30 (ace + ace)

* C. The number of hearts or spades he picks.
The measurable space is {(a,b): a elements in {2,3,4,5,6,7,8,9,10,J,Q,K,A}}
P{X = hearts or spades} = 26/52
P{Y = hearts or spades} = 26/52

Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
E = {(i,j) where i and j are either J, Q, or K

* Case B: The sum of card values is 17.
E = {(i,j) where i + j is 17 

* Case C: The value of both cards is less than 8.
E = {(i,j) where i and j both < 8


### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.
The measurable space is {(a): a elements in {1,2,3,4,5,6}}
P{X = 1} for player_A = 1/6
P{X = 2} for player_A = 1/6
P{X = 3} for player_A = 1/6
P{X = 4} for player_A = 1/6
P{X = 5} for player_A = 1/6
P{X = 6} for player_A = 1/6

* B. The greatest score.
The measurable space is {(a): a elements in {1,2,3,4,5,6}}
P{X>Y} = 1/36
P{Y>X} = 1/36
    {2,1}, {3,1}, {4,1}, {5,1},{6,1},
    {3,2}, {4,2}, {5,2}, {6,2},
    {4,3}, {5,3}, {6,3},
    {5,4}, {6,4},
    {6,5}
    
* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".
The measurable space is {(a): a elements in {1,2,3,4,5,6}}
P{X = 1 coin}  = 1/36
P{Y = 1 coin}  = 1/36

* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 
The measurable space is {(a): a elements in {1,2,3,4,5,6}}
P{X = 0} = {1,1}, {2,2}, {3,3}, {4,4}, {5,5}, {6,6}
P{X = 1} = {2,1},{3,2},{4,3},{5,4},{6,5} = 5/36
P{X = 2} = {3,1},{4,2},{5,3},{6,4} = 4/36
P{X = 3} = {4,1},{5,2},{6,3} = 3/36
P{X = 4} = {5,1},{6,2} = 2/36
P{X = 5} = {6,1} = 1/36

Describe the following events:
* Case A: The score of player A is 2.
E = {(i,j) where i is 2 and j is in {1,2,3,4,5,6} 

* Case B: The greatest score is lower or equal than 2.
E = {(i,j) where i = 2 and j < 2

* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  This event has a probability of 2/36 
  
  * Player A loses more than 2 coins.
  This event has a probability of 5/36 
    
  * Player A neither wins nor loses coins.
  This event has a probability of 6/36 


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