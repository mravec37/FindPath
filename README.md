# Find Path in a Maze

## Problem Description

The goal of this project is to create an algorithm that finds a path from a start position** to a target position in a maze.

The maze is represented as a rectangular 2D grid of characters.

### Maze Rules

- `.` – free cell  
- `#` – blocked cell  
- `S` – start position (exactly one)  
- `X` – target position (exactly one)

### Movement Rules

- Allowed moves:
  - `u` – up
  - `d` – down
  - `l` – left
  - `r` – right
- Diagonal movement is **not allowed**
- Movement is allowed only through free cells (`.`) and the target (`X`)

## Input

The algorithm must accept maze input in two ways:

1. **Standard Input**
2. **File Input**

Each input method must be implemented as a separate class:

- `AbstractFindPathInputReader` (base class)
- `FindPathInputReaderStdIn` (reads from standard input)
- `FindPathInputReaderFile` (reads from a file)

## Output

- If a path exists:  
  Output a sequence of steps (`u`, `d`, `l`, `r`) that leads from `S` to `X`
- If no path exists:  
  Output an error or message indicating that no path was found

## Example Maze

