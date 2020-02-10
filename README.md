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
Ω = {(dice1, dice2): dice1, dice2 € {1,2,3,4,5,6}}
* A. The values that the player obtains.
two random values between 1 and 6 with result not related
* B. The sum of the values obtained.
RV = {2,3,4,5,6,7,8,9,10,11,12}
two random values between 1 and 6 with result not related. Central values {6,7,8} have more probabilities because there are more number combinations for them
* C. The maximum value obtained after rolling both dices.
RV = {12}
the result would be two times 6 because is the maximum value and should be in both cases
Describe the following events:
* Case A: Both values are greater than 5.
RV = {(5,6),(6,6,),(6,5)}
the only possibility that both numbers are greater than 5 is having two 6 and this is also the maximum combination
* Case B: The sum of values is even.
RV = {(1,1),(2,2),(3,1) ... (3,5) ... (4,4) ... (6,6) ... }
both numbers are even or both odd
* Case C: The maximum is the value of both rolls.
RV = {(6,6)}

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
>> 52 cards
>> 3 * 4 = 12 figures
>> 4 aces
* A. The number of figures he picks.
Ω = {(deck): deck € 4 * {ace,2,3,4,5,6,7,8,9,J,Q,K}}
there are 3 figures 4 times so there are 12 figures over 52 cards
the second time he picks a card, there is 1 less so spectrum would be over the result after picking up a card
* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
RV = sum(Ω)
* C. The number of hearts or spades he picks.
RV = {0,1,2 of heards; 0,1,2 of spaces}
there are different options; he can pick up from 0 to two heart cards and from 0 to 2 of spaces. In case of both, there is just one option: 1 of each

Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
RV = {(J,J) ... (J,K) ... (K,K)}
* Case B: The sum of card values is 17.
RV = {(ace,2),(8,9)... }
* Case C: The value of both cards is less than 8.
RV = {(card1:card2): card1 ,card2 € (2,3,4,5,6,7)}

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.
Ω = {A € {1,2,3,4,5,6}}
* B. The greatest score.
RV = {12}
* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".
RV = {0,1}
* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 
RV = {-5,-4,-3,-2,-1,0,1,2,3,4,5}
Describe the following events:
* Case A: The score of player A is 2.
RV = {(2,1),(2,2),(2,3) ... (2,6)}
* Case B: The greatest score is lower or equal than 2.
RV = {(1,1),(1,2),(2,2),(2,1)}
* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
    RV = {(5,1)(6,1),(6,2)}
  * Player A loses more than 2 coins.
    RV = (1,6)
  * Player A neither wins nor loses coins.
    RV = {(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)}

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