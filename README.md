# TicTacToe

Write functions to design a TicTacToe game in Jupyter Notebook.

Step 1: Write a display_board() function that can print out a board. 

        1. First, set up board as a list, where each index 1-9 corresponds with a number on a number pad, so you can get a 3 by 3 board representation.

TEST Step: then write a test code to run the function on a test version of the board list, and make adjustments as necessary.

Step 2: Write a place_marker() function that takes in the board list object, a marker ('X' or 'O'), and a desired position (number 1-9) and assigns it to the board.

TEST Step: run the place marker function using test parameters and display the modified board.

Step 3: Write a win_check() function that takes in a board and a mark (X or O) and then checks to see if that mark has won.

        1. the player (X or O) who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.
        
TEST Step: run the win_check function against test_board - it should return True because X has successfully placed a horizontal row.

Step 4: Write a choose_first() function that uses the random module to randomly decide which player goes first. 

        1. import random.randint()
        
Step 5: Write a space_check() function that returns a boolean indicating whether a space on the board is freely available.

Step 6: Write a full_board_check() function.

        1. check if the board is full.
        2. return a boolean value. True if full, False otherwise.
        
Step 7: Write a player_choice() function.

        1. ask for a player's next position (as a number 1-9).
        2. then use the function from step 5 to check if it's a free position. 
        3. If it is, then return the position for later use.
        
Step 8: Write a replay() function.

        1. ask the player if they want to play again.
        2. return a boolean True if they do want to play again.
        
Step 9: Use while loops and the functions made in the previous steps to run the game!


Thank you!

