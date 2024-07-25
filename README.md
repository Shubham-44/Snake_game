# Snake_game
 The Snake Game, made with Python's Turtle module, lets players control a snake to eat food and grow longer. Avoiding collisions with walls and the snake's body is the main challenge. Featuring simple graphics and responsive controls, this game is a fun way to learn Python basics, including event handling and collision detection.

Controls
Use the arrow keys to control the direction of the snake:

Up Arrow: Move up
Down Arrow: Move down
Left Arrow: Move left
Right Arrow: Move right
Code Overview

game.py
Sets up the game screen and initializes the snake, food, and scoreboard.
Contains the main game loop to update the screen and handle collisions.

snake.py
Contains the Snake class which handles the creation and movement of the snake.

Methods:
__init__(): Initializes the snake with three segments.
create_snake(): Creates the initial snake.
add_segment(position): Adds a segment to the snake at the specified position.
extend(): Adds a new segment to the snake.
reset(): Resets the snake to its initial state.
move(): Moves the snake forward.
up(): Changes the snake's direction to up.
down(): Changes the snake's direction to down.
right(): Changes the snake's direction to right.
left(): Changes the snake's direction to left.

food.py
Contains the Food class which handles the creation and placement of food for the snake.

Methods:
__init__(): Initializes the food object.
refresh(): Places the food at a new random location.

scoreboard.py
Contains the Scoreboard class which handles the display and update of the game score.

Methods:
__init__(): Initializes the scoreboard.
update_scoreboard(): Updates the score display.
increase_score(): Increases the score.
reset(): Resets the score and updates the high score.
