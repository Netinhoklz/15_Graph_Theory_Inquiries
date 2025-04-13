# Graph Data Analysis Project

This repository contains the implementation of a comprehensive graph data analysis, addressing fifteen critical questions in graph theory as outlined in the project guidelines :contentReference[oaicite:0]{index=0}. The work applies theoretical concepts and practical programming techniques to explore various structural properties and algorithmic challenges within graph datasets.

## Project Objectives

The project is organized around the following fifteen questions:

1. **Dataset Selection**:  
   Identify and select five distinct graph datasets from sources such as [University of Michigan Network Data](https://public.websites.umich.edu/~mejn/netdata/) and [Stanford SNAP datasets](http://snap.stanford.edu/data/index.html).

2. **Degree Distribution Analysis**:  
   Calculate the Probability Distribution Function (PDF) and the Complementary Cumulative Distribution Function (CCDF) for graph degree distributions.

3. **Path Enumeration**:  
   Given two chosen vertices, identify all possible paths connecting them.

4. **Shortest Path Identification**:  
   Determine the shortest path between two chosen vertices.

5. **Average Distance Calculation**:  
   Compute the average distance between all pairs of vertices within the graph.

6. **Eccentricity Evaluation**:  
   For a selected vertex, determine its eccentricity, which is the maximum distance from that vertex to any other vertex in the graph.

7. **Network Diameter**:  
   Calculate the diameter of the network, defined as the longest of all the shortest paths between any pair of vertices.

8. **Graph Density**:  
   Evaluate the density of each graph, measuring the ratio of actual edges to the total number of possible edges.

9. **Cycle Detection**:  
   Determine if the graph contains Eulerian or Hamiltonian cycles.

10. **Clique Enumeration**:  
    Identify and list all cliques within the graph.

11. **Maximum Clique Identification**:  
    Find the maximum clique, i.e., the largest subset of vertices that form a complete subgraph.

12. **Connectivity Analysis**:  
    Check whether the graph is fully connected and, if not, report the number of connected components.

13. **Largest Component Extraction**:  
    Return the set of nodes that constitute the largest connected component of the graph.

14. **Graph Isomorphism Check**:  
    Compare two graphs to verify if they are isomorphic.

15. **Bridge Identification**:  
    Determine whether bridges exist in the graph, where a bridge is an edge whose removal increases the number of connected components.

## Repository Structure

- **Datasets**: Scripts and resources for downloading and preprocessing graph datasets.
- **Analysis Modules**: Separate scripts and notebooks for each of the fifteen questions, implementing algorithms and computations for degree distributions, path finding, connectivity, and more.
- **Visualizations**: Tools and functions for graph visualization using libraries like Matplotlib, aiding in the interpretation and presentation of analysis results.
- **Documentation**: Detailed write-ups accompanying each section, explaining the methodology, theory, and results behind the analyses.

## Methodology

For every question addressed, the following steps are followed:

- **Data Preparation**: Load and clean the selected graph datasets.
- **Algorithm Implementation**: Employ efficient graph algorithms (using libraries such as NetworkX and iGraph) to perform the required computations and analyses.
- **Result Validation**: Cross-validate the outputs with theoretical expectations and, where applicable, compare across multiple datasets.
- **Visualization**: Generate visual representations of graphs and their properties to provide intuitive insights into the analysis.

## Conclusion

This project offers a methodical exploration of essential topics in graph theory. By solving fifteen diverse questions, the work not only highlights fundamental aspects such as connectivity, path analysis, and clique detection but also opens avenues for further research and applications in complex network analysis.

Feel free to explore the code and documentation within this repository for a deeper insight into each of the analyses performed.
