# Unity - Cellular Automata

## Rules for Conways GOL
- 1 - any live cell with 2 or 3 neighbors survives
- 2 - any dead cell with 3 live neighbors becomes a live cell
- 3 - all other live cells die in the next generation and all other dead cells stay dead

## Game
- Intializes grid with random live cells
- Population Control - kills/revives cells based on conways rules
- Count Neghbors - iterates through grid to get num neighbors for each cell

## Cell
- stores cell neighbor count and life status

## Example run in Unity:
![Alt Text](https://github.com/brycehills/Unity---Conways-Game-of-Life/blob/main/Assets/Resources/gol.gif)
