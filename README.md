# FactSync

FactSync is an AI-powered research assistant that extracts and processes information from web articles, enabling users to ask contextual questions and receive accurate answers with source references.

## Key Features

- Web Article Processing: Fetches text from URLs and structures it for efficient retrieval.
- AI-Powered Q&A : Uses OpenAI's GPT models for answering user queries.
- FAISS-Based Search : Embeds and indexes extracted content for fast, similarity-based retrieval.
- Streamlit Interface: Provides a simple UI for interacting with the model.
- Source Attribution: Displays references for generated answers.

## Installation

1. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```
2. Set up your OpenAI API key by creating a .env file in the project root and adding your API

```bash
  OPENAI_API_KEY = your_api_key
```

## Usage

1. Run the Streamlit app by executing:
```bash
streamlit run main.py
```

## Project Structure

- main.py: The main Streamlit application script.
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your OpenAI API key.
- faiss_store_openai/: Directory containing FAISS index files.
  - index.faiss: FAISS index file storing embeddings.
  - index.pkl: Metadata file for FAISS index.
- Notebooks/: Jupyter notebooks for testing & development.
  - FAISS_Index.ipynb: Notebook for FAISS index creation.
  - Retrieval.ipynb: Notebook for retrieval & query handling.
  - TextLoader_Splitter.ipynb: Notebook for text processing.
  - movies.csv: Sample dataset for testing.
  - sample_news.txt: Sample news text file.
  - sample_text.csv: Sample text data file.
  - vector_index.pkl: Precomputed FAISS vector index.



