# Polynomial Assignment

# Polynomial Interpolation using Lagrange Formula

## Description

This project calculates the constant coefficient of a polynomial using
Lagrange interpolation.

## Technologies Used

- Java
- BigInteger
- Gson
- JSON

## Input

The input is provided through a JSON file containing:
- n
- k
- x values
- base
- encoded y values

## Process

1. Read the JSON file.
2. Extract n and k.
3. Convert the encoded y values from their respective bases.
4. Create the coordinate points.
5. Apply Lagrange interpolation.
6. Calculate P(0).
7. Print the constant coefficient.

## Formula

P(0) is the constant coefficient of the polynomial.

## How to Run

Run `Main.java` using Eclipse.

Gson library is required for reading the JSON file.
