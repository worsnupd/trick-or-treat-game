## How to use

1. Click on the board. (Required for kicking in React Synthetic Keyboard Events)
1. Use arrow keys to move the player (red) and collect the green sprites.

## App Logic

### Rendering random sprites
For each row, one column is randomly selected and a green sprite is placed in it.

### Counting Moves
Initially moves is assigned -1. A function named `updateMove()` is called inside render method. So this function is called when component first renders and at every re-render. Due to this initial firing of function, we have assigned moves to -1.


## Assumptions

1. Number of sprites is equal to `boardSizeY`.
1. If boardSizeY is 10, then the initial row position of player is 5.