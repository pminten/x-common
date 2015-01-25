Implement the core logic behind a game of 4x4 sudoku.

Your code will be given input events which are either directions (up, down,
left, right) or numbers (1, 2, 3, 4). Your code will be responsible for
updating the internal 4x4 grid and communicating relevant changes.

To show the state of the grid to the user some rendering code is provided. The
rendering code has two operations: setting thehighlighted cell or "marker"
(where the next entered number will end up) and setting the number in a cell.

Your code should allow for optional logging code to be attached. This code
should be invoked when a cell is filled and when the puzzle has been
successfully completed.
