# Fibonacci Sequence Generator

## Overview

The **Fibonacci Sequence Generator** is a simple Java console application that prompts the user to enter the number of terms to generate and then prints the corresponding Fibonacci sequence.

The Fibonacci sequence is a series of numbers in which each number is the sum of the two preceding numbers, starting with **0** and **1**.

Example sequence:

```text
0, 1, 1, 2, 3, 5, 8, 13, 21, ...
```

This project is intended for beginners learning Java programming concepts such as loops, user input, variables, and arithmetic operations.

## Features

* Accepts user input for the number of Fibonacci terms.
* Generates the Fibonacci sequence using a `for` loop.
* Displays each term on a new line.
* Uses the `Scanner` class to read input from the keyboard.

## Example Output

```text
Enter the number of terms in the Fibonacci Series
8

Fibonacci Sequence:
0
1
1
2
3
5
8
13
```

## Technologies Used

* Java
* `java.util.Scanner`

## How to Run

1. Save the file as `Fibonacci.java`.
2. Open a terminal or command prompt.
3. Compile the program:

```bash
javac Fibonacci.java
```

4. Run the program:

```bash
java Fibonacci
```

5. Enter the number of Fibonacci terms when prompted.

## Project Structure

```text
day6/
└── Fibonacci.java
```

## How the Program Works

1. Prompts the user to enter the number of terms.
2. Initializes the first two Fibonacci numbers:

   * `a = 0`
   * `b = 1`
3. Uses a `for` loop to generate each term.
4. Prints the current value of `a`.
5. Calculates the next Fibonacci number by adding `a` and `b`.
6. Updates the values of `a` and `b` for the next iteration.

## Learning Objectives

This project demonstrates how to:

* Read user input using `Scanner`.
* Use a `for` loop for repetition.
* Update variables within a loop.
* Generate a mathematical sequence.
* Display formatted console output.

## Future Improvements

Possible enhancements include:

* Display the sequence on a single line separated by spaces or commas.
* Validate user input to ensure a positive number is entered.
* Handle very large Fibonacci numbers using `long` or `BigInteger`.
* Allow the user to generate multiple sequences without restarting the program.

## Author

Created as a beginner Java programming exercise to practice loops, variables, user input, and sequence generation.
