# PRODIGY_SD_02

Build a program that generates a random number and challenges the user to guess it. The program should prompt the user to input their guess, compare it to the generated number, and provide feedback if the guess is too high or too Iow. It should continue until the user correctly guesses the number and then display the number of attempts it took to win the game.

explanation:
 Generate a Random Number: The program generates a random number between 1 and 100. This is the number the user will try to guess.

Initialize Attempts Counter: The program keeps track of the number of guesses the user makes.

Print Welcome Messages: The program prints welcome messages to the console, informing the user about the game.

Main Game Loop:

The game runs in a continuous loop until the user guesses the correct number.
The user is prompted to enter a guess, which is then converted to an integer.
Each guess increments the attempts counter by 1.
The program checks if the guess matches the random number:
If the guess is correct, it prints a congratulatory message with the number of attempts and exits the loop.
If the guess is too high or too low, it provides appropriate feedback and continues the loop.
The game continues to prompt the user for guesses and provides feedback until the correct number is guessed.
