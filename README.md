# Equivalence Testing

This repository contains Pylint exercises from CODIO. It was part of Module 3 (“Secure Software Development”) Unit 5 (Equivalence Testing in Python) of my MSc in Computer Science at the University of Essex, UK.


## Descrition

Run equivalence.py in the Codio workspace - Testing with Python - which is an implementation of equivalence partitioning. This test partitions integers [-3,5] into equivalence classes based on lambda x, y: (x-y)%4 == 0.
In the output, you should be able to see how a set of objects to be partitioned are considered, and a function evaluates if the two objects are equivalent before printing the result.

* test_equivalence_partition() produces the following output:
set([1, -3]) set([2, -2]) set([3, -1]) set([0, 4]) 0 : set([0, 4]) 1 : set([1, -3]) 2 : set([2, -2]) 3 : set([3, -1]) 4 : set([0, 4]) -2 : set([2, -2]) -3 : set([1, -3]) -1 : set([3, -1])


You should carry out further investigations on the code and experiment with it.

## Solution

The recipe includes a test to partition the set of integers [-3,5) into equivalence classes based on the relation lambda x, y: (x - y) % 4 == 0.

An equivalence relation is a relationship on a set, generally denoted by “∼”, that is reflexive, symmetric, and transitive for everything in the set. 

Equivalence relations are relations that have the following properties: 
* They are reflexive: A is related to A. 
* They are symmetric: if A is related to B, then B is related to A. 
* They are transitive: if A is related to B and B is related to C then A is related to C.


## Resources
