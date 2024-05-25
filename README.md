# Dealer Distribution System

This C++ project simulates the distribution of products from a company's warehouse to its dealers. The scenario involves a company with 1000 units of a product in its warehouse and 10 dealers placing orders ranging from 0 to 100 units.

## Project Overview

The project involves the following steps:

1. Writing dealer orders, dealer addresses (using pointers), and requested quantities to a file named "orders.txt".
2. Generating a random traversal order for the dealers.
3. Listing the traversal order, dealer addresses, and their respective order quantities on the screen.
4. Writing the traversal order, dealer addresses, and order quantities to the "orders.txt" file.
5. Calculating the remaining product quantity in the warehouse after distribution and displaying it on both the console and the "orders.txt" file.

## Usage

1. Compile the `dealer_distribution.cpp` file using a C++ compiler.
2. Run the compiled program.

```bash
g++ -o dealer_distribution dealer_distribution.cpp
./dealer_distribution
