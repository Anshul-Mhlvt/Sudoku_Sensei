## Live Link
[Sudoku Sensei] (https://anshul-mhlvt.github.io/Sudoku_Sensei/)

## Features

- **Time Complexity** - 9 ^ $(n * n)$, where n is the number of sides of the sudoku board (9 in case of a standard sudoku board).
- User gives a sudoku state as an **input**.
- It uses **Backtracking Algorithm** to solve a particular Sudoku State.
- An **unsolvable state** (wrong sudoku state input) is recognized by the algorithm. 

### 1) Setting the Sudoku State
- User can set the **board state**.
- First, click on the number from the **number pad** which you want to place in the board. This will select that particular number.
- Then select the cell on the board in which you want to place the selected number. This will put that number at that particular cell.
- To **change** the selected number, you have to select the new number from the number pad.
- Number on any cell on the board can be **overwritten** by other numbers by the user, in case a wrong number is placed at that cell.
- There is a **clear button ("C")** which helps to clear any cell which has a number in it. 

### 2) Starting to solve Sudoku Board
- Once the Sudoku state has been set, click the start button for the algorithm to start working.
- If the given Sudoku state has some **ambiguity** (it is not solvable), then it will throw a message that the state is **not valid**. In that case, the user needs to find the mistake and correct it.
- If given Sudoku state is valid, then the algorithm will start doing it's job by running the backtracking algorithm.
- Once the board is solved, the algorithm will be completed and a **solved message** will be shown.


