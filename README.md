# Mini Semantic Search Engine for AI/ML FAQs

## Overview
This project is a mini semantic search engine that retrieves relevant
AI and machine learning FAQs based on the meaning of a user's question.

## Features
- Loads FAQ data using Pandas
- Cleans missing and duplicate data
- Converts FAQ text into chunks
- Generates embeddings using Sentence Transformers
- Stores embeddings in ChromaDB
- Retrieves the top three relevant FAQs
- Displays search results with distance scores

## Technologies
- Python
- Pandas
- Sentence Transformers
- ChromaDB
- Google Colab

## Embedding Model
sentence-transformers/all-MiniLM-L6-v2

## How to Run
1. Install dependencies using requirements.txt.
2. Open week2_semantic_search.ipynb in Google Colab or Jupyter.
3. Run the notebook cells in order.
4. Enter a query using the semantic_search function.

## Dataset
The faqs.csv file contains AI/ML questions and answers.

## Example Query
How can computers learn from examples?

## Limitations
Search results depend on the quality and coverage of the FAQ dataset.
The system retrieves existing answers and does not generate new answers.
