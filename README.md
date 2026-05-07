## Wikispeedia Network Analysis
(July 2025)

This is a university project for the **Network Science and Data Visualisation** course at the **University of Turin**.  

## Wikispeedia Dataset
The wiki game is a simple online game where players start from one Wikipedia page and must reach another page by clicking on links present in the pages. One of the most famous websites for playing this game is [Wikispeedia](https://dlab.epfl.ch/wikispeedia/play/), from which the [Wikispeedia navigation paths](https://snap.stanford.edu/data/wikispeedia.html) dataset from Stanford University was extracted.

The dataset contains a reduced version of Wikipedia from 2007 and the completed and uncompleted paths taken by Wikispeedia users.

- Finished paths: 51,318
- Unfinished paths: 24,875
- Articles: 4,604
- Links: 119,882

## Objective
The objective of this project is to analyze the network structure of Wikipedia in the context of Wikispeedia. The analysis will be exploratory in nature, seeking to obtain insights into the network structure and how users navigate within it.
Some key research questions are:

- **1_graph_properties.ipynb**: What type of structure does the Wikipedia network have?
- **2_nodes_centralities.ipynb**: Which articles are most central in the network?
- **3_community_detection.ipynb**: Are Wikipedia categories reflected in a community structure?
- **4_paths_difficulty.ipynb**: The difficulty of a challenge is correlated with structural or semantic difficulty?
- **5_hubs_in_paths.ipynb**: The nodes most frequently visited by players are also the most central?

Each Jupyter notebook attempt to answer these questions describing the methods and results.

## Overall Results 
This analysis confirms that the structural properties of the Wikipedia network influence human navigation behavior. We can conclude that **semantic relationships between articles play a minor role**. Instead, **structural features of the network are the main drivers** of user navigation patterns, either due to the natural attraction of bridge nodes or through intentional strategies used by experienced players.

Therefore, an effective strategy in the Wiki game may not involve constructing a semantically coherent path between source and target. Rather, it may rely on exploiting the most central nodes.
