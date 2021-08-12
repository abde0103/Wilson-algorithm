# Wilson-algorithm

This algorithm is a way to generate *uniform spanning trees (UST)*

# Main steps

1. Choose any vertex at random and add it to the UST.
2. Select any vertex that is not already in the UST and perform a random walk until you encounter a vertex that is in the UST.
3. Add the vertices and edges touched in the random walk to the UST after removing cycles.
4. Repeat 2 and 3 until all vertices have been added to the UST.
