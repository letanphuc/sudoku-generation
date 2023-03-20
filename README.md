# Sudoku Generation

generate 4x4, 9x9, 16x16 sudokus with a unique solution.

------


## Usage

`SudokuGenerator(size).sudoku(removeCellCount, maxGenerationTime);`
- where `size` can be 2, 3 and 4, which means 4x4, 9x9 and 16x16 sizes.
- `removeCellCount` is the number of cells you want to remove, you can also specify `INT_MAX` directly if you want to remove as many cells as possible
- `maxGenerationTime` indicates the maximum execution time of the generating program. If `maxGenerationTime` is reached without removing the specified `removeCellCount` cells, the program will return the result of removing as many cells as possible.


## Example
```
Enter sudoku size(choose 2, 3 or 4) :(eg. 3)
3
Enter sudoku remove count:(eg. 60)
60
Enter max generation time:(eg. 3)
4

Remove 58 Cells
Remain 23 Cells
Sudoku Board:
. . 8 | . . . | 5 . . 
. . . | . 8 1 | . 3 . 
. 7 . | . . . | 2 . . 
- - - - - - - - - - - 
. 4 . | . . . | 6 . . 
. . . | 9 . . | . . 2 
. . . | 3 7 . | 8 . 5 
- - - - - - - - - - - 
. . 3 | 6 . 5 | . . . 
. . . | . . 3 | . . 6 
. 1 . | . . 2 | . 7 . 

Sudoku Answer:
1 2 8 | 4 3 7 | 5 6 9 
9 5 6 | 2 8 1 | 4 3 7 
3 7 4 | 5 6 9 | 2 8 1 
- - - - - - - - - - - 
5 4 7 | 1 2 8 | 6 9 3 
8 3 1 | 9 5 6 | 7 4 2 
2 6 9 | 3 7 4 | 8 1 5 
- - - - - - - - - - - 
7 9 3 | 6 4 5 | 1 2 8 
4 8 2 | 7 1 3 | 9 5 6 
6 1 5 | 8 9 2 | 3 7 4 
```

## License

Sudoku Generation is available under the MIT license. See the LICENSE file for more info.