## Challenges
### Challenge 1
One player rolls two dice. Describe the measurable space and the random variable for:
* A. The values that the player obtains.

All the pairs of dice :
Ω = {(1,1); (1,2) ; (1,3) ; (1,4) ; (1,5) ; (1,6) ; (2,1)... (6,6)}
or
Ω = {(a,b) = {1,2,3,4,5,6} }

In the measurable space Ω, the random variable for the two dice main take all values in the 

* B. The sum of the values obtained.

All combinations of two dice are included between 2 & 12, with different weighting.
So Ω = {2,3,4,5,6,7,8,9,10,11,12}
The random variable is the values available in the Ω, i.e. between 2 & 12.

* C. The maximum value obtained after rolling both dices.
Ω = {12}

Describe the following events:
* Case A: Both values are greater than 5.

the unique event possible for both values to be greater than 5 is when both the dice are having the value : (6,6)

* Case B: The sum of values is even.
Out of the 36, 9 pairs are even, 9 pairs are uneven ; there are therefore 18 possible cases.

* Case C: The maximum is the value of both rolls.
7 is the most recurrent outcome, the value which has the most chance of coming out, due to the fact it has the most possible combination (6 cases out of 36)

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:

* A. The number of figures he picks.
Ω = {(J,J),(J,Q), (J,K),(Q,J), (Q,Q), (Q,K), (K,J), (K,Q), (K,K) }
Random variable = may take the 9 values out of the Ω

* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
Ω = {0, 20, 25, 30}
Random variable = may take any value of the Ω, with different ponderations for each case

* C. The number of hearts or spades he picks.
Ω = {0,1,2 of hearts ; 0,1,2 of spades}
Random variable = may take any value of the Ω, with different ponderations for each case

Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
- Picking the first card, the chance of picking a figure is of 12/52
- Picking the second card, the chance of picking a figure is of 11/51
=> the chance of picking is of 12/52 * 11/51

* Case B: The sum of card values is 17.
With two cards, the combination possible to obtain 17 are : 10 + 7, 9 + 8, 15 +2
We have to create a probability tree with all the possible outcomes to illustrate the results :

#10+7 case
- Picking the first card, the chance of picking a figure or a 10 are of 16/52
- Picking the second card a 7 are of 4/51

#9+8 case
- Picking the first card, the chance of picking a 9 are of 4/52
- Picking the second card a 8 are of 4/51

#8+9 case
- Picking the first card, the chance of picking a 8 are of 4/52
- Picking the second card a 9 are of 4/51

#2+Ace case
- Picking the first card, the chance of picking a 2 are of 4/52
- Picking the second card an ace are of 4/51
******
We have to sum up all those cases by adding up all cases: 
16/52*4/51 + 4/52*4/51 + 4/52*4/51 + 4/52*4/51 + 4*52/4*51
= 64/2652 + 16/2652 + 16/2652 + 16/2652
= 112/2652
* Case C: The value of both cards is less than 8.
- Picking the first card, the chance of picking a card less than 8 is of (7*4)/52 = 28/52
- Picking the second card, the chance of picking a card less than 8 is of (6*4 + 3*3)/51 = 32/51 
=> 28/52 * 32/51 = 0,33

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.
Ω = {1,2,3,4,5,6}
Random variable = any value among the Ω

* B. The greatest score.
Ω = {1,2,3,4,5,6}
Random variable = 6

* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".
Ω = {0 , 1}
Random variable = 0 coin or 1 coin

* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 
Ω = {0,1,2,3,4,5}
Random variable = between 0 and 5 coins

Describe the following events:
* Case A: The score of player A is 2.
For the player A to get a score of 2, only rolling 2 can work
So on a Ω = {1,2,3,4,5,6}, only 2 works = 1 chance out of 6

* Case B: The greatest score is lower or equal than 2.
So on a Ω = {1,2,3,4,5,6}, for the greatest score to be equal to 2, one player needs to roll 1, and the other 1 or 2
So there is a chance of 1/6 (for one player to roll 1) * a chance of 2/6 (the player with the highest score to roll 1 or 2)
= 2/36 = 1/18

* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
Ω of coins = {4,5}
The maximum gain possible is of 5 coins (1 VS.6 on two player' score)
Random variable = between 0 and 5 coins
It may happen on 4 occasions : 6 VS. 1, 5 VS. 1 , 6 VS. 1, 6 VS. 2

  * Player A loses more than 2 coins.
Ω of coins = {3,4,5}
The maximum gain possible is of 5 coins (1 VS.6 on two player' score)
Random variable = between 3 and 5 in the Ω. It encompasses

It may happen on 6 occasions : 6 VS. 1, 6 VS. 2, 6 VS. 3, 5 VS. 1, 5 VS. 2 , 4 VS. 1 

  * Player A neither wins nor loses coins.
Ω of coins = {6}
It may happen on 6 occasions, each time both roll dice are equal : (6,6), (5,5), (4,4), (3,3), (2,2), (1,1) 

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