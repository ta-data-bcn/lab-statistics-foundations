![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations

## Challenge 1
One player rolls two dices. Describe the measure space and the random variable for:
* A. The numbers he/she obtains

     omega = [(1,2),(3,4),(5,6)] (36 combinations)
     str = [((1,3), (4,2)), ...] 
     X((1, 3))= (1, 3)
     X((a, b))= (a, b)

* B. The sum of the rolls

     omega = [2,3,4,5,6,7,8,9,10,11,12]
     str = [2,2,6,3,...] 
     X((a)) = a
 
* C. Take only the maximum value
     
     omega = [1,2,3,4,5,6]
     str = [1,3,5,3,2...]
     X((a)) = a

Describe the following events:
* For case A: the number is greater than 5
      
      str = (6,6)
      
* Case B: The sum is even

      str = (2,4,6,8,10,12)
      
* Case C: the maximum is the value of both rolls

      str = ((1,1),(2,2),(3,3),(4,4),(5,5),(6,6))

## Challenge 2
One player is taking two cards from poker deck. Describe the measure space and the random variable for:
* A. The number of figures he takes.
* B. The sum of the cards (figures sum 10 and ace sum 15)
* C. The number of hearts or spades he takes.

Describe the 3 following events:
* For case A. The number of figures is two.
* Case B: The sum is 17.
* Case C: The number is less than 8.

## Challenge 3
Two players roll a dice. Describe the measure space and the random variable for:
* The score for player A
* Greatest score
* Earnings of player A with the rule “the player that has the greatest score receives a coin for the other player”
* Earnings of the player A with the rule “the player that has the greatest score receives the difference between the two scores”

Describe the events:
* The score of player A is 2 (case A)
* The greatest punctuation is <=2 (case B)
* If the winner pays the other the difference (case D):
  * A wins at least 4 coins.
  * A loses more than 2 coins.
  * No one loses.

## Challenge 4
Three players take balls. There are red, blue, green and black balls. They can take three balls at most with the following rules:
* If the ball is red they can’t take another ball.
* If the ball is green they earn a point and they can take another ball.
* If the ball is blue they can take another ball.
* If the ball is black one point is removed and they can’t take another ball.

Describe the measure space and the random variable for:
* Player A wins (no tie).
* Player A and B get the same points.
* All players get 0 points.

## Challenge 5
Now we are four players. What changes for each case?


## Challenge 6
We have 5 balls in an urn, two black and three white. Describe the measure space and the random variable for:
* The number of white balls after 3 takes, if every time we take a ball we keep it.
* The number of white balls after 3 takes, if every time we take a ball we put it again into the urn.
* The number of black balls after 3 takes, if every time we take a ball we keep it.
* The number of black balls after 3 takes, if every time we take a ball we put it again into the urn.
