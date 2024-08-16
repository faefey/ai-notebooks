# Notebooks Containing AI Concepts

This repository showcases the assigments from an artificial intelligence course I have taken.

## [robot_vacuum.ipynb](robot_vacuum.ipynb)

This notebook contains:

* Implementation of a simulated environment for an automatic vacuum cleaner robot

* Randomized agent implementation

* Simple reflex agent implementation

* Model-based reflex agent implementation

* Comparison of the performance of different agents in environments of different sizes

## [maze.ipynb](maze.ipynb)

This notebook contains:

* Defining the search problem (initial state, actions, transition model, goal state, path cost)

* Uninformed search: breadth-first search and depth-first search implementations

* Informed search: greedy best-first search and A* search implementations

* Discussion of loops, complete and optimal implementations, time and space complexities

* Comparison of solutions, path costs, total number of nodes expanded, maximum tree depth, maximum number of nodes, and maximum size of the frontier (with charts)

* Visualizations of search solutions found for mazes

## [tsp2.ipynb](tsp2.ipynb)

This notebook contains:

* Two-person version of the traveling salesman problem (find the two tours which collectively visit each of n cities and minimize the maximum tour length)

* Definition for local moves

* Steepest-ascent hill climbing (with and without random restarts) implementations

* Stochastic hill climbing implementation

* First-choice hill climbing implementation

* Simulated annealing implementation

* Comparison of objective function and number of local moves analyzed for each algorithm

## [mean_connect4.ipynb](mean_connect4.ipynb)

This notebook contains:

* "Mean" Connect 4 (normal Connect 4 with additional rules)

* Defining the search problem (initial state, actions, transition model, test for the terminal state, utility for terminal states)

* Game environment and random agent implementations

* Implementations of transition model, utility function, checking for terminal states, and checking for available actions in each state

* Playing different agents against each other

* Minimax search agent with alpha-beta pruning implementation (with and without cutoff at a specific depth)

* Experimentation with ordering of moves when searching for moves

* Heuristic alpha-beta tree search implementation with custom heuristic evaluation function

## [z3logic.ipynb](z3logic.ipynb)

This notebook contains:

* Sudoku as a constraint satisfaction problem

* Constraints defined and implemented using boolean variables corresponding to each number being in each cell

* Solving Sudoku and the Miracle Sudoku using z3py and defined constraints

* Proving solution uniqueness with z3py solver (finding number of solutions)

* Propositional logic (using both truth tables and z3py to prove logical entailment)

## [MNIST.ipynb](MNIST.ipynb)

This notebook contains:

* MNIST digit dataset (original size and downscaled)

* Splitting dataset into training, validation, and test data while keeping classes balanced

* One linear classifier using one-vs-rest and another using one-vs-one both implemented from scratch

* Comparison of test accuracy for different machine learning models

* Data augmentation

* K-nearest neighbors classifier implemented from scratch

* Neural networks implemented from scratch (only using PyTorch for backpropagation and gradient computation)

* Stopping neural network training based on validation accuracy

* Training neural network with batch and mini-batch gradient descent

* Comparison of different neural network architectures (number of hidden layers, number of neurons, activation functions, mini-batch or batch gradient descent) in training time, number of model updates, and test accuracy