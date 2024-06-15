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
Locate and eliminate enemy's ships before they do!

- Each player begins with a 10x10 grid and place 5 ships on their grid. All ships are 1 unit wide,
    and with lengths of 5, 4, 3, 3, and 2. These ships can be placed either horizontally or vertically.

- After the preparation stage of placing ships the game alternates between players allowing
    them to select one new position on the opponent’s grid that has not yet been attacked.
  
- The positions are marked once they have been attacked. Red = Hit, Blue = Miss

- Ships which are completely destroyed will be revealed their position on that player's grid.

- Player whose still have remaining ships is the winner.



# 1.3 Game Mechanics

- Marker: Symbolizes the red or blue colored markers that appear on the grid during an attack. These 10x10 are all made at the beginning and, if marked, drawn.
  
- Position: This is used to indicate a position with an x and y coordinate, primarily for grid coordinates, but it is also frequently used to provide pixel offsets for drawing.
  
- Rectangle: Used to represent a generic rectangle with collision detection against a single point and top corner, width, and height.
  
- SelectionGrid: The actual grid that illustrates the locations of cells with a set of lines and holds a collection of markers and ships. incorporates suitable techniques for maintaining the grid's condition.
  
- Ship: This is a term used to describe a ship that is meant to be drawn and keeps track of its position on the grid. When requested by other classes, the ship can also determine whether it has been destroyed.

# 1.4 Future Implementation


