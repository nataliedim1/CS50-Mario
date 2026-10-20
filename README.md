# CS50x: Mario (More Comfortable)

A robust C program that recreates the iconic adjacent step-pyramids from Nintendo's *Super Mario Bros.*, developed as part of Harvard University's **CS50x: Introduction to Computer Science**.

---

## Problem Overview

The goal of this program is to build two symmetrical, half-pyramids made of hashes (`#`) separated by a fixed two-space gap. The program prompts the user for a pyramid height and validates the input using a `do-while` loop to ensure it falls strictly within a valid bounds range ($1 \le \text{Height} \le 8$).

Features & Implementation Details
Input Validation: Utilizes the CS50 library's get_int function inside a do-while loop to continuously prompt until a valid integer between 1 and 8 is entered.

Nested Loop Logic: Uses outer loops for row iteration and separate inner loops to calculate dynamic padding (spaces) and left/right pyramid blocks (#).

Clean Output Formatting: Ensures consistent two-space gap alignment across all dynamic pyramid heights.

## Prerequisites
To compile and run this code, you will need:

A C compiler (such as gcc or clang)

The CS50 Library (cs50.h) installed, or run the project directly inside the CS50 Codespace.

## Compilation & Execution
Clone the repository:

## Bash
git clone [https://github.com/nataliedim1/YOUR-REPOSITORY-NAME.git](https://github.com/nataliedim1/CS50-Mario.git)
cd CS50-Mario
Compile the program:

## Inside CS50 Codespace / IDE:

Bash
make mario
Using GCC locally:

Bash
gcc mario.c -lcs50 -o mario
Run the executable:

Bash
./mario

### Sample Output (`Height: 4`)

```text
   #  #
  ##  ##
 ###  ###
####  ####

