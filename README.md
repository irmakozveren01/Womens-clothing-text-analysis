# Women's Clothing E-Commerce Reviews Analysis

This project presents a comprehensive text mining and natural language processing (NLP) analysis of customer reviews from the Women's Clothing E-Commerce Reviews dataset using **R**.

The objective is to extract meaningful insights from customer feedback through text preprocessing, sentiment analysis, topic modeling, and clustering techniques.

---

## Project Objectives

- Clean and preprocess customer review text
- Explore word frequencies and common terms
- Perform sentiment analysis
- Discover latent topics using LSA and LDA
- Estimate document clusters using Mixture of Unigrams (MOU)
- Compare different topic modeling approaches using evaluation metrics

---

## Dataset

**Dataset:** Women's Clothing E-Commerce Reviews

The dataset contains customer reviews of women's clothing products together with metadata such as recommendation status and department information.

After preprocessing:

- **22,641 reviews**
- **5,818 unique terms** in the final vocabulary

---

## Methods

### Text Preprocessing

- Lowercasing
- Punctuation removal
- Number removal
- Stopword removal
- Domain-specific stopword removal
- Stemming
- Corpus construction
- Document-Term Matrix (DTM)

---

### Exploratory Text Analysis

- Word Frequency Analysis
- Word Cloud Visualization

---

### Sentiment Analysis

- Sentiment score calculation
- Distribution of sentiment scores
- Most influential sentiment words
- Comparison of sentiment and recommendation status

---

### Topic Modeling

#### Latent Semantic Analysis (LSA)

- Singular Value Decomposition (SVD)
- Explained variance
- Low-rank approximation
- Topic extraction

#### Mixture of Unigrams (MOU)

- Cluster estimation
- Heatmap visualization
- Word frequency comparison

#### Latent Dirichlet Allocation (LDA)

- Topic distributions
- Top representative words
- Topic interpretation

---

## Model Evaluation

The project compares different topic modeling approaches using:

- Adjusted Rand Index (ARI)
- Accuracy
- Topic interpretation
- Model comparison

---

## Output

The repository includes:

- Complete R source code
- R Markdown report
- HTML report
- PDF report

---

## Authors

- Irmak Özveren
- Halit Kaan Kesgin
- Fatemeh Shirazi
