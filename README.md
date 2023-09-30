# ArkanoidGame
This is a simple implementation of the classic Arkanoid game in Java. Arkanoid is a game where the player controls a paddle to bounce a ball and break bricks.

Features
The game has a graphical user interface (GUI) using Java Swing for rendering.
You can control the paddle using the left and right arrow keys on your keyboard.
Press the spacebar to start the game and release the ball.
The ball bounces off the walls and the paddle.
Bricks are randomly placed on the screen, and the objective is to break all the bricks with the ball.
The game ends when the ball falls below the paddle.

How to Play
Compile and run the Arkanoid class.
Use the left and right arrow keys to move the paddle.
Press the spacebar to release the ball.
Try to break all the bricks without letting the ball fall below the paddle.

Code Structure
The code is organized into several classes:
Arkanoid: The main class that controls the game loop and manages game objects.
Ball: Represents the game ball, including its movement and collision detection.
BaseObject: An abstract base class for all game objects, providing common properties and methods.
Brick: Represents the bricks that the player needs to break.
Canvas: A class for rendering game objects on a canvas.
KeyboardObserver: Handles keyboard input events.
Stand: Represents the paddle controlled by the player.
