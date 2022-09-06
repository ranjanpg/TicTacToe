# PG's Tic Tac Toe Game
## Objective
This project aims to develop a game of Tic-Tac-Toe using HTML,CSS and JavaScript. It primarily consists of developing and implementing a responsive website that enables two players to pass and play Tic Tac Toe against one another.

In order to understand how this game is played below is a brief description.

## Game Description
 Tic-Tac-Toe is a two player game played on a 3 x 3 square board.
The players take turns putting marks(the mark must be ‘X’ or ‘O’) on a 3 x 3 board. The goal of this game is to be the first player to three same symbols in a row-horizontally, in a column-vertically or diagonally on a 3x 3 grid. The player who achieves this first is the winner, and the other one loses.
## Game Rules
A player can choose between two symbols with his opponent, usually ‘X’ and ‘O’ are chosen.
The player that gets to play first will get the ‘X’ mark(we call them player 1) and the player that gets the second chance gets the ‘O’ mark(we call them player 2).
Both players take turn playing with player 1 playing mark ‘X’ and player 2 playing mark ‘O’.
A player marks any of the 3x3 squares on the board, and their aim is to create a straight line horizontally,vertically, or diagonally with two intentions: 
One of the players gets three of their marks in a row(vertically,horizontally, or diagonally) i.e that player wins the game.
If no one can create a straight line with their own mark and all the positions on the board are occupied, then the game ends in a draw/tie. 
## Implementation Plan
![Game Implementation Flow Diagram]()
## Code Implementation
In this project , we have made the game using HTML,CSS and JavaScript.

### HTML section
In the HTML section, we first wrote the HTML structure and a title for the game “PG’s Tic Tac Toe.” Then we linked the style sheet or external CSS file in HTML for adding style property to the tags. Then inside the HTML body tag, we made a section in which we gave a title heading.
A div that contains nine cells to create the game board of three by three boxes. After that, we added a tag to show the game status and a button to restart the game if the player wants to play again. Finally, we add a script tag to link the JavaScript file to perform actions.

### CSS section
In the CSS section, we gave styling to the html elements by using tag name or class name. We gave the class name and in curly braces we added the properties that we want to apply on the html tags. Added CSS property to the tags like font-size in pixels, background-color with color value, margin, alignment, font-family, width, height, border,display-flex properties and so on.

### JavaScript section
In the JavaScript section, we defined players with symbols “X” and “O.” isGameover will be false means the game is active for the current player. One player will act, then the current player will change to the second player and vice versa. It will show the status of the game accordingly. Like it’s the turn of “X” or “O,” or one of them won or the game is a tie, etc.

We set the winning conditions according to the sequence of three identical symbols or game logic. There are eight possibilities of winning for each player. On the button click, the game will start again.
 
