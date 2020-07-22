# graph-mining
This project conducts graph mining using R. First I compute the minimum spanning tree and some classical graph mining statistics (density, length, reciprocity, etc). I then build centrality measures:
- Closeness centrality: actors high in closeness are able to efficienctly transmit information and have independance in the sense that they do not need to seek information from other more peripheral actors
- Betweeness centrality: Betweeness centrality measures the extent to which an actor lies between other actors on their goedesics. Able to influence both in direct and indirect
- Eigenvector centrality: eigencentrality is a measure of the influence of a node in a network. It assigns relative scores to all nodes in the network based on the concept that connections to high-scoring nodes contribute more to the score of the node in question than equal connections to low-scoring nodes.
