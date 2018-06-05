# N-Queens-problem-implementation
This repository contains the implementation of N-Queens problem in OpenGL


This project details the specification, implementation and verification of N Queen problem. The N Queen is the problem of placing N chess queens on a N*N chessboard so that no two queens attack each other. The main purpose of this project is to specify and verify the abstract model of a C++ program which computes all the possible solution to the n queen problem.

In this project a solution is proposed for n queen problem based on Backtracking algorithm. Backtracking is a standard method to find solutions for a particular kind of problems, known as ‘constraint-satisfaction’ problems. The idea is to place queens one by one in different columns, starting from the leftmost column. When we place a queen in a column, we check for clashes with already placed queens. In the current column, if we find a row for which there is no clash, we mark this row and column as part of the solution. If we do not find such a row due to clashes then we backtrack and return false.

This problem defines a set of constraint to validate any trial. The most primitive way to solve them is Brute force. The n queen problem becomes intractable for large values of ‘n’ and placed in NP class Problem. In n-queen problem, the goal is to place ‘n’ queens such that no queen can kill other using standard chess queen moves. The Solution can very easily be extended to the generalized form of the problem for the large value of ‘N’. The project contains problem background, complexity and conclusion.
