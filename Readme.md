# Knowledge Graph Project (by FORWARD Datalab)
![logo](./logo.png)

## Description

Here we extract `1.7m` documents from arXiv dataset available in https://www.kaggle.com/Cornell-University/arxiv. Moreover, we use `100,000` keywords to track word frequency and cooccurence within each document.

Our goal is to build a knowledge graph so that we find the right related words using `pmi`. Additionally, we project cooccurence matrix into 2D plot to visualize the similiary between the word clusters.


## Result
- `Query` => related words
- spastic => hypertonia, reflex, muscle
- thrombopoietin => thrombopoiesis, megakaryocyte, platelet
- colonialism => patriarchy, solidarity, meter

## Visualization
![plot](./plot.png)

We observe that similar words for a group of cluster
