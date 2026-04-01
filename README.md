Ludo Master: Digital Edition
A fully interactive, web-based version of the classic board game. This project brings the strategy and thrill of Ludo to your browser, featuring smooth animations and logic-driven gameplay for up to 4 players.

🕹️ How to Play
Ludo is a strategy board game for two to four players, in which the players race their four tokens from start to finish according to the rolls of a single die.

Game Modes
Local Multiplayer: Play with  4 friends on the same device.

Basic Rules
Starting: A player must roll a 6 to move a piece out of the base and onto the starting square.

Movement: Pieces move clockwise around the board based on the number rolled on the die.

Capturing: Landing on a square occupied by an opponent's piece sends their piece back to the base.

Winning: The first player to get all 4 pieces into the "Home" triangle wins!

🚀 The Tech Stack
I chose a lightweight but powerful stack to ensure the game remains responsive and accessible across all devices.

HTML5: Structured the game board using a combination of <div> grids for rendering the path.

CSS (Flexbox/Grid): Used to create the iconic cross-shaped board layout. I implemented Media Queries to ensure the board scales perfectly from mobile screens to desktop monitors.

JavaScript (ES6): The engine of the game.

Logic: Managed the state of 16 individual pieces.

Randomization: Used Math.random() to simulate fair die rolls.

Event Listeners: Handled user clicks to select which piece to move after a roll.
