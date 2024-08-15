# wumpus-world
an interactive Wumpus World game involves building a grid-based game where the player can move around, sense the environment, and take actions.
Wumpus World game environment will include a grid with pits, a Wumpus, gold, and breeze/stink indicators.

functions and methods:
WumpusWorld Class: Manages the game state, including the positions of the Wumpus, gold, pits, and player. It also handles the perceptions (stench and breeze) and player movements.

generate_world and place_entity Methods: Randomly place the Wumpus, gold, and pits on the board, ensuring no overlaps with each other and the player’s starting position.

set_perceptions Method: Set the stench and breeze indicators adjacent to the Wumpus and pits.

move_player Method: Move the player based on the given direction and check the new position for game events (e.g., encountering the Wumpus, falling into a pit, or finding gold).

perceive Method: Provide feedback to the player based on the current position.

display_world Function: Visualize the game state using matplotlib, displaying the grid and the positions of the player, Wumpus, gold, pits, and perceptions.

on_key Function: Handle keyboard events for moving the player.
