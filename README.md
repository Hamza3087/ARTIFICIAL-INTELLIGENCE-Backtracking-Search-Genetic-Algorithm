# ARTIFICIAL-INTELLIGENCE-Backtracking-Search-Genetic-Algorithm

BACKTRACKING 
Sudoku is the Japanese word for “single numbers”, and refers to numerical puzzle game that
has become popular in newspapers and game publications all over the world. Although the
rules for this puzzle are simple to understand, the solutions can range from the very simple to
the agonizingly difficult. This assignment will require you to develop a Sudoku solver by
applying search algorithms with
heuristics to solve a puzzle.

1. The digits to be entered are 1, 2, 3, 4, 5, 6, 7, 8, and 9.
2. A row is 9 cells wide. A filled-in row must have exactly one of each digit. There is 9
rows in the grid, and the same constraint applies to each of them.
3. A column is 9 cells tall. A filled-in column must have exactly one of each digit. There
are 9 columns in the grid, and the same constraint applies to each of them.
4. A box contains 9 cells in a 3-by-3 layout. A filled-in box must have exactly one of
each digit. There are 9 boxes in the grid, and the same constraint applies to each of
them

GENETIC ALGORITHM 
The magic square is a square matrix, whose order is odd and where the sum of the elements for
each row or each column or each diagonal is same. The sum of each row or each column or
each diagonal can be found using this formula. n(n2+ 1)/2. Consider the following example
puzzle called “Moving Magic Square”. It is played on a 3 × 3 table containing each of the
numbers 1 to 9. The number 9 is the “movable number”. You can move 9 in four directions
(up/down/left/right), and swap 9 with the number in that direction. The initial state is shown in
Table 1. As the player, we want to move 9 to reach a final state such that the sum of the three
numbers on every row, column, and diagonal is 15. There are multiple states that satisfy this
condition, and you can stop your answer when you find the first satisfied state.
You are to write programs to generate and solve
classic 3x3 magic square puzzles. However,
because you will generate random puzzle
instances, they may have zero, one, or more
solutions.
You are required to apply Genetic Algorithm.
