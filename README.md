**TASK 1**

**_Introduction_**

This repository contains Python code for analyzing biases and attitudes present in datasets related to identity terms, occupations, regions, and gender. The analysis is conducted using Word2Vec models and cosine similarity metrics.

**_Prerequisites_**

Ensure you have the following dependencies installed:

Python 3.x

Pandas

Gensim

NumPy

Matplotlib

Seaborn

Scikit-learn

**_Code Structure_**

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

**Task 2**

**_Introduction_**

This repository contains Python code for analyzing legal prompts stored in JSON files. The code utilizes various libraries such as Pandas, Matplotlib, Seaborn, NLTK, and Jsonlines for data processing, visualization, and sentiment analysis.

**_Prerequisites_**

Ensure you have the following dependencies installed:

Python 3.x

Pandas

Matplotlib

Seaborn

NLTK


**Code Structure**

The code is divided into several sections, each performing a specific analysis task:

1. Loading and Preprocessing

JSON files containing legal prompts are loaded into a Pandas DataFrame.
Text preprocessing tasks such as regular expression matching and data cleaning are performed.

2. Keyword Analysis

Keywords related to theft and forgery are extracted and their frequencies are analyzed.

3. Identity Term and Gender Analysis

Identity terms and genders mentioned in the prompts are extracted and their frequencies are analyzed.
Actions mentioned in the prompts are also analyzed.

4. Visualization

Frequency distributions of actions, identity terms, and genders are visualized using bar plots.

5. Prompt Distribution Analysis

The distribution of prompts across different files is analyzed.

6. Sentiment Analysis

Sentiment analysis is performed on the legal prompts using NLTK's SentimentIntensityAnalyzer.
The distribution of sentiment scores is visualized using a histogram.


**NOTE: task_1 and task2 have data for both the tasks**
