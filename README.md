A classic Connect Four game implementation where two players take turns dropping dots into a grid.
The goal is to connect four dots in a row — horizontally, vertically, or diagonally — before your opponent does.

📖 Overview

Connect Four is a two-player strategy game played on a grid (typically 6×7).
Players alternate turns, dropping their colored dot into a column.
The dot falls to the lowest available space in that column.

The game ends when:

A player connects four dots, or

The board is completely filled (draw)

🛠️ Tech Stack

Language: Java

Concepts Used:

2D Arrays

Loops & Conditions

Functions / Methods

Game Logic

Input Validation

✨ Features

Two-player turn-based gameplay

Real-time win detection

Horizontal, vertical, and diagonal checks

Draw detection

📂 Project Structure
Connect-Four-Game/
│
├── src/
│   └── ConnectFour.java
│
├── README.md
└── .gitignore

🎯 Game Rules

Two players: Player 1 (X) and Player 2 (O)

Players choose a column number on their turn

The dot drops to the lowest empty cell

First player to connect 4 dots wins

If the grid fills up → Draw

▶️ How to Run the Game

###Clone the repository
git clone https://github.com/your-username/connect-four-game.git

###Move to the project directory
cd connect-four-game

###Compile the program
javac ConnectFour.java

###Run the game
java ConnectFour


🧩 Algorithm Used

Grid Representation: 2D array

Move Placement: Bottom-up column scan

Win Detection:

Horizontal check

Vertical check

Diagonal (↘ and ↗) check

Time Complexity:

O(rows × columns) per move check

📌 Use Cases

Java mini project

DSA & logic practice

Interview demonstrations

Game development basics

🔮 Future Enhancements

Add single-player mode (AI opponent)

GUI using Java Swing / JavaFX

Highlight winning dots

Online multiplayer version

Sound effects & animations

👤 Author

Ankur
GitHub: https://github.com/Ankurchoudhary75
Clean and readable logic

Console-based interface (easy to upgrade to GUI)
