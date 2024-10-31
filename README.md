# Quadratic Equation Solver

This is a simple Java program that solves a quadratic equation in the form of `ax^2 + bx + c = 0`. The program calculates and displays the roots of the equation based on user inputs for the coefficients `a`, `b`, and `c`. It also determines if the equation has real roots, a single root, or no real roots at all.

## Table of Contents
- [Project Structure](#project-structure)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Example](#example)
- [License](#license)

## Project Structure

This project contains two files:

- `Main.java`: Contains the main program logic for taking user input and displaying results.
- `QuadraticEquation.java`: Defines the `QuadraticEquation` class, which contains methods to calculate the discriminant and find the roots.

## Features
- Accepts user input for the coefficients `a`, `b`, and `c` to form a quadratic equation.
- Calculates the discriminant to check if the equation has:
  - Two distinct real roots
  - One real root
  - No real roots
- Displays the roots if they exist.

## Getting Started
To run this project, you need:
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) installed on your system.

### Running the Program
1. Clone or download the project files.
2. Compile the code:
   ```bash
   javac Main.java QuadraticEquation.java
   ```
3. Run the compiled program:
   ```bash
   java Main
   ```

## Usage
The program will prompt you to enter three coefficients (`a`, `b`, `c`) for the quadratic equation. It will then calculate the discriminant and display the roots if they exist.

## Example
Here's a sample interaction with the program:

### Input
```
Enter a, b, c: 1 -3 2
```

### Output
```
1.0*x*x-3.0*x+2.0=0
The roots are 2.0 and 1.0
```

If the equation has no real roots, the output will be:
```
The equation has no roots
```