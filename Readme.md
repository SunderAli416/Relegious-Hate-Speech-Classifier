# Hate Speech Detection Project

This project aims to detect hate speech against Islam using various machine learning and deep learning models. The project explores different techniques, including preprocessing, tokenization, word embedding, character encoding, topic modeling, and attention mechanisms for deep learning models. The goal is to improve the performance of hate speech detection systems and provide more effective tools for identifying and addressing hate speech.

## Techniques Used

The project incorporates the following techniques:

1. **Tf-Idf + Multinomial Naïve Bayes:** The project includes a baseline model using Tf-Idf vectors and the Multinomial Naïve Bayes algorithm.

2. **Glove Vector Embedding + Word Tokenization (Padded Text Sequences) + CNN:** A deep learning model using GloVe word embeddings, word tokenization with padding, and a Convolutional Neural Network (CNN) architecture.

3. **Character Tokenization (Padded Text Sequences) + CNN:** Another deep learning model that utilizes character-level tokenization with padding and a CNN architecture for text classification.

4. **Glove Vector Embedding + Word Tokenization (Padded Text Sequences) + DBpedia Ontology Attention + CNN:** A model incorporating DBpedia ontology-based attention along with GloVe word embeddings and a CNN architecture.

5. **Glove Vector Embedding + Word Tokenization (Padded Text Sequences) + Custom Ontology Attention + CNN:** A model utilizing a custom ontology-based attention mechanism along with GloVe word embeddings and a CNN architecture.

6. **Glove Vector Embedding + Word Tokenization (Padded Text Sequences) + BERTopic Attention + CNN:** A model that incorporates BERTopic-based attention, GloVe word embeddings, and a CNN architecture.

## Directory Structure

The project directory has the following structure:


- The `Notebooks/` directory contains separate Jupyter notebooks for each approach, where you can find the implementation and evaluation of each model.

- The `Data/` directory stores the training and testing data used in the project, represented as CSV files (`train.csv` and `test.csv`).

- The `Ontologies/` directory contains the ontologies used in the project, including the DBpedia ontology (`DBpediaOntology.owl`) and a custom ontology (`CustomOntology.owl`).

- The `Models/` directory is dedicated to storing the trained models. Each model is saved with a `.h5` extension.

Feel free to explore the notebooks and directories for detailed implementation and further
