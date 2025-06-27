# Instant Insanity challenge from IonQ

## What is the Instant Insanity puzzle?
The Instant Insanity puzzle is a classic recreational mathematics problem involving four cubes. Each face of the four cubes is colored with one of four distinct colors (e.g., Red, Blue, Green, Yellow). The objective of the puzzle is to stack the four cubes in a column such that all four colors appear exactly once on each of the four vertical sides of the stack.

You can start with the interactive visualization: [https://instantinsanity.z20.web.core.windows.net/](https://instantinsanity.z20.web.core.windows.net/)

A strong starting point for understanding this puzzle, its history, and classical encoding and solutions can be found on its Wikipedia page. [https://en.wikipedia.org/wiki/Instant_Insanity](https://en.wikipedia.org/wiki/Instant_Insanity)

5-qubit/cube encoding concept: [https://instantinsanity.z20.web.core.windows.net/switches.html](https://instantinsanity.z20.web.core.windows.net/switches.html)

## The Challenge: Solving Instant Insanity with a QC
For this hackathon, your task is to tackle the Instant Insanity puzzle using a quantum computer. A conventional approach includes the following essential steps; however, feel free to develop innovative concepts:
1. Problem Encoding: Develop a method to encode the classical state of the Instant Insanity puzzle (i.e., the configuration of the cubes and their faces) into a quantum representation suitable for a quantum computer.
2. Objective Function Formulation: Formulate an objective function that, when minimized on a quantum computer, yields a valid solution to the Instant Insanity puzzle. This function should represent the conditions for a correct solution (all four colors appearing once on each vertical side).
3. Quantum Solution: Implement a quantum algorithm to find the solution to the Instant Insanity puzzle based on your encoding and objective function. This may involve using techniques like variational Quantum Imaginary Time Evolution (varQITE), Quantum Approximate Optimization Algorithm (QAOA), Variational Quantum Eigensolver (VQE), or other relevant quantum optimization approaches.

The notebook in this repository demonstrates how to solve the MaxCut problem using the varQITE algorithm, making it an excellent starting point for learning this approach.
   
We encourage participants to explore different quantum approaches and demonstrate the power of quantum computing in solving this classic combinatorial problem.

Submissions will be evaluated on the novelty and originality of their approach, with the aim of fostering a collaborative publication.
