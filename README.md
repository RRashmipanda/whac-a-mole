# Live
 https://rrashmipanda.github.io/whac-a-mole/

# Project Overview:

Whack-a-Mole Game: Developed a browser-based interactive "Whack-a-Mole" game using vanilla JavaScript, HTML, and CSS.


# Tile Setup:
Created a 3x3 grid of tiles dynamically in JavaScript.

# Mole and Plant Appearance: 
Implemented timed intervals to randomly place mole and plant images on the grid.

# Dynamic Grid Creation:

Utilized a loop to create 9 tiles, each with a unique ID and click event listener.

Appended the tiles to a container element in the HTML (e.g., a div with the id "board").

# Random Tile Selection:

Random Function: Used Math.random() and Math.floor() to generate random tile indices for mole and plant placement.

Ensured that mole and plant do not occupy the same tile simultaneously.

# Timed Events:

Mole Interval: Set an interval to place the mole on a random tile every second.

Plant Interval: Set an interval to place the plant on a random tile every two seconds.

# Game Logic:

Score Handling: Increased the score by 10 points when the mole tile is clicked.

Game Over Condition: Ended the game when the plant tile is clicked, displaying the final score.

# Event Handling:

Tile Click Events: Attached event listeners to each tile to handle game interactions.

Update Score: Updated the score in the HTML dynamically based on user actions.

# Image Handling:

Dynamically created image elements for the mole and plant, setting their src attributes to corresponding image files.

Cleared previous images from the tiles before placing new ones to ensure only one mole or plant is visible at a time.

# Game State Management:

State Variables: Managed the game state using variables (currMoleTile, currPlantTile, score, gameOver).

Conditional Logic: Implemented conditions to check for game-over state and prevent further interactions once the game is over.
