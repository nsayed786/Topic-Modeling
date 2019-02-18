# Topic-Modeling
Topic model is a type of statistical model for discovering the abstract "topics" that occur in a collection of documents.

# Introduction
This project is based on topic modeling on Company review from Glassdoor site. I'll share the details on how to scrap the data and perform topic modeling using LDA. And also compute Perplexity and Coherence Score, which decide the model preformance.

## Getting Started
These instructions will get you through the project and it's requirements

## Prerequisite
Libraries
```python
Gensim
Spacy
nltk
pyLDAvis
numpy
pandas
matplotlib
```

## Installation
I worked on Jupyter, below are the ways to install the libraries in conda environment

```python
conda install -c anaconda gensim
conda install -c anaconda nltk
conda install -c spacy spacy
conda install -c conda-forge/label/cf201901 pyldavis
```

# Steps
```
1. Import Libraries
2. Load the data
3. Cleaning the data
4. Tokenization
5.Build Bigram and Trigram
6. Create a dictionary
7. Create documnent-term Matrix
8. Perform LDA
9.Compute the model ( Perplexity and Coherence Score)
10. Visualization
```
