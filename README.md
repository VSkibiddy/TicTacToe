# Tic Tac Toe Web Game

A simple and interactive Tic Tac Toe game built using HTML, CSS, and JavaScript. This project demonstrates basic web development concepts such as DOM manipulation, event handling, and game logic implementation.

## Features

* Two-player gameplay (Player A vs. Player B)
* Player A uses the X symbol
* Player B uses the O symbol
* Turn-based system with on-screen instructions
* Automatic winner detection
* Prevents overwriting occupied cells
* Game starts with a dedicated start button
* Clean and minimal user interface

## Project Structure

TicTacToe/\
│── index.html\
│── x_icon.png\
│── o_icon.png\
└── README.md\

## How to Run the Project

1.Download or clone the repository.\
2.Ensure the following files are in the same directory:
* index.html
* x_icon.png
* o_icon.png

3.Open index.html in any modern web browser such as:
* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Safari

4.Click the "press to start" button to begin the game.

## How to Play

1.Click "press to start" to initialize the game.\
2.Player A begins and places an X on the board.\
3.Player B follows by placing an O.\
4.Players take turns selecting empty cells.\
5.The first player to align three symbols in a:
* Row
* Column
* Diagonal\
wins the game.

6.A popup announces the winner when the game ends.

## Technologies Used

* HTML5 – Structure of the game board
* CSS3 – Styling and layout
* JavaScript – Game logic and interactivity

## Game Logic Overview
* The board is represented by a 3×3 matrix initialized with zeros.
* Player moves are stored as:\
 - 1 for Player A (X)\
 - -1 for Player B (O)
* A player wins when the sum of a row, column, or diagonal equals:\
 - 3 → Player A wins\
 - -3 → Player B wins

## License
This project is intended for educational purposes. You are free to use and modify it.

## Author
Trong Vuong Tran - Developed as part of a web development exercise.
