![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations

## Challenge 1
One player rolls two dices. Describe the measure space and the random variable for:
* A. The numbers he/she obtains
omega = {1,2,3,4,5,6}, structure = {(1,1),(1,2),(3,1)...}
RV: X({D1,D2}) = 1,1

* B. The sum of the rolls
omega = {1,2,3,4,5,6}, structure = {(1,1),(1,2),(3,1)...}
RV: X({D1,D2}) = 2

* C. Take only the maximum value
omega = {1,2,3,4,5,6}, structure = {(1,1),(1,2),(3,1)...}
RV: X({D1,D2}) = 2

Describe the following events:
* For case A: the number is greater than 5
omega = {1,2,3,4,5,6}, structure = {(3,3),(4,2),(5,1),(6,2)...}
RV: X({3,3}) = 6 

* Case B: The sum is even
omega = {1,2,3,4,5,6}, structure = {(1,3),(1,5),(2,2),(2,4),...}
RV: X({2,2}) = 4
* Case C: the maximum is the value of both rolls
omega = {1,2,3,4,5,6}, structure = {(1,1),(1,2),(1,3),...}
RV: X({2,3}) = 3 


## Challenge 2
One player is taking two cards from poker deck. Describe the measure space and the random variable for:
* A. The number of figures he takes.
omega = {0,1}, structure = {(0,0),(0,1),(1,1)}
RV: X({0,1}) = 1

* B. The sum of the cards (figures sum 10 and ace sum 15)
omega = {1,2,3,4,5,6,7,8,9,10,10,10,15}, structure = {(1,2),(1,10),(10,15),(15,3),...}
RV: X({4,8}) = 12

* C. The number of hearts or spades he takes.
omega = {0,1,2}, structure = {(0,0),(0,1),(1,1),...}
RV: X({0,1}) = 1

Describe the 3 following events:
* For case A. The number of figures is two.
omega = {0,1,2}, structure = {(0,0),(0,1),(1,1)}
RV: X({}) = 2

* Case B: The sum is 17.
omega = {1,2,3,4,5,6,7,8,9,10,10,10,15}, structure = {(1,2),(1,10),(10,15),(15,3),...}
RV: X({10,7}) = 17

* Case C: The number is less than 8.
omega = {0,1,2}, structure = {(0,0),(0,1),(1,1),...}
RV: X({0,1}) = 1


## Challenge 3
Two players roll a dice. Describe the measure space and the random variable for:
* The score for player A
omega = {1,2,3,4,5,6}, structure = {(1,1),(1,2),(2,2)...}
RV: X({4,2}) = 4

* Greatest score
omega = {1,2,3,4,5,6}, structure = {(1,1),(1,2),(2,2)...}
RV: X({2,6}) = 6

* Earnings of player A with the rule “the player that has the greatest score receives a coin for the other player”
omega = {1,2,3,4,5,6}, structure = {0,1}
RV: X({5,2}) = 1

* Earnings of the player A with the rule “the player that has the greatest score receives the difference between the two scores”
omega = {1,2,3,4,5,6}, structure = {0,1,2,3,4,5}
RV: X({5,2}) = 3

Describe the events:
* The score of player A is 2 (case A)
omega = {1,2,3,4,5,6}, structure = {1,2,3,4,5,6}
RV: X({2,4}) = 2

* The greatest punctuation is <=2 (case B)
omega = {1,2,3,4,5,6}, structure = {1,2,3,4,5,6}
RV: X({2,1}) = 2

* If the winner pays the other the difference (case D):
  * A wins at least 4 coins.
  RV: X({6,2}) = 4 
  * A loses more than 2 coins.
  RV: X({2,5}) = 3
  * No one loses.
  RV: X({2,2}) = 0
 

## Challenge 4
Three players take balls. There are red, blue, green and black balls. They can take three balls at most with the following rules:
* If the ball is red they can’t take another ball.
* If the ball is green they earn a point and they can take another ball.
* If the ball is blue they can take another ball.
* If the ball is black one point is removed and they can’t take another ball.

Describe the measure space and the random variable for:
* Player A wins (no tie).
omega = {red, blue, green, black}, structure = {(red),(green,red),(blue, blue, green),(black)...}
RV ({(green,green,blue),(red),(red)}) = 2, 0, 0 

* Player A and B get the same points.
RV({(green, red),(green, red),(red)}) = 1, 1, 0

* All players get 0 points.
RV({(red),(red),(red)}) = 0, 0, 0


## Challenge 5
Now we are four players. What changes for each case?

* Player A wins (no tie).
omega = {red, blue, green, black}, structure = {(red),(green,red),(blue, blue, green),(black)...}
RV({(green,green,blue),(red),(red),(red)}) = 2, 0, 0, 0

* Player A and B get the same points.
RV({(green, red),(green, red),(red),(red)}) = 1, 1, 0, 0

* All players get 0 points.
RV({(red),(red),(red),(red)}) = 0, 0, 0, 0


## Challenge 6
We have 5 balls in an urn, two black and three white. Describe the measure space and the random variable for:
omega = {black,black,white,white,white}, structure = {(black,black,white,white,white),(white,black,black,white,white),...}

* The number of white balls after 3 takes, if every time we take a ball we keep it.
omega = {black,black,white,white,white}, structure = {(black,black,white),(white,black,black),...}
RV({(black,black,white)}) = 2

* The number of white balls after 3 takes, if every time we take a ball we put it again into the urn.
omega = {black,black,white,white,white}, structure = {(black,black,white),(white,black,black),...}
RV({(black,black,white)}) = 3

* The number of black balls after 3 takes, if every time we take a ball we keep it.
omega = {black,black,white,white,white}, structure = {(black,black,white),(white,black,black),...}
RV({(black,black,white)}) = 0

* The number of black balls after 3 takes, if every time we take a ball we put it again into the urn.
omega = {black,black,white,white,white}, structure = {(black,black,white),(white,black,black),...}
RV({(black,black,white)}) = 2
