# WordleC - Word Guessing Game

## Introduction

This repo implements a command line interface version of Wordle in C. User has the opportunity to guess a secret word of a specified length (5, 6, 7, or 8 letters) within a limited number of tries. The program provides colored feedback in the CLI.

## Features

- Customizable word length: You can specify the length of the secret word as a command-line argument (5, 6, 7, or 8 letters). If no length is provided, the default word length is 5.

- Colored feedback: The program uses colored text to provide feedback on your guesses. Green letters indicate correct letters in the correct position, yellow letters indicate correct letters in the wrong position, and red letters indicate incorrect letters.

- Limited attempts: You have a limited number of attempts (equal to the word length plus one) to guess the secret word. If you run out of attempts, the game ends.

- Quit option: You can quit the game at any time by entering "quit" as your guess.

## How to Use

Compile the program by running the following command in your terminal:

## Dependencies

- This program uses the CS50 library for some input functions, so you should have the "cs50.h" and "cs50.c" files in the same directory as the program.
