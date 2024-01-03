# Minesweeper
This project is an implementation of the classic Minesweeper game using Python. The game consists of a grid (where the dimensions of the grid can be adjusted in code) with cells from 1 to the grid size number. The objective is to click on all possible cells which are not mines. The game is over if the user clicks on a mine or if all cells remaining to be clicked are mines. The user is prompted with a dialog box in both cases.

## How to Play
1. Clone or download the repository.
2. Run the main.py file in any IDE.
3. Click on the cells to start playing.
4. Try to click on as many cells as possible and avoid mines along the way.
5. As soon as the game is over, you will be prompted.
   
## Features
* Interactive gameplay with a counter displaying the number of remaining cells.
* Random assignment of mines at the beginning of each game for a new challenge.
* An option to flag/unflag cells that are potentially mines with a right click.
* Auto click all cells adjacent to the clicked cell if it shows the number 0 (meaning the clicked cell has 0 mines adjacent to it).

## Technologies used
* Python
* Tkinter library

## Compatibility
The game is can be run on any modern Windows machine.

## A legend
1. Red stands for a cell being a mine.
2. Orange stands for a cell being marked or 'flagged' as a mine.

## Credits
This project is created by Aryan Kumar. Feel free to contact me at aryankrkyn@gmail.com for any questions or feedback.

Enjoy playing the Minesweeper game!
