# Chess_Endgame
Objective    Build a machine learning model to calculate the depth of win (i.e. the number of moves required to win the game).

#Problem Statement
 

Chess endgames are complex domains which are enumerable. Endgame databases are tables of stored game-theoretic values for the enumerated elements (legal positions) of the domain. The game-theoretic values stored denote whether or not positions are won for either side, or include also the depth of win (number of moves) assuming minimax-optimal play.

#Data description

There are six attribute variables and one class variable (i.e. optimal depth-of-win).

 

Attribute Information:

   1. White King file (column)

   2. White King rank (row)

   3. White Rook file

   4. White Rook rank

   5. Black King file

   6. Black King rank

   7. optimal depth-of-win for White in 0 to 16 moves, otherwise drawn

{draw, zero, one, two, ..., sixteen}.
