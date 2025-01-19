# Dense-Embedding-Model
Trained a dense embedding model to learn meaningful  embeddings from the dataset (that has been extracted using web-crawling from State Bank Of Pakistan (SBP) and pre-processed )


## **Objective: Develop embeddings that capture semantic relationships within the data..**

The goal is to train a dense embedding model to learn meaningful embeddings from the dataset that is extracted (from State Bank Of Pakistan) and pre-processed.

## Tools and Libraries used
- NLTK
- WORD2VEC
- GENSIM
- MATPLOTLIB
- PANDAS
- NUMPY
- SKLEARN

  ## Steps
  
  1. Data Preparation
     - Data Set:10 Crawled Pages (20-25 lines each)
     - Vocabulary Size: 1030 words
     - Embedding Dimension: 30
  2. Pre-Processing
        - Lower-Casing
        - Removing Punctuation
        - Creating Lemmas
        - Creating word tokens
          
3. Defining Model Hyperparameters
        - Vector Size: 30 dimensions
        - Context Window Size: 5 words
        - Minimum Count: 1 (to include all words)
        - Negative Sampling: 5 samples
   
4. Training Word2vec model
      - Epochs : 10
      - Training Algorithm: Skip-gram (sg=1)
        
5. Model Evaluation (Cosine Similarity)

      - Using Cosine Similarity
      - Clustering  Similar Words


## Project Outcomes
- Accurate Semantic Relationships
  High similarity between related words like “implement” and “objective.”

- Contextual Understanding
  Embeddings effectively captured business and abstract term relationships.

- Optimized for Small Data
  Word2Vec delivered quality embeddings despite the small dataset.





---


![1](https://github.com/user-attachments/assets/4365fad9-ad05-42b7-8244-c4ee6dab92f9)








![2](https://github.com/user-attachments/assets/c96d60aa-c2cc-41e8-b767-9af8345145a0)





