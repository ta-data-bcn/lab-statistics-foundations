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
The measurable space is always the total posible outcomes so in this case are the tuples from (1,1)...(6,6) being the first element of each tuple dice number 1 and the second, dice number two.
* A. The values that the player obtains. 
- Here the random variable would be the same as the measurable space because there's no restrictions. Therefore, X = (1,1),(1,2)...(6,6).
* B. The sum of the values obtained.
- Here the random variable is only X = (2,3,4,5,6,7,8,9,10,11,12) because are the outcomes in this case.
* C. The maximum value obtained after rolling both dices.
- Here I understand that you only count the maximum value of both dices, therefore the random variable X is (1,2,3,4,5,6).

Describe the following events:
* Case A: Both values are greater than 5.
- In this case, we can see that X = (5,5), (5,6), (6,5), (6,6) so the chance to get this is 4/36 (where 36 is the measurable space).
* Case B: The sum of values is even.
- In this case, we can see that X = (2,4,6,8,10,12), therefore we can get those outcomes with 16 outcomes so the chance is 18/36 (logic, because are half of the outcomes).
* Case C: The maximum is the value of both rolls.
- In this case, we can see that X = (1,1)(2,2)(3,3)(4,4)(5,5)(6,6), therefore, the chance is 6/36.

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
The measurable space is all possible outcomes. So for drawing two cards - the first card has 52 choices, and the second has 51 choices. So there are 52*51=2652 total choices. But since it doesn't matter if you have an A/K or a K/A we can divide by 2 so our measurable space is 2652/2 = 1326.
* A. The number of figures he picks.
- Here the random variable would be X={0,1,2}. Because he can either draw 0,1 or 2 figures.
* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
- Here the random variable would be X = (2+2)(2+3)...(2+15)(3+2)(3+3)...(3+15)...(15+1) so from 4 to 25 plus 30, so 22 posibilities.
* C. The number of hearts or spades he picks.
- Here the random variable would be again X(hearts)={0,1,2} and X(spades)={0,1,2}
Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
- In this case, we can see that X = (J/J)(J/Q)(J/K)(J/A)(Q/Q)(Q/K)(Q/A)(K/K)(K/A)(A/A), so the chance would be 10/1326. 
* Case B: The sum of card values is 17.
- In this case, we can see that X = {17} so there's (9/8)(A/2)(10/7)(J/7)(Q/7)(K/7), so the chance would be 7/1326.
* Case C: The value of both cards is less than 8.
- In this case, we can see that X = (2,2)..(2,7)(3,3)..(3,7)...(6,7)(7,7) so 6+5+4+3+2+1=21, so the chance would be 21/1326.

### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
Here the measurable space would be the same as in challenge 1 but in this case the first element of each tuple would be player A's score and the second would be Player B's score.
but the posible outcomes would be the same, 36 differents options.

* A. The score of player A.
- Here the random variable for the score of player A would be {1,2,3,4,5,6}.
* B. The greatest score.
- Here the random variable it's just the highes value of each tuple, so it would be as well, {1,2,3,4,5,6}.
* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".
-Here the random variable would be {0,1}, because either player A has the higher score or he doesnt.
* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 
- Here the random variabel would be each posible difference between the rolls, so {0,1,2,3,4,5}.

Describe the following events:
* Case A: The score of player A is 2.
- In this case, we can see that P(Xa=2)= (2,1)(2,2)(2,3)(2,4)(2,5)(2,6), therefore the chance would be 6/36 or more inuitively 1/6.
* Case B: The greatest score is lower or equal than 2.
- In this case, we can see that P(High score < 2) = (1,1)(2,1)(1,2)(2,2), therefore the chance would be 4/36, so 1/9.
* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  - In this case, we can see that P(player A wins 4 coins or more) = (5,1)(6,2)(6,1), so the chance is 3/36 or 1/12.
  * Player A loses more than 2 coins.
  - In this case, we can see that P(player A loses 2 coins or more) = (1,3)(1,4)(1,5)(1,6)   (2,4)(2,5)(2,6)(3,5)(3,6)(4,6), therefore the chance would be 10/36.
  * Player A neither wins nor loses coins.
  - In this case, we can see that P(player A stays even) = (1,1)(2,2)(3,3)(4,4)(5,5)(6,6),   therefore, the chance would be 6/36 or 1/6.

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