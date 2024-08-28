Maze Runner Game: Overview and Mechanics

The Maze Runner game is a text-based adventure where the player navigates through a maze represented by a 2D grid. The grid is implemented using a dynamic 2D character array, showcasing fundamental programming concepts and pointer usage in C/C++.
Key Features:

    Maze Representation: The maze is a grid where each cell can either be a path (*), an obstacle (+), or empty space. The grid is dynamically allocated using pointers, demonstrating the use of dynamic memory allocation and pointer arithmetic.

    Player Navigation: The player moves within the maze by entering commands corresponding to directions: U for up, D for down, L for left, and R for right. This involves pointer manipulation to update the player's position within the 2D array.

    Lives and Moves: The player has a limited number of lives and moves. Colliding with obstacles (+) reduces the player's lives. This feature demonstrates basic control structures and conditionals to manage game state.

    Difficulty Levels: The game offers multiple difficulty levels (easy, medium, hard), with each level determining the size and complexity of the maze. Higher difficulty levels feature larger mazes with more obstacles. This involves pointer-based dynamic memory management to create and handle different maze sizes.

    Winning Condition: To win the game, the player must navigate through the maze and reach the rightmost edge without exhausting all their lives or moves. The use of pointers helps in efficiently checking and updating the game state.

The implementation of the Maze Runner game illustrates fundamental programming concepts such as dynamic memory allocation, pointer manipulation, and control structures, providing a hands-on example of how these concepts can be applied to create an interactive and engaging game.
