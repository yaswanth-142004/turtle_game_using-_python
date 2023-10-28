# turtle_game_using-_python
This Python code is for a simple game where you control a player character that needs to avoid oncoming cars. Here's a brief description of the code:

    1.The code imports necessary modules, including the time module for time-related functions and three custom modules: player, car_manager, and scoreboard.

    2.It sets up the game screen with a width and height of 600x600 pixels and turns off automatic screen updates for smoother animation.

    3.The player character is created using the Player class, and a car manager is initialized with the CarManager class. A scoreboard is also created using the Scoreboard class.

    4.The code listens for key presses on the "Up" arrow key, allowing the player character to move upwards.

    5.The main game loop is initiated with game_is_on = True. Inside this loop:

    6.The game sleeps for 0.1 seconds to control the game's speed.
    7.The screen is updated to show changes in the game.
    8.The car manager creates new cars and moves existing ones in the game.

    9.It checks for collisions between the player character and the cars. If a collision is detected (i.e., the player character's distance from any car is less than 20 pixels), the game ends, and the "game over" m 
     message is displayed on the scoreboard.

    10.The code also checks if the player character successfully crosses the finish line. If the player reaches the finish line, their position is reset to the starting point, the car manager's level increases (making the game more difficult), and the player's level on the scoreboard is updated.

    11.The game loop continues until the player decides to exit by clicking on the game window.
