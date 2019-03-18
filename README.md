![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# Lab | Statistics Foundations

## Challenge 1
One player rolls two dices. Describe the measure space and the random variable for:
* A. The numbers he/she obtains
* B. The sum of the rolls
* C. Take only the maximum value

## Solution 1.1:
* Ω = {1, 2, 3, 4, 5, 6}

* Structure = {(1, 1), (1, 2), (1, 3), (1, 4), (1, 5), (1, 6), (2, 1), ...}
     
* A: X(1, 6) = (1, 6)
   
* B: X(1, 6) = 7
   
* C: X(1, 6) = 6

Describe the following events:
* For case A: the number is greater than 5
* Case B: The sum is even
* Case C: the maximum is the value of both rolls

## Solution 1.2:
* A: Events = {(5, 5), (5, 6), (6, 5), (6, 6)}
   
* B: Events = {(1, 1), (1, 3), (1, 5), (2, 2), (2, 4), ...}

* C: Events = {(1, 1), (2, 2), (3, 3), ...}

## Challenge 2
One player is taking two cards from poker deck. Describe the measure space and the random variable for:
* A. The number of figures he takes.
* B. The sum of the cards (figures sum 10 and ace sum 15)
* C. The number of hearts or spades he takes.

## Solution 2.1:
* Ω = {Ace, 2, 3, 4, 5, 6, 7, 8, 9, 10, Jack, Queen, King}

* Structure = {(Ace, Ace), (Ace, 2), ..., (2, Ace), (2, 2), ...}

* A: X(Ace, Jack) = 1
   
* B: X(Ace, Jack) = 25
   
* C: X(Ace, Jack) = 0

Describe the 3 following events:
* For case A. The number of figures is two.
* Case B: The sum is 17.
* Case C: The number is less than 8.

## Solution 2.2:
* A: Events = {(Jack, Jack), (Jack, Queen), (Jack, King), (Queen, Jack), (Queen, Queen), (Queen, King), (King, Jack), (King, Queen), (King, King)}
   
* B: Events = {(Ace, 2), (2, Ace), (Jack, 7), (7, Jack), (Queen, 7), (7, Queen), (King, 7), (7, King)}

* C: Events = {(2, 2), (2, 3), (2, 4), (2, 5), (3, 2), (3, 3), (3, 4), (4, 2), (4, 3), (5, 2)}

## Challenge 3
Two players roll a dice. Describe the measure space and the random variable for:
* The score for player A
* Greatest score
* Earnings of player A with the rule “the player that has the greatest score receives a coin from the other player”
* Earnings of the player A with the rule “the player that has the greatest score receives the difference between the two scores”

## Solution 3.1:
* Ω = {1, 2, 3, 4, 5, 6}

* Structure = {(1, 1), (1, 2), (1, 3), (1, 4), (1, 5), (1, 6), (2, 1), ...}
   
* A: X(3, 1) = 3
   
* B: X(3, 1) = 3
   
* C: X(3, 1) = 1

* D: X(3, 1) = 2

Describe the events:
* The score of player A is 2 (case A)
* The greatest punctuation is <=2 (case B)
* If the winner pays the other the difference (case D):
* A wins at least 4 coins.
* A loses more than 2 coins.
* No one loses.
  
## Solution 3.2:
* A: Events = {(2, 1), (2, 2), (2, 3), (2, 4), (2, 5), (2, 6)}
   
* B: Events = {(1, 1), (1, 2), (2, 1), (2, 2)}

* C: Events = {(1, 2), (1, 3), (1, 4), (1, 5), (1, 6), (2, 1), (2, 3), ...}

* D: Events = {(5, 1), (6, 1)}

* E: Events = {(1, 4), (1, 5), (1, 6), (2, 5), (2, 6), (3, 6)}

* F: Events = {(1, 1), (2, 2), (3, 3), (4, 4), (5, 5), (6, 6)}

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

## Solution 4.1:
* Ω = {red, blue, green, black}

* Structure = {(red, red, red), (red, red, blue), (red, red, green), (red, red, black), (red, blue, red), ...}
   
* A: X(green, red, red) = (1, 0, 0)
   
* B: X(green, green, red) = (1, 1, 0)
   
* C: X(red, red, red) = (0, 0, 0)

## Challenge 5
Now we are four players. What changes for each case?


## Challenge 6
We have 5 balls in an urn, two black and three white. Describe the measure space and the random variable for:
* The number of white balls after 3 takes, if every time we take a ball we keep it.
* The number of white balls after 3 takes, if every time we take a ball we put it again into the urn.
* The number of black balls after 3 takes, if every time we take a ball we keep it.
* The number of black balls after 3 takes, if every time we take a ball we put it again into the urn.
