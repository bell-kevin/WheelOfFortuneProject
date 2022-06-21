# WheelOfFortuneProject
SDEV 2210 Project. In this game, the user guesses letters to see if they appear in a secret word. Create a project that simulates this game. You will use a 2D array – the first row holds the letters of the secret word, and the second row holds symbols until the letter is guessed. When displaying the board, you would only display the second row, the guessed letters. Ask the user to guess a letter, check if it appears anywhere in the secret word, and if it does, change the symbol in the second row to the guessed letter. For example, if the user guessed the letter “e”, you would find that letter in the first row in in cell 6, and so would change cell 6 in the second row to show that same letter. After each guess, tell the user how many times that letter was found and redisplay the board. Check if the game is over by checking if there are any symbols left in the second row of the array. If there are, that letter hasn’t yet been guessed, so the game is not over.  Create a class for the game and a driver class. In the Game class, use instance variables for the 2D array for the board, and the length of the secret word. The constructor needs no parameters, and will instantiate the 2D array and fill it with the letters of the secret word and the symbols. Note: for this version, you will hard-code a “secret” word into the game array. Make sure it is at least 6 letters long, and must have at least 1 letter that appears more than once in the word. For the sample session, the secret word is “generator”. Create a method to display the board – the second row of the array, with the symbols and guessed letters. Create a method to find a letter that is passed in as a parameter. Every time that letter is found in the secret word, count it, and display how many times the letter was found as well as the new version of the board. That means you will call the display method inside of the method to find a letter. Create a method that returns a Boolean that tells the driver class that the game is over.  In the driver class, write code that matches the following pseudocode:         Create a new game        Display the board        While game is not over              Ask the user for a letter              Call the method to find that letter (which displays the results)              Check if the game is over        Print “Congratulations, game is over” Take a screenshot of one successful play of the game.     Submission: the specified screenshot, and the root folder for the project     Pay careful attention to the rubric for this assignment. Remember the standards that apply to every project.  Note that you must use correct formatting in the code -- appropriate indentation is most important. You can use Shift-Alt-F to have NetBeans automatically format the code correctly. If the formatting is incorrect, it will be returned to you for changes with a grade of zero.  Note: You need to submit the whole project for these assignments. In File Explorer, go to the location where you created the project. There will be a folder with the name of your project -- that is the root folder of the project.  If you submit the root folder of the project, the instructor can run it on a different machine to grade it. If you don't submit the proper folder, it won't run on another machine, and the assignment will be marked with a zero.
