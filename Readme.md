# Knowledge Graph Project (by FORWARD Data Lab)
![logo](./logo.png)

## Description

Here we extract `1.7m` documents from the arXiv dataset available in https://www.kaggle.com/Cornell-University/arxiv. Moreover, we use `100,000` keywords to track word frequency and co-occurrence within each document.

Our goal is to build a knowledge graph to find related words using the metric `PMI.` Additionally, we project the co-occurrence matrix into a 2D plot to visualize the similarity and dissimilarity among words and clusters.


## Result
- `Query` => related words
- spastic => hypertonia, reflex, muscle
- thrombopoietin => thrombopoiesis, megakaryocyte, platelet
- colonialism => patriarchy, solidarity, meter
- mamluk => terracotta, mesopotamia, lustre
- gene => neofunctionalization, mesophile, pseudogene


## Visualization
![plot](./plot.png)

We observe that similar words form a word cluster.
