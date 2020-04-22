# Conway-s-game-of-life-python
my implementation of the Conway’s game of life in python using **pygame 1.9.6**

![Alt Text](gol.gif)

#### Usage
--- Drawing phase --- \
`MOUSE` - Left and Right click to paint or clear square\
`S` - Stop Drawing Phase and Start Life Phase \
`C` - Clear grid\
`R` - Fill grid at random\
`Q` - Quit Game\
\
\
--- Life Phase ---\
`S` - Stop Life Phase and Start Drawing Phase\
`O` - To Decrease speed\
`P` - To Increase speed\
`Q` - Quit Game

#### Settings
Colors, dimensions of squares, number of row/columns and margin size can be modified in this variables:
```python
# ------------------------ Settings ------------------------ #
# Define some colors
BLACK = (0, 0, 0)
WHITE = (255, 255, 255)
GREEN = (0, 255, 0)

# This sets the WIDTH and HEIGHT of each square in the grid
SQUARE_SIZE = 20
WIDTH = SQUARE_SIZE
HEIGHT = SQUARE_SIZE

# This sets the margin between each cell
MARGIN = 1

# This sets the number of columns and rows
COL_COUNT = 40
ROW_COUNT = 20
```
