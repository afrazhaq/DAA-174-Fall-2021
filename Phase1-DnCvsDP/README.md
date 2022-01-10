# Group Members:
## Afraz Ul Huq (8886)
## Syed Hamza Haider (62610)

# Hosted Webpage
https://queen-cover-problem.000webhostapp.com/

# How We Approached This Problem
Firstly, We managed to create the ui and script functionality of chessboard. Then, we implemented the Queen Cover Problem. The steps to solve this problem are as follows:

Step 1: Starting from any corner square of the board, find an ‘uncovered’ square (Uncovered square is a square which isn’t attacked by any of the queens already placed). If none found, goto Step 4.

Step 2: Place a Queen on this square and increment variable ‘count’ by 1.

Step 3: Repeat step 1.

Step 4: Now, you’ve got a layout where every square is covered. Therefore, the value of ‘count’ can be the answer. However, you might be able to do better, as there might exist a better layout with lesser number of queens. So, store this ‘count’ as the best value till now and proceed to find a better solution.

Step 5: Remove the last queen placed and place it in the next ‘uncovered’ cell.

Step 6: Proceed recursively and try out all the possible layouts. Finally, the one with the least number of queens is the answer.

# References:
chessboardui:
https://unpkg.com/browse/@chrisoakman/chessboardjs@1.0.0/dist/chessboard-1.0.0.css

chessboard.js:
https://unpkg.com/browse/@chrisoakman/chessboardjs@1.0.0/dist/chessboard-1.0.0.js

Solution code:
https://www.geeksforgeeks.org/minimum-queens-required-to-cover-all-the-squares-of-a-chess-board/
