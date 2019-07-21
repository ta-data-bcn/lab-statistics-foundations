# SOLUTIONS UNDER EACH CHALLANGE

## Challenges
### Challenge 1
One player rolls two dices. Describe the measurable space and the random variable for:
* A. The values that the player obtains.
* B. The sum of the values obtained.
* C. The maximum value obtained after rolling both dices.

Describe the following events:
* Case A: Both values are greater than 5.
* Case B: The sum of values is even.
* Case C: The maximum is the value of both rolls.

# SOLUTIONS
- measureable_space = ((1/1), (1/2), (1/3), (1/4), (1/5), (1/6), (2/1), (2/2), (2/3), (2/4), (2/5), (2/6), (3/1), (3/2), (3/3), (3/4), 
                           (3/5), (3/6), (4/1), (4/2), (4/3), (4/4), (4/5), (4/6), (5/1), (5/2), (5/3), (5/4), (5/5), (5/6), (6/1), (6/2),
                           (6/3), (6/4), (6/5), (6/6))
* A (1/2) = (1/2)
* B (1/2) = (3)
* C (1/2) = (2)

* Case A:
    - Events:       X(x|y >5) = (6/6)

* Case B:
    - Events:           X {(x+y) % 2 == 0} = ((1/2), (1/4), (1/6), (2/1), (2/3), (2/5), (3/2), (3/4), (3/6), (4/1), (4/3), (4/5), (5/2),
                                               (5/4), (5/6), (6/1), (6/3), (6/5))
                                
* Case C:
     - Events:           X(x=y) = ((1/1), (2/2), (3/3), (4/4), (5/5), (6/6))

### Challenge 2
One player picks two cards from a poker deck. Describe the measurable space and the random variable for:
* A. The number of figures he picks.
* B. The sum of card values. Consider that the value of figures is 10 and the value of aces is 15.
* C. The number of hearts or spades he picks.

Describe the following events:
* Case A: The number of figures in the cards the player picked is two.
* Case B: The sum of card values is 17.
* Case C: The value of both cards is less than 8.


# SOLUTIONS

MEASURABLE_SPACE = ( (Ace_hearts/Ace_hearts),  (Ace_hearts/2_hearts), (Ace_hearts/3_hearts), ..., (King_leaf/Queen_leaf),
                    (King_leaf/King_leaf))

* A : X(_leafAce_h_leafea_leafr ... = (17)
* C : X(Ace_hearths/2_hearts) = (2)

* Case A: (count figures) = (A_leaf/A_otherSign),(A_leaf/A_spades),(A_leaf/A_hearts), (A_leaf/J_leaf), (A_leaf/Q_leaf), (A_leaf/K_leaf) ...
                            (K_hearts/K_spades)
* Case B: (x+y = 17) = ((A_leaf/2_otherSign),(A_leaf/2_spades),(A_leaf/2_hearts), (A_leaf/2_leaf) ... (K_hearts/7_leafs)
* Case C: (x&y <7) = (2/2), (2/3), (2/4), (2/5), (2/6), (2/7) (3/2), (3/3), (3/4), (3/5), (3/6), (3/7), (4/2), (4/3), (4/4), (4/5), (4/6) ,
                     (4/7), (5/2), (5/3), (5/4), (5/5), (5/6), (5/7), (6/2), (6/3), (6/4), (6/5), (6/6), (6/7), (7/2), (7/3), (7/4), (7/5),
                     (7/6), (7/7)
### Challenge 3
Two players roll a dice. Describe the measurable space and the random variable for:
* A. The score of player A.
* B. The greatest score.
* C. The earnings of player A if the game rules state that:  
"The player with the greatest score gets a coin from the other player.".
* D. The earnings of player A if the game rules state that:  
"The player with the greatest score gets as many coins as the difference between the score of player A and player B.". 

Describe the following events:
* Case A: The score of player A is 2.
* Case B: The greatest score is lower or equal than 2.
* Case C: Considering the case where the winner gets as many coins as the difference between scores (D), describe: 
  * Player A wins at least 4 coins.
  * Player A loses more than 2 coins.
  * Player A neither wins nor loses coins.
  
  
# SOLUTIONS

- measureable_space = ((1/1), (1/2), (1/3), (1/4), (1/5), (1/6), (2/1), (2/2), (2/3), (2/4), (2/5), (2/6), (3/1), (3/2), (3/3), (3/4), 
                           (3/5), (3/6), (4/1), (4/2), (4/3), (4/4), (4/5), (4/6), (5/1), (5/2), (5/3), (5/4), (5/5), (5/6), (6/1), (6/2),
                           (6/3), (6/4), (6/5), (6/6))
* (Player A/ Player B)
* A : X(3) = (3)
* B : X(3/4) = (4)
* C : X(3/4) = Player A gives a coin to Player B
* D : X(3/5) = Player A gives two coins to Player B

* Case A                 
    - Events:    X(2/y) = (2)

* Case B
    - Events:    X(x|y <= 2) = ((1/1),(1/2), (2/1) (2/2))

* Case C
    - Events     X(Player A gets at least 4 coins) = (6/1), (6/2), (5/1)
    -            X(Player A loses more than 2 coins) = (1/4), (1/5), (1/6), (2/5), (2/6), (3/6)
    -            X( Player A neither wins nor losses coins) =  (1/1), (2/2), (3/3), (4/4), (5/5), (6/6),


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