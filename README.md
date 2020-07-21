## Super-hero-connection-using Apache Spark and Python

A program which checks the interconnectivity between any two superheros in the Marvel universe and assigns it a score based on this. The higher the score the less connected are the two superheros. To perform this we use a graph which contains a superhero_ID connected to all other superhero_IDs as nodes and every row indicates one instance where all these superheros appeared together. We combine this with another file which conrains the superhero_ID mapped to their respective name. We perform BFS on the graph with one superhreo as the starting point and traverse the graph until we find the other superhero. The no. of nodes travelled is assigned as the score/distance.


## Techniques Used
1. BFS (breadth first search)
2. Spark
3. Python

## Datasets
The datasets were procured from the udemy course of Big data and spark by Frank Kane.

The two files are:-
'Marvel+Names.txt'- Superhero_ID mapped to names
'Marvel+Graph.txt'- Graph showing interconnectivty of   superheros in the form of appereances. 

## How to run
1. Start Spider or any other pyrhon IDE.
2. Run all cells in `degrees-of-separation.py`.
