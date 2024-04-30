# Named Entity Recognition (NER) and Karate Club Network Analysis

This repository contains Python code for Named Entity Recognition (NER) and analysis of Zachary's karate club network.

## 1. Named Entity Recognition (NER)

### (i) Description
A natural language processing (NLP) technique called Named Entity Recognition (NER) attempts to recognize and categorize named entities in a text into specified categories, like names of people, places, organizations, times, amounts, monetary values, percentages, and so on. NER's main objective is to identify entities and their types in order to extract structured information from unstructured text. For many NLP applications, including document summarization, information retrieval, and responding systems, this task is essential. Tokenizing the input text into words or phrases and then categorizing each token into preset entity categories are the usual steps involved in NER. For NER, a variety of deep learning and machine learning techniques are used, such as neural network-based models like Bidirectional LSTMs, statistical models like Conditional Random Fields (CRF), and rule-based techniques.

### (ii) Usage
1. Install required dependencies:
   ```bash
   pip install spacy
   python -m spacy download en_core_web_sm
2. Run the NER code:
   ```bash
   python ner.py
3. Input a text file containing 200-300 words.
4. The recognized named entities along with their categories will be written to an output file.
## 2. Karate Club Network Analysis
### Description Analysis of Zachary's karate club network using NetworkX library.

### Usage
1. Install required dependencies:
   ```bash
   pip install networkx
2. Run the network analysis code:
   ```bash
   python karate_club_analysis.py
3. This Python script analyzes Zachary's karate club network from the "karate.gml" file using NetworkX, a graph analysis library. It performs the following tasks:

   i. Creates a graph from the "karate.gml" file and displays basic information about the network.

   ii. Stores metadata of actors in the network.

   iii. Calculates various centrality measures (degree, betweenness, closeness, eigenvector, and pagerank centrality) and provides an analysis based on the centrality values.

   iv. Finds possible k-components of the network and computes the clustering coefficient.

   v. Identifies communities using the Girvan-Newman algorithm and Louvain method.

### Data Source
The karate club network dataset (karate.gml) can be obtained from [here](https://doi.org/10.6084/m9.figshare.7985174.v1).
### Note
Analyzing nodes based on centrality values can provide insights into the importance and influence of individual actors within the network. Higher centrality values indicate greater significance in terms of network connectivity or influence. Similarly, identifying communities within the network can reveal cohesive subgroups or cliques among the members. These analyses can help in understanding the structure and dynamics of social networks like Zachary's karate club.
