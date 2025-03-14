# TV Show Facebook Network Analysis

## Overview
This repository contains the code and analysis for studying a social network of TV show Facebook pages. The network is based on mutually liked Facebook pages, where nodes represent TV show pages, and edges indicate mutual likes. The dataset was collected in November 2017 and represents blue-verified Facebook page networks.

## Features
- **Network Construction & Visualization**: Graph representation of TV show pages and their mutual connections.
- **Network Metrics**:
  - Degree Distribution
  - Centrality Measures (Degree, Betweenness, Closeness, Eigenvector, PageRank)
  - Clustering Coefficient & Density
  - Path Analysis (Shortest Path, Network Diameter)
- **Community Detection**: Louvain method for identifying clusters.
- **Random Graph Comparison**:
  - Erdős–Rényi (ER)
  - Barabási-Albert (BA)
  - Watts-Strogatz (WS)
- **Strategic Implications**: Insights into influencer marketing, content recommendation, competition analysis, and risk management.


## Files
- `ddsm.ipynb` - Main script for network analysis.
- `data/tv_show_network.csv` - Input dataset containing mutual likes.
- `README.md` - Documentation of the project.
- `report.pdf` - Generated report based on analysis.

## Results
- The network is highly connected with a small-world structure.
- Certain TV shows act as influential hubs.
- Community detection reveals genre-based clusters.
- BA model best approximates the real network’s degree distribution.

## Contributors
- Munish KHan

For any questions or suggestions, feel free to open an issue!

