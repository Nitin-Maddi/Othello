# Othello AI

A high performance Othello AI, which uses the MTD(f) search algorithm to find optimal moves using zero window searches.
Makes use of an edge table which maps valid edge positions to an edge stability score, which was computed by fully running out a minimax algorithm on each of the 6561 permutations of edge possibilites. 
Utilizes a heursitic to judge board state through a weighted combinations of various board metrics including mobility, potential mobility, and edge stability.
