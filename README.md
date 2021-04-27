# Battleships
Single device game of battleships
Players begin the game by adding their own ships onto a 8*8 battlefield 
The ships cannot overlap, nor can they exceed the scope of the battlefield
The screen is erased after player1 finishes setting up his battlefield so that player2 cannot peak at his ship placement

After player2 finishes setting up his battlefield, the screen is cleared again and the attack window for player one is displayed where player 1 
can see player2's battlefield (all balnk initially and updated after each shot is fired) as well as his own (showing his ships as well as player2's hits/misses)

The state of player1's and 2's fleets are also displayed as lists with 'casualties' shows the ships that were destroyed by the opponent and 'kills' showing the enemy 
ships that were destroyed by the player.

Repeated attacks on the same tile will cause the game to display an error message, the player will get a second chance and has to input fresh coordinates that the shot is aimed at.

The screen is cleared after each player finished his turn.

Victory is achieved either through destroying all of the opponent's ships or through hitting more tiles with ships in them than the opponent when the alloted turns run out. 
