# TICTACTOE
Java based
game of tic-tac-toe
A board game (such as Tic-tac-toe) is typically programmed as a state machine. Depending on the current-state and the player's move, the game transits into the next-state. In this example, I use a variable currentState to keep track of the current-state of the game, and define named constants to denote the various states of the game (PLAYING, DRAW, CROSS_WON, and NOUGHT_WON).  A method called stepGame() is defined, which will be called to transit into next state.

<<<Rules>>>
In first move I've entered player "X" move at 1st row and 1st column .
It is also know as Noughts and crosses, where noughts is 0 and crosses is X.
After running this program it will ask both player's "X" and "O" to enter there noughts and crosses respectively one by one.  
This process will execute until one player loss or the game will draw. 

If player "X" won it will show :-
'X' won!
Bye!

If the player "O" won it will show :-
'O' won!
Bye!

In the case of draw it will show :- 
It's a Draw! 
Bye!
