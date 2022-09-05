# Camel
Camel is a schema matching system for data lakes. It reframes the schema matching for data lakes problem into an entity matching problem, then solves the problem using state-of-the-art entity matching solutions.

We are currently only releasing the data lakes used in the paper. Each data lake contains two folders: *csv* and *catalog*. The *csv* folder contains all the tables for the current data lake in csv format. The *catalog* folder contains a csv file, *catalog.csv*, which contains the gold matches. In *catalog.csv*, each row is a column of a table of the current data lake. Two rows of *catalog.csv* is a match if they have the same *Label*.
