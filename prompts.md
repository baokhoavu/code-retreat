# 🌊🚢💥The Game of Battleship

You've been tasked with creating the game of Battleship in JavaScript without the DOM.

# The setup

The game is played on four grids, two for each player. 
The grids are typically square – usually 10×10 – and the individual squares in the grid are identified by letter and number.
On one grid the player arranges ships and records the shots by the opponent. On the other grid the player records their own shots.

Before play begins, each player secretly arranges their ships on their primary grid. 
Each ship occupies a number of consecutive squares on the grid, arranged either horizontally or vertically.

The number of squares for each ship is determined by the type of the ship. 
The ships cannot overlap (i.e., only one ship can occupy any given square in the grid). 
The types and numbers of ships allowed are the same for each player. 

# Class of ship Size
- 1 Carrier 5
- 2 Battleship  4
- 3 Cruiser 3
- 4 Submarine 3
- 5 Destroyer 2

After the ships have been positioned, the game proceeds in a series of rounds. 
In each round, each player takes a turn to announce a target square in the opponent's grid which is to be shot at.

The opponent announces whether or not the square is occupied by a ship, and if it is a "miss", the player marks their primary grid with a white peg; if a "hit" they mark this on their own primary grid with a red peg.

The attacking player notes the hit or miss on their own "tracking" grid with the appropriate color peg (red for "hit", white for "miss"), in order to build up a picture of the opponent's fleet. 
After the player gets a hit the player continues shooting until the player gets a miss.

When all of the squares of a ship have been hit, the ship is sunk, and the ship's owner announces this (e.g. "You sank my battleship!"). 

If all of a player's ships have been sunk, the game is over and their opponent wins.

![image](https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Battleship_game_board.svg/500px-Battleship_game_board.svg.png)

# The Challenge

The game should able to be played automatically without user input.
How will you create and assign ships, then randomly target areas and fire until a winner is picked?

# Pair 0 - Paper and Pencil


