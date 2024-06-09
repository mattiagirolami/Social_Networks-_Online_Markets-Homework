## Problem 1: Modified Barabási–Albert Model
Proved a property of the Barabási–Albert Model.

## Problem 2: Graph Analysis

* Densest Subgraph: Applied the greedy algorithm to identify the densest subgraph in G=(V,E).
* Minimum Cut: Found the minimum cut in the graph.
* Cheeger’s Inequalities: Verified Cheeger’s inequalities by calculating the second smallest eigenvalue λ2 and the conductance ϕ(G).
* Optimal Cut: Identified the cut that satisfies Cheeger’s inequalities.

## Problem 3: Degree Comparison in Social Networks

Proved that in a social network, the expected degree of a random node E[X] is always less than or equal to the expected average degree of its neighbors E[Y].
Also showed that E[X]=E[Y] only if the graph is regular, meaning all nodes have the same degree.

## Problem 4: Streaming Connectivity Algorithm

Designed a streaming algorithm to monitor the connectivity of a graph G(t,w) in a sliding window model, where only the most recent w edges are considered active.
* Algorithm: Proposed an efficient algorithm to update connectivity as new edges arrive.
* Space Complexity
* Update Time

## Problem 5: Opinion-Formation Model with Back-Fire Phenomenon

Proposed an opinion-formation model that accounts for the back-fire phenomenon, where interactions between individuals with sufficiently different opinions lead to increased disagreement.
Also provided assumptions and rationale for the model and argued how it naturally leads to the back-fire effect.

## Problem 6: Applying Graph Neural Networks (GNNs) on PubMed Dataset

Applied GNNs for node classification and link prediction tasks using the PubMed dataset, which consists of publications and citation links:
* Node Classification: Trained and evaluated different GNN architectures (GCN, GraphSAGE, GAT) to classify publications by subject category.
* Link Prediction: Built a GNN model to predict citation links between publications.
* Exploratory Data Analysis (EDA): Analyzed network structure, node features, and class distribution to understand the dataset's characteristics.
* Evaluation Metrics: Used accuracy, precision, recall, F1-score for node classification, and AUC-ROC, F1-score, and ranking metrics for link prediction.
