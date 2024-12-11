# Exercise 1: Florentine Marriage Data Analysis

## Overview

This analysis explores the Florentine Marriage dataset to uncover key relationships and centralities within a network of families. The dataset focuses on marriage alliances between prominent families in Florence, Italy. Various centrality measures are computed to assess the influence and position of each family in the network.

## Quantitative Insights

The following centrality measures were calculated:

### Degree Centrality
Degree centrality indicates the number of direct connections (alliances) a family has.
- **Medici**: 0.3333
- **Ridolfi**: 0.3333
- **Other families**: Ranged from 0.1111 to 0.2222

### Closeness Centrality
Closeness centrality measures how close a family is to all other families in the network.
- **Ridolfi**: 0.4737
- **Medici**: 0.4286
- **Other families**: Ranged from 0.2432 to 0.4500

### Betweenness Centrality
Betweenness centrality captures the extent to which a family acts as a bridge between other families.
- **Ridolfi**: 0.5278
- **Medici**: 0.4167
- **Other families**: Ranged from 0.0000 to 0.3889

### Eigenvector Centrality
Eigenvector centrality measures a family’s influence based on the influence of its neighbors.
- **Ridolfi**: 0.4577
- **Medici**: 0.4461
- **Other families**: Ranged from 0.0659 to 0.4009

### PageRank
PageRank evaluates the importance of each family based on incoming connections.
- **Medici**: 0.1399
- **Ridolfi**: 0.1379
- **Other families**: Ranged from 0.0598 to 0.1107

## Visual Insights

The network of marriage alliances was visualized with nodes representing families and edges representing marriage alliances. 

Key observations:
- **Medici and Ridolfi families**: These families are central to the network, with the highest degree and betweenness centrality.
- **Peripheral families**: Families like Strozzi and Pazzi have minimal influence in the network.

## Conclusion

The Medici family holds a strategic position in the Florentine social network, demonstrating their significant political and social influence. This analysis highlights the importance of centrality measures in understanding the dynamics of social networks.

## Technologies Used

- Python (for data analysis and centrality calculations)
- NetworkX (for graph analysis and centrality measures)
- Matplotlib/Plotly (for visualizing the network graph)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/DBEST-EZRA/Graph_Algorithm_Application.git
