# Incorrect Winner Determination in Tic-Tac-Toe Dapp

This repository demonstrates a bug in a Tic-Tac-Toe Dapp's winner determination logic. The `checkWinner` function fails to correctly identify a win in certain scenarios, leading to incorrect game results.  The bug and its solution are provided in separate JavaScript files.

**Bug:** The original `checkWinner` function (checkWinnerBug.js) has a flaw that causes it to miss some winning combinations under specific circumstances.

**Solution:** The corrected `checkWinner` function (checkWinnerSolution.js) addresses the identified bug, ensuring accurate win detection in all valid cases.

The solution includes comprehensive testing to validate its correctness and prevent similar issues in the future.