# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. How do the performance and efficiency of the Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms compare when solving Sudoku puzzles? In what scenarios might one approach be preferable over the other?

The performance and efficiency of DFS and BFS are different in how they solve each puzzle. DFS is generally more efficient and is better for problems with simpler solutions, while BFS explores each possible outcome to come up with the exact answer, better for accuracy and the complexity of sudoku puzzles.

2. How did the choice of data structures (like the Stack for DFS and Queue for BFS) impact the implementation and functionality of the algorithms? Are there alternative data structures or design patterns that could have been used to achieve the same objectives?

DFS uses a stack data structure, which involves last in first out techniques to efficiently backtrack and solve problems. BFS on the other hand uses a queue data structure, implementing first in first out techniques, fully exploring each possible combination to find the most accurate solution. While there could be alternative search methods to solve the puzzles, DFS and BFS are two of the most simple and widely understood search methods.

3. Considering the current implementation, how might the Sudoku solver be adapted or extended for larger puzzles or different types of grid-based logic games? How can the lessons learned from this assignment be applied to real-world problem-solving or optimization challenges?

To implement the solver for different grid-based puzzles, we could definitely use both BFS and DFS to solve through each possibility, as many grid-based puzzles consist of one-move logic answer paths. Both the concepts and application of search methods are used all around us, from search engines to AI models, search methods are crucial to even the most mundane parts of everyday life.4