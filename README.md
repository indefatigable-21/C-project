# 2048 Game in C++

## Overview

This is a simple implementation of the popular puzzle game "2048" in C++. The game is played on a 4x4 grid, and the goal is to combine numbered tiles to reach the tile with the value of 2048. The game includes features such as sliding tiles, undoing moves, displaying instructions, and checking for a win or loss.


## Features

- **Undo Moves**: The game supports up to 5 undo operations, allowing you to revert to the previous state of the game.

- **Scoring**: You earn points when tiles are merged. The total score is displayed throughout the game.

- **Instructions**: You can view game instructions by entering 'i' during gameplay.

- **Restart**: You have the option to restart the game at any point by entering 'r'.

- **Quit**: To quit the game, enter 'q'.

## How to Play

- To move tiles, use 'w' for up, 's' for down, 'a' for left, and 'd' for right.

- Undo a move by entering 'u'. You can undo up to 5 moves.

- Enter 'r' to restart the game.

- To display instructions, enter 'i'.

- To quit the game, enter 'q'.

## Building and Running

1. Ensure you have a C++ compiler installed (e.g., g++).
2. Compile the code by running the following command:

   ```sh
   g++ -o 2048 2048.cpp
