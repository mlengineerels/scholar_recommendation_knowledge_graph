# Scholar Recommendation Pipeline

A machine learning pipeline that enhances link prediction accuracy by leveraging Graph Neural Networks (GNN), Recurrent Neural Networks (RNN), and Knowledge Graph Reasoning. This project aims to improve data-driven decision-making in academic and research networks by accurately predicting connections between scholars.

## Project Overview

In the realm of academia, identifying potential collaborations between scholars based on their research interests and past publications can be challenging. This project addresses that by implementing a recommendation pipeline that achieved a **10% improvement** in link prediction accuracy compared to traditional baseline models.

## Features

- **Improved Link Prediction**: Utilizes GNN and RNN models to uncover hidden relationships and predict potential connections between scholars.
- **Knowledge Graph Reasoning**: Enhances recommendations by reasoning over structured academic data.
- **Data-Driven Insights**: Increases the accuracy of recommendations, enabling better decision-making for academic partnerships.

## Technologies Used

- **Graph Neural Networks (GNNs)**: Captures structural and relational information within the knowledge graph.
- **Recurrent Neural Networks (RNNs)**: Processes sequential data to improve the accuracy of relationship predictions.
- **Knowledge Graphs**: Represents complex relationships between scholars and their research work.
- **PyTorch**: Framework for building, training, and optimizing machine learning models.

## Data Sources

The dataset includes scholarly publications, author metadata, research topics, and citations. It was processed to create a knowledge graph where nodes represent scholars and edges represent relationships, such as co-authorship and shared research interests.

## Methodology

1. **Data Preprocessing**: Raw data is cleaned and converted into a structured format for knowledge graph construction.
2. **Model Training**:
   - GNN is used to learn embeddings for each scholar node, capturing relationships within the graph.
   - RNN is used to capture temporal patterns, improving the understanding of sequential relationships.
3. **Knowledge Graph Reasoning**: Iteratively updated to include newly inferred relationships.
4. **Link Prediction**: The model predicts connections between scholars, with results evaluated against a baseline for accuracy improvement.

## Results

This project improved link prediction accuracy by **10%** over baseline models, enhancing the ability to identify potential research collaborations within scholarly networks.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mlengineerels/scholar_recommendation_knowledge_graph.git
   cd scholar-recommendation-pipeline
