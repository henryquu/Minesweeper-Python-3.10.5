# Minesweeper 
Python3, using tkinter. Interface imitiating google minesweeper.

<p align="center">
  <img src="images/interface.png" />
</p>

## Board Generation:
- start generating bombs only after user clicks first cell
- no bombs around user's click
- add bomb count to cells around every bomb
 
## Gameplay:
- click on empty cell reveals all connected horizontally and verticaly empty cells
- click on number reveals it
- click on revealed cell -> do nothing
- right click not revealed cell - mark as bomb
- all non-bomb cells revealed -> win
- click on bomb -> lost game:
    - show all bombs 
    - show wrongly placed flags

##
| Difficulty | Nr of bombs | Height | Width |
| -----------|-------------|--------|-------|
| Easy       |  10         | 8      | 10    |
| Mediu      |  40         |14      | 18    |
| Hard       |  99         |20      | 24    |

## Interface:
- upper frame:
    - difficulty menu
    - counter of unmarked bombs
    - timer
    - restart button
- grid
- highlight hovered cells

## Files:
- board.py - board, cells and everything about them
- game.py - interface
- setup.py - needed constants, function decorator for gating functions 

## Contributing
Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License
License in file LICENSE.txt