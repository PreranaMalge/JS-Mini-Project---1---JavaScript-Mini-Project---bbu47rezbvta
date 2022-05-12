# Flappy Bird:
Flappy Bird is an endless game that involves a bird that the player can control. The player has to save the bird from colliding with the hurdles like pipes. Each time the bird passes through the pipes, the score gets incremented by one. The game ends when the bird collides with the pipes or falls down due to gravity. The sections below describe the steps that have to be taken for building this game.

# HTML Section:
 In this section, the elements of the game are created and loaded. The images for the background, bird, hurdles and the score elements are selected.
 Next, we create and link the styles.css and App.js file.

# CSS Section: 
In this section, the size, position and style of the game objects are modified according to need.

# JavaScript Section:
 This section contains the part of the code that controls the game state and the moving objects. The following steps have to be followed in this section.

        ✤ Get a reference to bird and background image in JavaScript file.

        ✤  Set some values for background scrolling speed, the flying speed of the bird. 
        
        ✤  Apply collision with ground and pipes and if the bird collides then change the game state to end state and show a message to restart the game.

        ✤ Increment score value after every successful navigation between the pipes.
        