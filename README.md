# Information Retrieval with TF-IDF and Boolean Search

A Python-based Information Retrieval project that processes text documents and implements core techniques used in document search and retrieval.

## Overview

The project implements a basic information retrieval pipeline for indexing and searching a collection of text documents. It combines text preprocessing, TF-IDF weighting, inverted indexing, Boolean query processing, and cosine similarity.

## Features

- Text preprocessing and tokenization
- Stopword removal
- TF (Term Frequency) calculation
- IDF (Inverse Document Frequency) calculation
- TF-IDF weighting
- Inverted index construction
- Boolean query processing using `AND`, `OR`, and `NOT`
- Document retrieval based on Boolean queries
- Cosine similarity calculation between document vectors

## Information Retrieval Pipeline

1. Load and preprocess the text documents.
2. Remove punctuation, special characters, and stopwords.
3. Tokenize the documents into individual terms.
4. Build an inverted index mapping terms to documents.
5. Calculate TF and IDF values.
6. Generate TF-IDF representations for the documents.
7. Process user queries using Boolean operators.
8. Retrieve matching documents.
9. Calculate cosine similarity between vectors when required.

## Technologies

- Python
- NLTK
- NumPy
- Pandas
- SciPy

## Example Query

The system supports Boolean queries such as:

```text
information AND retrieval
