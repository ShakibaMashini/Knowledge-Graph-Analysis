# Knowledge-Graph-Analysis
The main goal of this project was to develop an effective and efficient solution for updating a knowledge graph. To achieve this, we simulated the process by splitting our dataset into two parts: system (representing the existing knowledge graph) and change (representing new data). This setup allowed us to evaluate our model by comparing its predictions with the ground truth.
As shown in the accompanying plot, the dataset was divided into these two parts, with the goal of predicting links in the change portion. To do this, we extracted all possible relationships for entities common between the system and change parts of the knowledge graph. Next, we labeled these relationships and used the labeled data for training and testing the model

![Knowledge Graph Visualization](KG-KGu.png)


Below is a graph representing the relationships in the knowledge graph analysis:

![Knowledge Graph Visualization](graph-3.png)
