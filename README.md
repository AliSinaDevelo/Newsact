# Newsact
Newsact is a tiny tool that identifies fake from real, genuine from phoney in the media made with Scikit

## Overview

In the age of social media, distinguishing between real and fake news has become increasingly important. This project demonstrates how to build a machine learning model to detect fake news using Python. By leveraging the power of Python and machine learning libraries, you can build a model to classify news as either REAL or FAKE.

## Project Goals

- **Detect Fake News**: Build a machine learning model that can accurately classify news articles as real or fake.
- **Understand Key Concepts**: Learn about essential terms such as TF-IDF Vectorization and Passive-Aggressive Classification.

## Key Concepts

- **Fake News**: Fake news refers to misleading or false information spread through media, often to achieve specific political or social goals. Understanding fake news is crucial for ensuring the reliability of information.
  
- **TfidfVectorizer**: 
  - **TF (Term Frequency)**: Measures how frequently a term appears in a document. Higher frequency indicates greater relevance.
  - **IDF (Inverse Document Frequency)**: Measures the importance of a term across the entire corpus. Terms that are common in many documents are given lower importance.
  - **TfidfVectorizer** converts raw documents into a matrix of TF-IDF features, which helps in understanding the significance of words in the context of the entire dataset.

- **PassiveAggressiveClassifier**:
  - An online learning algorithm that adjusts its weights aggressively in response to misclassifications, but remains passive when predictions are correct. It is designed to handle large-scale data efficiently and doesn't converge like other algorithms, focusing instead on making incremental updates to correct errors.

## Project Structure


