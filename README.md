# matrix
# Matrix Script Decoder

## Description

The Matrix Script Decoder is a Python program designed to decode a complex matrix script composed of alphanumeric characters, spaces, and symbols. The script reads the matrix column by column, extracting alphanumeric characters and replacing sequences of symbols or spaces between them with a single space for better readability.

## Features

- Reads a matrix of strings defined by user input.
- Decodes the matrix by reading it column-wise.
- Cleans the output by removing unwanted symbols and spaces between alphanumeric characters.

## Requirements

- Python 3.x
- No additional libraries are required other than the standard library.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/bondpapi/matrix.git

   cd matrix

   python matrix.py

## Input Format

R C

row1

row2

...

rowR

# Example
# Input:
7 3

Tsi

h%x

i #

sM

$a

#t%

ir!

# Output:

This is Matrix


