## PROJECT DETAILS

## Project Title: Guess the Number Game
## Author Name: Ajala Timilehin Ayobami
## Peer Reviewer Name: Olaniyi Taiwo

## OVERVIEW

A Number Guessing game: the computer picks a random number; the user guesses it. If they match—you win. Otherwise, try again.

## Goals

Prompt the user for a guess (with a clear range hint).

Generate a random integer in the same range.

Compare the two values with if/else conditional logic.

Print a win/lose message.

## Inputs & Outputs

Input: one integer from the user (e.g., between 1 and 10).

Output: a message:

Win → YES! You beat the matrix

Lose → Ooops! Not this time, try again

## Algorithm (step-by-step)

STEP 1: Import random module based on the programming language being used.

STEP 2: Using the imported random module, generate a random number in the same range then store in another defined variable e.g. computerNumber.

STEP 3: Start a loop that keeps running and requesting new guesses until user guesses the computer's number from STEP 2 correctly.

STEP 4: Display prompt/input field asking the user for a number with a range hint (e.g., “Guess a number between 1 and 10 then press Enter”).

STEP 5: Read/Get the user's input value then store the data into a defined variable e.g. userGuess.

STEP 6: If userGuess is not a number or userGuess is less than 1 or greater than 10, return a message to the user e.g. "Invalid input, keep guessed number within range 1-10", then continue to re-prompt user to guess again.

STEP 7: If userGuess is greater than computerNumber, return a message to the user e.g. "Too high, try again", then continue to re-prompt user to guess again.

STEP 8: Else, If userGuess is less than computerNumber, return a message to the user e.g. "Too low, try again", then continue to re-prompt user to guess again.

STEP 9: Else, If userGuess is equal to computerNumber, return a message to the user e.g. "YES! You beat the matrix", end the loop and program.
