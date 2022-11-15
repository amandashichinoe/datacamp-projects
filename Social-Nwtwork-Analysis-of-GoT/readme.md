# Social Network Analysis of Game of Thrones

The main goal of this project was to apply some Social Network Analysis(SNA) concepts to find out the most important character in the books series 'A Song of Ice and Fire' which gave rise to the Game of Thrones sitcom.

### Python Libraries 🛠️

I used this versions for networkx and scipy:
- networkx -> 2.8.8
- scipy -> 1.9.3

Scipy library older than version 1.8.0 doesn't have some attributes used in this project. Is recommended check your version and upgrade if necessary.

To verify your library version, run the following command in your terminal:
````
python -c "import scipy; print(scipy.__version__)"
````

To upgrade your package run:
````
pip install --upgrade scipy
````

After upgrade your package it is necessary restart your notebook.

If still throwing an error, try to upgrade your networkx library too:
````
pip install --upgrade networkx
````

### Some Social Network concepts 📚 

Social Network Analysis(SNA) is the study of the relationship between nodes which are connected to each other by links(also named edges).

I would take so much time to explain all concepts envolved in a Social Network Analysis, so bellow I explain briefly the concepts used in this project and invite you to explore more about this topic.

- Degree Centrality: For a undirected network is the number of links that a given node has. For a directed network is the sum of the in-degree(number of links that a node receive) and the out-degree(number of the links that leave the same node). In both cases can be weighted(the links has a weight) or unweighted.

- Betweenness Centrality: Measures how often the node appears on the shortest paths between nodes. The nodes that appears most often are the leaders of informations. Depending on the tools which you are using to make your analysis, these nodes can be the ones with the highest or lowest scores.
For networkx is the highest score.

- PageRank: Is an algorithm used by Google Search to rank websites in their search engine results. It works by counting the number and quality of links to  page to determine a rough estimate of how important the website is. The underlying assumption is that more important websites are likely to receive more links from other websites.

### To know more 🔗
- [Networkx Refference](https://networkx.org/documentation/stable/reference/index.html)
- [Page Rank Algorithm](https://www.geeksforgeeks.org/page-rank-algorithm-implementation/)