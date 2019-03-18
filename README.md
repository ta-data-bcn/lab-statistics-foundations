![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations

## Challenge 1
One player rolls two dices. Describe the measure space and the random variable for:
* A. The numbers he/she obtains
X({6,6}) = (6,6)
* B. The sum of the rolls
X({2,2}) = 4
* C. Take only the maximum value
X({3,3}) = 3

Describe the following events:
* For case A: the number is greater than 5
* Case B: The sum is even
* Case C: the maximum is the value of both rolls

## Challenge 2
One player is taking two cards from poker deck. Describe the measure space and the random variable for:
* A. The number of figures he takes.
X({K, Q}) = 2
* B. The sum of the cards (figures sum 10 and ace sum 15)
X({Q, 7}) = 17
X({2, 5}) = 8
* C. The number of hearts or spades he takes.

Describe the 3 following events:
* For case A. The number of figures is two.
* Case B: The sum is 17.
* Case C: The number is less than 8.

## Challenge 3
Two players roll a dice. Describe the measure space and the random variable for:
* The score for player A
X({2, 3}) = 2
* Greatest score
X({2, 1}) = 2
* Earnings of player A with the rule “the player that has the greatest score receives a coin for the other player”
X({6, 2}) = (1, -1)
* Earnings of the player A with the rule “the player that has the greatest score receives the difference between the two scores”


Describe the events:
* The score of player A is 2 (case A)
* The greatest punctuation is <=2 (case B)
* If the winner pays the other the difference (case D):
  * A wins at least 4 coins.
X({6, 2}) = 4
  * A loses more than 2 coins.
X({2, 5}) = 3
  * No one loses.
X({2, 2}) = 0

## Challenge 4
Three players take balls. There are red, blue, green and black balls. They can take three balls at most with the following rules:
* If the ball is red they can’t take another ball.
* If the ball is green they earn a point and they can take another ball.
* If the ball is blue they can take another ball.
* If the ball is black one point is removed and they can’t take another ball.

Describe the measure space and the random variable for:
* Player A wins (no tie).
X({Green, Green, Green}, {Blue}, {Red}) = (3, 0, 0)
* Player A and B get the same points.
X({Green, Green, Black}, {Green, Blue, Green}, {Blue, Blue, Blue}) = (2, 2, 0)
* All players get 0 points.
X({Red}{Red}{Red}) = 0


## Challenge 5
Now we are four players. What changes for each case?
Extra structure representing events of player D


## Challenge 6
We have 5 balls in an urn, two black and three white. Describe the measure space and the random variable for:
* The number of white balls after 3 takes, if every time we take a ball we keep it.
X({White, Black, White}) = 2
* The number of white balls after 3 takes, if every time we take a ball we put it again into the urn.
X({White, White, White}) = 3
* The number of black balls after 3 takes, if every time we take a ball we keep it.
X({White, Black, Black}) = 2
* The number of black balls after 3 takes, if every time we take a ball we put it again into the urn.
X({Black, Black, Black}) = 3
