# karate club community detection using modularity
## Overview
- applied spectral modularity on the imported karate club date from networkx
    - iterate till negative leading eigen values
- compute:
    - degree centrality,
    - betweenness centrality,
    - closeness centrality,
    - clustering coefficient
- visualise the graphs and colour nodes after every split
- plot the variation in the centralities and coefficient for each node after each iteration
  - plot line and bar graphs using matplotlib
## Discussion:
- overall 3 communities are formed
- degree centraility with high value indicating an immediate hub ( a lot of direct connections)
  1. it increases for most of the nodes this means that as the communities are divided they are more connected to one another and form hubs
- betweenes centrality indicates the nodes that are bridges between multiple communities
  1. it shows very varied changes with some increasing very high and some dropping very low, this indicates that some nodes can break apart with smaller communities
- closeness centrality indicated how quickly a node can reach another
  1. it shows a more gradual trend , this shows that with smaller communities connections also become many and nodes become more well connected as one bridge can connect with entire communities
- clustering coefficient depicts how connected the neighbors are
  1. relatively less turbulent with a few going up and down.

## Requirements
- numpy
- networkx
- matplotlib
