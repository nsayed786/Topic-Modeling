# Topic-Modeling
Topic model is a type of statistical model for discovering the abstract "topics" that occur in a collection of documents.

# Problem statement
It's very difficult for individual to go through each company and know about the company. I am trying to find the topics from various company reviews from Glassdoor site, which will help people to know better about the company.

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
urllib
bs4
```

## Installation
I worked on Jupyter, below are the ways to install the libraries in conda environment

```python
conda install -c anaconda gensim
conda install -c anaconda nltk
conda install -c spacy spacy
conda install -c conda-forge/label/cf201901 pyldavis
```
## User Input
Users input will be the keywords for ex: good company,life balance etc

## Output
Based on the user keywords, The model will diplay the company name and the reviews about the company based on the keywords

# Model compared with traditional method.
In traditional method you have to define rules for each company review, which is messy. Here the model itself will try to find the topics from the review and diplay only those which are relevant.

# Steps
```
1. Import Libraries
2. Load the data
3. Cleaning the data
4. Tokenization
5. Build Bigram and Trigram
6. Create a dictionary
7. Create documnent-term Matrix
8. Perform LDA
9. Compute the model ( Perplexity and Coherence Score)
10. Visualization
11. Find the dominant topics.
12. Based on the topic, diplay the result to audience
```

## References
https://www.analyticsvidhya.com/blog/2016/08/beginners-guide-to-topic-modeling-in-python/<br/>
https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/<br/>
https://www.analyticsvidhya.com/blog/2018/10/mining-online-reviews-topic-modeling-lda/<br/>
https://www.analyticsvidhya.com/blog/2018/10/stepwise-guide-topic-modeling-latent-semantic-analysis/
