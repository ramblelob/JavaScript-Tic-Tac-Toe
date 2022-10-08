# JavaScript-Tic-Tac-Toe

Requirements: 
Create a new Github repo called JavaScript-Tic-Tac-Toe.
Your local repo should consist of 3 files: index.html, styles.css, script.js.
Remember to commit frequently, ideally after each task.
When finished, publish your project on Github pages.
Optional but highly recommended: do the same project on codepen! :)

Rules of the game. 
Tic-Tac-Toe is a simple and fun game for 2 players, X and O. The game is played on a grid that's 3 squares by 3 squares. Each player's goal is to make 3 of their own mark in a row (vertically, horizontally, or diagonally).
When clicked on an empty cell, X or O will appear, alternately, representing one of the two players. The player who is playing "X" always goes first. Players take turns placing their mark, X or O, on an open square in the grid. The first player to get 3 of her marks in a row (up, down, across, or diagonally) is the winner. 
When all 9 squares are full, the game is over. It's a draw if there's no winner.
If you don't fully understand the rules, or if you haven't played this game before, feel free to play the game online:
https://gametable.org/games/tic-tac-toe/
(select Two Player game)

Steps:
1. Using HTML and CSS, create a board - a grid of 9 squares, 3-by-3, as shown in Image 1 (attached). Each cell is 100px wide and 100px tall. The board is centered in the middle of the page. (Hint: use CSS grid.)

2.  When clicked on an empty square, X or O will appear, depending whose turn it is. Using JavaScript logic, figure out whose turn it is, so the right mark will appear each time. That is, X goes first, O goes next, X goes next, etc.  Make sure that a square is empty before a mark can be placed in it.

3. Check if there's a winner (there are 8 possible winning combinations). To remind, the first player to get 3 of her marks in a row (up, down, across, or diagonally) is the winner. 

4. When one of the players wins, there should appear a semi-transparent overlay (see Image 2, attached) saying "X's Wins! Restart" or "O's Wins! Restart", depending on who is the winner. When clicked on the Restart button, the game starts over.

5. If there's no winner and all 9 squares are filled, there should appear a similar overlay saying "Draw! Restart". Again, when clicked on the Restart button, the game starts over.
