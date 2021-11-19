# Knight's_Tour_problem_implementation
Implementing the Knight’s Tour problem in C so that the computer will find the solution automatically 

The Knight’s Tour is a challenge to move a knight from the board game of Chess around
the board landing on all squares but reaching each square only once. Knights move in
an ‘L’ shape (of two squares in one direction and one square at right angles to it or viceversa).

In this project, the computer will select moves by creating a game tree. A game tree consists of all the
possible states of the game and in this assignment the computer determines any possible
solution to be the best one. Each node of the game tree has children that indicate the
states of the game that follow from the state of the parent for each possible move, i.e.
each node in the tree possesses at most 8 children of any node but as more moves are
made, or if a smaller board is used, then there will become less.
