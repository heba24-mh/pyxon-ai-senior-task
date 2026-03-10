# Heba Task – Agentic AI Pipeline

## 📌 Overview
This project is an **Agentic AI Pipeline** built with Python and Jupyter/Colab.  
It creates an intelligent agent capable of:
- Searching the web for information (Search Agent).
- Reading and extracting text from articles (Reader Agent).
- Building a vector index using embeddings and FAISS (RAG).
- Retrieving the most relevant context (Retriever).
- Summarizing answers with a language model (Summarizer Agent).
- Displaying results interactively with ipywidgets (UI).

---

## ⚙️ Dependencies
Install the required libraries:

```bash
pip install ddgs requests beautifulsoup4 transformers sentence-transformers faiss-cpu ipywidgets🧠 Pipeline Components
- LLM Setup: Uses google/flan-t5-base for text generation.
- Embedding: Uses sentence-transformers (all-MiniLM-L6-v2) for text embeddings.
- Search Agent: Queries DuckDuckGo via ddgs.
- Reader Agent: Fetches and parses article text with BeautifulSoup.
- Build Index (RAG): Creates a FAISS vector index for retrieval.
- Retriever: Finds the most relevant context for a query.
- Summarizer Agent: Generates concise answers using the retrieved context.
- Router Agent: Decides whether the query is a URL, search, or RAG.
- UI: Interactive interface with text input, search button, and slider for results.
▶️ Usage
- Open the notebook in Google Colab or Jupyter.
- Run the dependency installation cell.
- Enter your query in the text box.
- Adjust the number of results with the slider.
- Click the 🔍 Search button.
- Results will appear in separate output boxes, each showing one article.
📚 Example
Query:
What is Artificial Intelligence?


The agent will:
- Search the web
- Read articles
- Build a vector index
- Retrieve relevant context
- Display results in separate boxes with summaries
👩‍💻 Author
Developed by Heba Al_Shebat – Visionary developer, designer, and aspiring AI trainer.
