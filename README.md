# Sudoku Game Project

A C++ Sudoku puzzle generator and solver with an interactive game interface, timer, and leaderboard system.

## Features

- **Sudoku Generation**: Generates random valid Sudoku puzzles using backtracking with randomization.
- **Puzzle Solving**: Includes a solver to check solutions and ensure puzzle uniqueness.
- **Interactive Gameplay**:
  - Play with 3 attempts per game.
  - Timer to track completion time.
  - Fill cells by entering coordinates (row, column, number).
- **Difficulty Levels**: Choose the number of empty cells (1-81) to adjust difficulty.
- **Leaderboard**: Save and view top scores for different difficulty levels in `rekordy.txt`.

## Installation

1. **Requirements**:
   - C++ compiler (e.g., `g++`).
   - CMake (optional, for building).

2. **Build Instructions**:
   ```bash
   g++ sudoku.cpp gamecycle.cpp main.cpp -o sudoku_game
