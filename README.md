Consumer Complaints NLP Analysis

This project analyses 903 consumer complaints from the CFPB database regarding Shellpoint Partners, LLC over a six-month period. Using Python, the project cleans and preprocesses unstructured complaint narratives, converts them into numeric vectors using Bag-of-Words and TF-IDF, and identifies recurring topics with Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF).

The workflow includes:

Text cleaning, tokenization, stopword removal, and lemmatization using NLTK.

Vectorization with scikit-learn (CountVectorizer and TfidfVectorizer).

Topic modeling with LDA and NMF to extract dominant topics per complaint.

Mapping dominant topics to readable labels and saving results to Excel files.

The repository contains:

Complaints.ipynb – Jupyter notebook with full code and workflow.

complaints.xlsx.csv – Original dataset.

Cleaned and output Excel files with topic assignments.

This analysis provides insights into the most pressing issues in consumer complaints and can influence decision-making for customer service improvements.
