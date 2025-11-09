## Mini Retrieval-Augmented Generation (RAG) System

This project is a simple RAG system built in Python using Hugging Face Transformers.
It retrieves relevant context from a custom knowledge base and generates precise, fact-based answers.

## 🔍 Features

Retriever: Sentence-transformers (MiniLM) for semantic similarity search

Generator: DistilBERT QA model for extracting answers from retrieved text

Extended Knowledge: Added custom facts (e.g., about Mars)

Interactive QA: Users can query and test responses in Colab

## 📘 Tech Stack

* Python
* Hugging Face Transformers
* SentenceTransformers
* Google Colab
  
## 📊 Example
Input question: What is the average distance between Earth and Mars?

Output: The average distance is about 225 million kilometers.

## 📂 Files
mini_rag_system.ipynb: Main project notebook
