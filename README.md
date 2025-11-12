# Word Embeddings (Natural Language Processing)

This project explores how Word2Vec models capture meaning and similarity between words by learning from context. Using **CBOW** and **Skip-Gram** architectures, the analysis visualises semantic relationships in vector space and demonstrates how these embeddings power modern Natural Language Processing.

📊 [Word2Vec Presentation](https://pitch.com/v/word-embeddings---word2vec-ndreji)



## Project Overview

Text data is unstructured by nature — full of nuance and ambiguity. This project investigates how neural network–based embeddings transform words into numerical vectors that retain their semantic relationships.  
By comparing **Continuous Bag of Words (CBOW)** and **Skip-Gram**, the analysis highlights how context defines meaning and how embeddings underpin NLP applications like sentiment analysis, topic modelling, and search relevance.

**Goal:** Build and interpret Word2Vec embeddings that represent semantic similarity.  
**Dataset:** Movie review corpus (cleaned and tokenised text)  
**Embedding dimensions:** 50–300  



## Dataset Summary

- Source: Publicly available movie reviews dataset used for educational NLP tasks  
- Type: Text corpus for unsupervised learning  
- Features include: tokenised sentences, context windows, and target words  



## Approach

**1. Text Preprocessing**  
- Normalised text: lowercased, removed punctuation, tokenised  
- Filtered out stopwords and low-frequency tokens  

**2. Model Development**  
- Implemented **CBOW** (predict target from context) and **Skip-Gram** (predict context from target) using Word2Vec  
- Tuned vector size, window length, and negative sampling  

**3. Evaluation & Visualisation**  
- Measured word similarity with cosine distance  
- Applied **PCA** and **t-SNE** for dimensionality reduction  
- Visualised word clusters to show context relationships  



## Key Findings

| Model | Strengths | Best Use Case |
|:------|:-----------|:--------------|
| **CBOW** | Faster to train, captures frequent word contexts well | Large datasets with balanced vocabulary |
| **Skip-Gram** | Captures rare-word relationships, deeper contextual understanding | Smaller or imbalanced corpora |

- Both models learn intuitive clusters — words with similar meanings are positioned close in vector space.  
- Skip-Gram demonstrated stronger performance for rare terms, while CBOW excelled with common words.  
- Dimensionality reduction revealed interpretable patterns such as sentiment polarity and thematic grouping.  



## Tools and Techniques

- **Languages & Libraries:** Python, Gensim, NumPy, Pandas, Matplotlib, Scikit-learn  
- **Skills Demonstrated:** Text preprocessing, analytical thinking, neural embeddings, vector similarity, dimensionality reduction, data visualisation  



## Outcome

This project demonstrates how machine learning can extract meaning from unstructured language and convert it into quantifiable insights.  
It strengthens interpretive and analytical skills in NLP, bridging the gap between technical model results and their real-world implications.



## Author

👩🏽‍💻 **Bate Bita Tambe**  
Business and Data Analyst  
[LinkedIn](https://www.linkedin.com/in/bate-bita-tambe-a29ab6221)
