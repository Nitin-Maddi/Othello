# Othello

A high performance Othello AI, which uses the MTD(f) search algorithm to find optimal moves using zero window searches. Additionally uses an edge table which mapped valid edge positions to an edge stability score, which was computed by fully running out a minimax algorithm on each of the 6561 permutations of edge possibilites. Developed a heursitic to judge board state through weighted combinations of various board metrics including mobility, potential mobility, and edge stability.
