# CSC649: My First Python Experiment

## What the program does

This Python program asks the user to enter a sentence and calculates the number of words and characters in the sentence.

The program also checks whether the user entered an empty input.

## How to run

1. Open the project in PyCharm.
2. Make sure the Python interpreter is Python 3.12 and the project virtual environment is `.venv`.
3. Open `main.py`.
4. Run the program.
5. Enter a sentence when prompted.

## Test Results

### Test 1: Normal sentence

Input:

`Hello my name is Aina`

Result:

`Word count: 5`

`Character count (including spaces): 21`

The program produced the expected result.

### Test 2: Empty input

Input:

Press Enter without typing anything.

Result:

`You did not enter a sentence.`

The program correctly handled the empty input.

### Test 3: Extra spaces

Input:

`Hello     my    name     is    Aina`

Result:

The program correctly counted the words as 5. The character count includes the extra spaces.

## Limitation

The program only counts words and characters. It does not analyse punctuation or determine whether the entered words form a grammatically correct sentence."# CSC649" 
