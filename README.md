# Fall 2022 CS170 Project

This is an approximation algorithm for a penguin argument problem. Penguins have different feelings towards some collection of other penguins represented as edge weights in a graph. The problem was to make as few groups as possible with as even a sizing as possible that minimizes the amount of infighting in a group. 

The solution we used was a greedy algorithm that uses simulated annealing to introduce randomness and avoid local minimums. There is a python and a c++ implementation. The C++ implementation also takes advantage of multithreaded workloads to speed up the solver. 
