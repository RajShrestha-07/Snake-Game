# Snake

Snake is a small web game. Steer the snake to eat the red squares, and it grows longer each time. The game ends if you hit a wall or your own body. It saves your best score on your device. You can play with the arrow keys or WASD, by swiping on the board, or with the on-screen buttons.

Live demo: https://YOUR-USERNAME.github.io/Snake/

Built with: HTML, CSS and JavaScript.

What this project shows: The game runs on a loop. A timer calls a `tick` function every 130 milliseconds, and each tick moves the snake one square, checks for a crash, and checks if it ate the food. The snake is stored as a list of x and y positions. Each move adds a new head and removes the tail, unless food was eaten, in which case the tail stays and the snake grows. The board is drawn on an HTML canvas. The game also stops you from reversing straight into yourself.

What I'm learning from it: I'm studying how the `tick` function moves the snake and detects crashes, how the food is placed on a free square, and how the canvas is redrawn after every move.
