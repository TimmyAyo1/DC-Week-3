## OVERVIEW

A Number Guessing game: the computer picks a random number; the user guesses it. If they match—you win. Otherwise, try again.

## Goals

Prompt the user for a guess (with a clear range hint).

Generate a random integer in the same range.

Compare the two values with if/else conditional logic.

Print a win/lose message.

## Inputs & Outputs

Input: one integer from the user (e.g., between 1 and 20).

Output: a message:

Win → YES! You beat the matrix

Lose → Ooops! Not this time, try again

## Algorithm (step-by-step)

STEP 1: Display prompt/input field asking the user for a number with a range hint (e.g., “Guess a number between 1 and 20 then press Enter.”).

STEP 2: Import random module based on the programming language being used.

STEP 3: Read/Get the user's input value then store the data into a defined variable e.g. userGuess.

STEP 4: Using the imported randome module, generate a random number in the same range then store in another defined variable e.g. computerNumber.

STEP 5: Using if/else conditional logic, compare userGuess with computerNumber.

STEP 6: If userGuess is equal to computerNumber, return a message to the user e.g. "YES! You beat the matrix"

STEP 7: Else, return a message to the user e.g. "Ooops! Not this time, try again".