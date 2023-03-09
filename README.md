# Lab-Assignment--3
CS-362 Artificial Intelligence Lab 

## Abstract
Travelling Salesman Problem (TSP) is a hard problem, and is simple to state. Given a graph in which the nodes
are locations of cities, and edges are labelled with the cost of
travelling between cities, find a cycle containing each city exactly
once, such that the total cost of the tour is as low as possible.
## Learning Objective : 
Non-deterministic Search — Simulated Annealing For problems with large search spaces,
randomized search becomes a meaningful option given partial/
full-information about the domain.

## Problem:
Travelling Salesman Problem (TSP) is a hard problem, and is simple to state.  Given a  graph in which the nodes are locations of cities, and edges are labelled with the cost of travelling between cities,  find a cycle containing each city exactly once, such that the total cost of the tour is as low as possible.

For the state of Rajasthan, find out at least twenty important tourist locations.  Suppose your relatives are about to visit you next week.  Use Simulated Annealing to plan a cost effective tour of Rajasthan.  It is reasonable to assume that the cost of travelling between two locations is proportional to the distance between them.


## VLSI Datasets :

## For Rajasthan :

## Results :

By this experiment, We came to know about Simulated Annealing.
Simulated Annealing (SA) is a heuristic algorithm used to solve optimization problems. One such problem is the Travelling Salesman Problem (TSP), where the objective is to find the shortest possible route that visits each city in a given list exactly once and returns to the starting city.

In the context of the TSP, the SA algorithm works by starting with an initial solution (i.e., a random tour) and iteratively improving it by making small changes. The algorithm then accepts these changes according to a probability function, which is based on a parameter called the temperature.

During the early stages of the algorithm, the temperature is set high, and the algorithm is allowed to accept worse solutions with a higher probability. This is because a high temperature allows the algorithm to explore a larger portion of the search space, potentially finding better solutions that may be far away from the initial solution.

As the algorithm progresses, the temperature is gradually reduced, which reduces the probability of accepting worse solutions. This allows the algorithm to converge towards a better solution as the temperature approaches zero.

The SA algorithm can be applied to the TSP by considering a set of neighboring tours that can be obtained by swapping two cities in the current tour. The probability of accepting a worse solution is given by the Metropolis criterion:

P = e^(-ΔE / T)

Where P is the probability of accepting the new solution, ΔE is the change in energy (i.e., the length of the tour) between the new and current solutions, and T is the current temperature.

By iterating this process, the SA algorithm can converge towards an optimal solution for the TSP, although it may not guarantee finding the optimal solution due to the random nature of the algorithm. However, SA is known to be effective in finding good solutions for the TSP and other optimization problems.
