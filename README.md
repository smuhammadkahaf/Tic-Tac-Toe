
# Tic Tac Toe (C++)

A simple, interactive console-based Tic Tac Toe game for two players, written in C++ for Windows.


## Features
- Two-player mode with custom player names
- Score tracking across rounds
- Option to restart with swapped players and scores
- Help/instructions menu
- Animated loading and title screen
- Windows-specific console clearing and sleep effects

## How to Play
1. Compile and run the C++ source file (`tickcross_.cpp`).
2. Choose from the main menu:
   - **1. How to play**: View instructions and controls.
   - **2. Start game**: Enter player names and begin playing.
   - **3. Exit**: Quit the game.
3. Players take turns entering the number corresponding to the grid position (1-9) to place their mark (X or O).
4. To restart the game during your turn, enter `r` or `R`.
5. To return to the main menu during your turn, enter `e` or `E`.
6. The game announces the winner or a draw, and displays current scores.

## Controls
- **Grid positions**: Enter 1-9 to mark a cell.
- **Restart**: Enter `r` or `R` during your turn.
- **Exit to menu**: Enter `e` or `E` during your turn.

## Requirements
- Windows OS (uses `system("cls")` and `Sleep()`)
- C++ compiler 

## Build Instructions
1. Open a terminal in the project directory.
2. Compile the source code:
   ```sh
   g++ tickcross_.cpp -o tickcross_.exe
   ```
3. Run the game:
   ```sh
   tickcross_.exe
   ```

## File Structure

## License
This project is for learning purposes. You are free to use, modify, and share it.

## Author
Muhammad Kahaf

---

Enjoy playing Tic Tac Toe!
