# mooters
its a shooting 2D game using pygames
This code is a basic implementation of a two-player game using the Pygame library.
The code imports the necessary modules and initializes Pygame and the fonts.
It sets the dimensions of the game window (WIDTH and HEIGHT) and creates the window using pygame.display.set_mode().
Various color constants and other variables are defined.
The game assets, such as images and fonts, are loaded and scaled as needed.
The draw_window() function is defined to draw the game window with spaceships, bullets, health bars, and text.
Functions yellow_handle_movement() and red_handle_movement() handle the movement of the yellow and red spaceships, respectively, based on the keys pressed by the players.
The handle_bullets() function moves the bullets, detects collisions with the opposing spaceship, and handles health updates.
The draw_winner() function displays the winner text on the screen.
The main() function initializes the game state, including the positions and health of the spaceships, and enters the game loop.
Inside the game loop, the code checks for events, including quitting the game, firing bullets, and registering hits on spaceships.
If a spaceship's health reaches zero, the winner is determined and the game loop breaks.
The player's key inputs are obtained and used to update the spaceship movements.
Bullets are handled to update their positions and check for collisions.
The draw_window() function is called to update the game window with the current game state.
The main() function is called to start the game
