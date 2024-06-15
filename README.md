# DSA Lab Final Project

## Contents

```
1.0 Members
1.1 Introduction
1.2 Game Rules
1.3 Game Mechanics
1.4 Future Implementation
```
# 1.0 Members
```
ITITIU22071 Nguyễn Danh Huy 
ITITIU22064 Nguyễn Minh Hùng
ITCSIU22280 Nguyễn Quách Dịch Thịnh
```
# 1.1 Introduction

# 1.2 Game Rules
Battleship has a simple set of rules that create an enjoyable game through trying to find an opponent’s
ships before they find yours. The rules can be summarised as follow.

- Each player begins with a 10x10 grid and place 5 ships on their grid. All ships are 1 unit wide,
    and with lengths of 5, 4, 3, 3, and 2. These ships can be placed either horizontally or vertically.
- The game starts with the player and their opponent not knowing where the opponent’s ships
    are.
- After the preparation stage of placing ships the game alternates between players allowing
    them to select one new position on the opponent’s grid that has not yet been attacked.
- The positions are marked once they have been attacked, either with a blue marker indicating
    it was a miss in open water, or a red marker indicating a ship was hit.
- Once a ship has been destroyed from all grid positions having been hit, the ship is revealed as
    destroyed to the other player.
- The game ends when all ships for either player’s side have been destroyed. The winner is the
    player with ships still not destroyed.



# 1.3 Game Mechanics

- Marker: Represents the coloured red or blue markers that show up when attacking on the
    grid. All 10x10 of these are created at the start and drawn if they have been marked. They
    keep track of the ship they would represent hitting to allow the AI to get the information.
- Position: Used to represent a position with an x and y coordinate mostly for indicating the grid
    coordinates, but in many cases also to represent pixel offsets for drawing.
- Rectangle: Used to represent a generic rectangle with a top corner, width, and height with
    collision detection against a single point.
- SelectionGrid: The actual grid that contains a collection of markers, ships, and draws these
    with a set of lines to show where cells are. Includes appropriate methods to manage the state
    of the grid.
- Ship: Defines a ship that keeps track of where it is located on the grid and should be drawn.
    The ship can also track whether it has been destroyed to notify other classes when asked.

# 1.4 Future Implementation


