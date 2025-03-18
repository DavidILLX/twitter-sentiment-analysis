# Twitter Sentiment Analysis using BERT &amp; K-Means Clustering
This project explores sentiment analysis using BERT and VADER, followed by K-Means clustering on the sentiment embeddings. The goal is to compare different sentiment analysis techniques and discover hidden structures in sentiment data.

## Features
* Data Preprocessing: Cleaning and tokenization of text data. Lemmatization using WordNetLemmatizer.
* Custom Stop Words: Using TF-IDF to define and compare stop words with standard stop words.

Sentiment Analysis:
1. VADER: Rule-based sentiment analysis.
2. BERT: Transformer-based sentiment classification.

## Clustering with K-Means:
Applying clustering to sentiment embeddings.  
Visualizing clusters using PCA/UMAP.  

## Evaluation 
Comparing sentiment distributions.  
Statistical tests (e.g., paired t-tests) to measure significance.

## Results
* Comparison of sentiment scores with different stop words.
* Distribution plots of sentiment scores.
* Cluster visualizations of sentiment embeddings.

### Future Work
* Experiment with DBSCAN
* Test with different pre-trained BERT models.
* Improve stop word selection with topic modeling.
