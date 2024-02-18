**TASK 1**

_Introduction_

This repository contains Python code for analyzing biases and attitudes present in datasets related to identity terms, occupations, regions, and gender. The analysis is conducted using Word2Vec models and cosine similarity metrics.

_Prerequisites_

Ensure you have the following dependencies installed:

Python 3.x

Pandas

Gensim

NumPy

Matplotlib

Seaborn

Scikit-learn

_Code Structure_

The code consists of several sections, each focusing on a specific analysis task. Here's a brief overview:

1. Loading and Tokenization

The datasets are loaded from TSV files and tokenized for further processing.

2. Word2Vec Model Training

Word2Vec models are trained on the tokenized datasets to obtain word embeddings.

3. Bias Analysis

Bias between identity terms (e.g., religion, occupation) and stereotypical/non-stereotypical attributes is calculated using cosine similarity metrics.
Biases between regions and stereotypes are also analyzed.

4. Visualization

The average stereotypical attitudes by religion/region and non-stereotypical attitudes by occupation are visualized using bar plots.

5. Name Analysis

Analysis of gender biases in names is performed, specifically focusing on names ending with 'a' or 'i' and their association with female gender.
