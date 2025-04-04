# greedy-coloring-algorithm
Greedy Algorithm for for determining the Chromatic Number of a graph.

## What Is
In Graph Coloring, the Chromatic Number of a graph G, χ(G) chi of G, is the smallest number of colors k such that there is a valid k-coloring of G.  
G = (V,E) and undirected graph  
C = a finite set of colors  
A valid coloring is a function f: V → C such that for every edge {x,y} ∈ E, f(x) ≠ f(y)  

## Pseudocode
* Number the set of possible colors, C  
  * Assume ther is a large supply of different colors even though they may not all be used  
* Order the vertices in any arbitrary order  
* Consider each vertex v in order:  
  * Assign v a color that is different from the color of v's neighbors that have already been assigned a color.  
    * When selecting a color for v, use the lowest numbered color possible  
