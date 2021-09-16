# DES-Assignment-1
Automata and Petri nets

Introduction
The objective of this home assignment is to get a deeper understanding of some basic features of discrete event systems. This will be achieved by implementing a few key functions in Python, including the computation of coreachable states, as well as the synchronous composition of two automata. These functions are then applied to the analysis of a simple coordination control system.

This home assignment is performed in two member groups. Write all your answers into this notebook and submit only this notebook (.ipynb) on Canvas

Comments and Recommendations
As before, the following resources will be of great help to you for this assignment:
DES lecture notes
Python docs
Google
Wikipedia overview of syntax and semantics
We will work extensively with sets in this assignment:
A set is created either through set(*iterable*) or by listing its elements between curly braces {*iterable*};
An empty set must be created by set(). {} will create an empty dictionary;
You will also see often something like {elem for elem in items if elem}. This is called a set comprehension and builds efficiently a new set by iterating over items and adding the elem for which the if-statement is true;
Have an extensive look at the set documentation for more information on set methods. Use set methods as much as possible.
The assignment is written for Python 3.5 or later.
If your code passes all the tests in this notebook, you are on a good way. That does not mean you have passed though! We will test your code with additional edge cases. So, convince yourself that everything is correct before you submit, e.g. through your own test cases.
