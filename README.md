# Word Embeddings (Natural Language Processing)

This project explores how words can be represented as numerical vectors to uncover meaning and similarity within text. Using **Word2Vec** architectures (**CBOW** and **Skip-Gram**), the analysis demonstrates how context defines meaning and how these representations support real-world text analytics.

📊 [Word2Vec Presentation](https://pitch.com/v/word-embeddings---word2vec-ndreji)



## Project Overview

Text data is vast, unstructured, and complex. To interpret it effectively, analysts rely on numerical representations that capture relationships between words.  
This project builds and compares **Continuous Bag of Words (CBOW)** and **Skip-Gram** models to show how each learns contextual relationships in a movie-review corpus and how these insights can inform practical applications such as sentiment analysis and content categorisation.

**Goal:** Transform text into structured numerical data that reflects linguistic and semantic relationships.  
**Dataset:** IMDB Movie Review Dataset (50 000 reviews, evenly split into train / test).
**Embedding dimensions:** 50 – 300 dimensions.



## Dataset Summary

- **Source:** IMDB Movie Review Dataset (Andrew Maas et al., 2011) 
- **Type:** Unstructured text corpus for unsupervised learning  
- **Focus:** Understanding how vector representations reflect sentiment and similarity among words.  



## Approach

**1. Data Preparation**  
- Normalised and tokenised text, removing punctuation and low-frequency words  
- Built context–target training pairs for model learning  

**2. Model Development**  
- Implemented **CBOW** (predict target from context) and **Skip-Gram** (predict context from target)  
- Trained on the review corpus using different window sizes and embedding dimensions  
- Applied negative sampling to improve efficiency  

**3. Evaluation & Visualisation**  
- Measured cosine similarity to evaluate learned relationships  
- Reduced dimensions with **PCA** and **t-SNE** to visualise clusters  
- Explored vector arithmetic examples (e.g., *king – man + woman ≈ queen*) to interpret relationships  



## Key Insights

| Model | Strengths | Ideal Scenario |
|:------|:-----------|:---------------|
| **CBOW** | Fast and stable, captures general context effectively | Larger balanced datasets |
| **Skip-Gram** | Learns nuanced relationships and rare terms | Smaller or imbalanced corpora |

- Both models produced clear thematic clusters separating positive, negative, and neutral terms.  
- Skip-Gram provided richer insight into less-frequent words, supporting more detailed sentiment segmentation.  
- The results illustrate how numerical embeddings translate qualitative text into patterns analysts can measure and act on.  



## Tools and Techniques  

- **Languages & Libraries:** Python, TensorFlow, NumPy, Pandas, Matplotlib, Scikit-learn  
- **Analytical Skills:** Text preprocessing, analytical thinking, similarity analysis, result interpretation, data visualisation, data storytelling, dimensionality reduction.



## Outcome  

The project bridges language and analytics by turning text into measurable vectors that reveal meaning at scale.  
It strengthens the ability to interpret unstructured data, derive sentiment trends, and explain how context influences language, which are essential capabilities for business and data analytics roles.  



## Author  

👩🏽‍💻 **Bate Bita Tambe**  
Business and Data Analyst  
[LinkedIn](https://www.linkedin.com/in/bate-bita-tambe-a29ab6221)

