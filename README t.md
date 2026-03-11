# Agentic AI Research Assistant

## Overview

This project implements an Agentic AI pipeline built with Python and Google Colab.

The system creates an intelligent agent capable of:

- Searching the web for information
- Extracting text from articles
- Building a vector index using FAISS
- Retrieving relevant context using embeddings
- Generating summarized answers using a language model
- Displaying results through an interactive interface

---

## Technologies Used

Python  
Transformers (HuggingFace)  
Sentence Transformers  
FAISS Vector Database  
DuckDuckGo Search (ddgs)  
BeautifulSoup  
ipywidgets  

---

## System Architecture

User Query  
↓  
Router Agent  
↓  
Search Agent  
↓  
Reader Agent  
↓  
Vector Index (FAISS)  
↓  
Retriever  
↓  
Summarizer Agent  
↓  
Final Answer + Sources

---

## Dependencies

Install required libraries:

pip install ddgs requests beautifulsoup4 transformers sentence-transformers faiss-cpu ipywidgets

---

## How to Run

1. Open the notebook in Google Colab.
2. Run the installation cell.
3. Enter your query in the input box.
4. Adjust the number of results using the slider.
5. Click the Search button.

The system will search the web, retrieve information, and generate summarized answers.

---

## Example Query

What is Artificial Intelligence?

The system will:
- Search the web
- Extract article text
- Build a vector index
- Retrieve relevant context
- Generate an answer using the language model
- Display the results with sources

---

## Author

Heba Al_Shebat  
AI Developer and Data Science Graduate
