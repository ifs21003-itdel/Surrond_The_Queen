# Surrond_The_Queen
A simple game program project created using the python language. This game is still not perfect and I won't continue it because I'm busy studying, sorry.

# How To Play
  players play against a computer program by moving rook pieces that can move only horizontally and vertically. For queen pieces, the queen can also only move    
horizontally and vertically and move. Both sides' pieces cannot eat each other and only the player's pieces can trap the queen. Here's the gameplay:

1. Players will be asked for input in the form of the number of pieces they want in the range 4 - 10.
2. The player's pieces will be placed randomly along with the queen and the user can move his pieces.
3. The player can select the pawn cell that he will move by using the <strong>left mouse button</strong> first and a red mark on the pawn box will appear indicating that the player selected that pawn.
4. The player selects the cell as the moving position of the selected object horizontally or vertically using the <strong>right mouse button</strong>.
5. Players can continue to move one of their pieces in one turn until they can trap the queen.

# How Bot Works
  This game is an implementation of the Best First Search concept where the queen will move based on a heuristic value. The heuristic value in question is the number of player pieces that can surround them in the cell in question. The queen will continue to move in turn randomly to cells with a heuristical value of zero. If there are no cells with a heuristic value of zero, the player is declared the winner and the game ends.

# How To Run
  Players can run this program through Command Prompt or Run in Visual Studio Code
