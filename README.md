Social Media Sentiment Analysis and Topic Modeling (Reddit)

Overview
This project analyzes large-scale social media data from Reddit to understand public perceptions of ChatGPT.  
It combines sentiment analysis and topic modeling to extract user opinions, emotional trends, and key discussion themes.

The system processes over 50,000 user comments and transforms unstructured text into actionable insights for product and strategy decisions.


Dataset
- Source: Reddit comments related to ChatGPT  
- Size: 50,000+ records  
- Content: user-generated discussions, opinions, and experiences  


Key Features
- Large-scale text preprocessing and normalization  
- Hybrid sentiment labeling using TextBlob + VADER  
- Sentiment classification using TF-IDF + ML models  
- Topic modeling using LDA and clustering (K-means)  
- User insight extraction based on sentiment and topic distribution  


Methods

1. Data Preprocessing
- Lowercasing and text normalization  
- Removing noise (URLs, punctuation, stopwords)  
- Tokenization and lemmatization  

2. Sentiment Analysis
- Combined sentiment labeling (TextBlob + VADER)  
- Classification using:
  - Logistic Regression  
  - SVM  
  - XGBoost  

3. Topic Modeling
- Latent Dirichlet Allocation (LDA)  
- K-means clustering for topic grouping  


Results
- Successfully classified user sentiment into positive, neutral, and negative categories  
- Identified major discussion themes such as:
  - AI capabilities  
  - ethical concerns  
  - productivity use cases  
- Generated structured insights from large-scale unstructured data  


Demo
(Add screenshots here)

Examples:
- Sentiment distribution chart  
- Topic visualization  
- Word frequency analysis  

Tech Stack
- Python  
- Pandas / NumPy  
- Scikit-learn  
- NLTK  
- Matplotlib / Visualization tools  

How to Run

```bash
pip install -r requirements.txt
python main.py
