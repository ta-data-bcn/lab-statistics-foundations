![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations

## Challenge 1
One player rolls two dices. Describe the measure space and the random variable for:
* A. The numbers he/she obtains

     omega = [(1,2),(3,4),(5,6)] (36 combinations)  //  str = [((1,3), (4,2)), ...]      //   X((a, b))= (a, b)

* B. The sum of the rolls

     omega = [2,3,4,5,6,7,8,9,10,11,12]   //   str = [2,2,6,3,...]    ///   X((a)) = a
 
* C. Take only the maximum value
     
     omega = [1,2,3,4,5,6]   //   str = [1,3,5,3,2...]   //   X((a)) = a

Describe the following events:
* For case A: the number is greater than 5
      
      Events = {(6, 6)}
      
* Case B: The sum is even

     Events = {(1, 1), (1, 5), (1, 3), (2, 4), (2, 2),...}

* Case C: the maximum is the value of both rolls

     Events = {(1, 1), (2, 2), (3, 3), ...}

## Challenge 2
One player is taking two cards from poker deck. Describe the measure space and the random variable for:
* A. The number of figures he takes.
     
     omega = [(3, J),(2, 2),...]   //   str = [((3, J),(K, A)),...]   //   X((3, J)) = (3,10)
    
* B. The sum of the cards (figures sum 10 and ace sum 15)
     
     omega = [4,8,9,10,...]   //   str(...)   //   X((A, J)) = 25
     
* C. The number of hearts or spades he takes.

     omega = [(Spade,Heart),(heart,heart),...]   //   str(...)   //   X((heart,spade)) = 2

Describe the 3 following events:
* For case A. The number of figures is two.
      
     Events = {(J, J), (J, K), (J, Q), (Q, J), (Q, Q), (K, Q), (K, J), (Q, K), (K, K)}

* Case B: The sum is 17.
     
     Events = {(A, 2), (2, A), (J, 7), (7, J), (Q, 7), (7, Q), (K, 7), (7, K)}

* Case C: The number is less than 8

     Events = {(2, 2), (2, 3), (2, 4), (2, 5), (3, 2), (3, 3), (3, 4), (4, 2), (4, 3), (5, 2)}
     

## Challenge 3
Two players roll a dice. Describe the measure space and the random variable for:
* The score for player A

     omega = {(1, 1), (3, 2), ...}

* Greatest score

     X(5, 2) = 5

* Earnings of player A with the rule “the player that has the greatest score receives a coin for the other player”

     X(5, 2) = 1

* Earnings of the player A with the rule “the player that has the greatest score receives the difference between the two scores”

     X(5, 2) = 3
     
Describe the events:
* The score of player A is 2 (case A)
     
     Events = {(2, 1), (2, 2), (2, 3), (2, 4), (2, 5), (2, 6)}

* The greatest punctuation is <=2 (case B)

     Events = {(1, 1), (1, 2), (2, 1), (2, 2)}

* If the winner pays the other the difference (case D):

     Events = {(1, 2), (1, 3), (1, 4), (1, 5), (1, 6), (2, 1), (2, 3), ...}

* F: Events = 
  * A wins at least 4 coins.     {(5, 1), (6, 1)}
  * A loses more than 2 coins.   {(1, 4), (1, 5), (1, 6), (2, 5), (2, 6), (3, 6)}
  * No one loses.                {(1, 1), (2, 2), (3, 3), (4, 4), (5, 5), (6, 6)}

## Challenge 4
Three players take balls. There are red, blue, green and black balls. They can take three balls at most with the following rules:

    omega = {(R,R,R), (R,B,G), (G,G,Y)...}

* If the ball is red they can’t take another ball.
     
* If the ball is green they earn a point and they can take another ball.

     X(G,G,R) = (1, 1, 0)

* If the ball is blue they can take another ball.

     X(B,B,G) = (0, 0, 1)

* If the ball is black one point is removed and they can’t take another ball.
     
     X(B) = (0)

Describe the measure space and the random variable for:
* Player A wins (no tie).
* Player A and B get the same points.
* All players get 0 points.

## Challenge 5
Now we are four players. What changes for each case?


## Challenge 6
We have 5 balls in an urn, two black and three white. Describe the measure space and the random variable for:
     
   omega = {(b, b, w), (b, w, w), (w, w, w), ...}

* The number of white balls after 3 takes, if every time we take a ball we keep it.

     X(b, b, w) = 2

* The number of white balls after 3 takes, if every time we take a ball we put it again into the urn.

     X(b, b, w) = 3

* The number of black balls after 3 takes, if every time we take a ball we keep it.

     X(b, b, w) = 0

* The number of black balls after 3 takes, if every time we take a ball we put it again into the urn.

     X(b, b, w) = 2
