# NSLS
A local search algorithm based on non-dominated sorting for solving the minimum weight minimum connected dominating set problem (MWMCDS)

1- Context

In graph theory, a dominating set (DS) for a simple undirected graph G = (V, E) where V is the set of vertices and E is the set of edges, is a subset D of V such that each vertex not in D has at least one neighbor in D. If its induced subgraph G(D) is connected then it represents a connected dominating set (CDS). The minimum weight minimum connected dominating set problem (MWMCDS) is a bi-objective optimization problem defined on a simple undirected edge-weighted graph as a CDS with minimum cardinality and minimum total weight.

2- Data Description

Two types of datasets were used in this work :

DataSet1: it contains 9 instances of graphs that are undirected and edge-weighted.

DataSet2: it contains 360 problem instances, and each instance consists of an undirected vertex-weighted graph. Since the MWMCDS problem necessitates an edge-weighted graph, the weight of each edge is derived by averaging the weights of its endpoints.  The number of edges m is varied for each vertex count n, and for a specific number of vertices and edges, 10 instances exist for most graphs.

3- .exe file

A greedy randomized local search algorithm based on a non-dominated sorting concept named NSLS is proposed to solve the MWMCDS problem. The program code is entirely written in C++ language on Visual Studio IDE, and the executable version produced is NSLS.exe.
