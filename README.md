# FactSync

FactSync is an AI-powered research assistant that extracts and processes information from web articles, enabling users to ask contextual questions and receive accurate answers with source references.

## Key Features

- Web Article Processing: Fetches text from URLs and structures it for efficient retrieval.
- AI-Powered Q&A : Uses OpenAI's GPT models for answering user queries.
- FAISS-Based Search : Embeds and indexes extracted content for fast, similarity-based retrieval.
- Streamlit Interface: Provides a simple UI for interacting with the model.
- Source Attribution: Displays references for generated answers.

## Installation

1. Clone this repository to your local machine using:

```bash
  git clone https://github.com/codebasics/langchain.git
```
2. Navigate to the project directory:

```bash
  cd 2_news_research_tool_project
```
3. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```
4. Set up your OpenAI API key by creating a .env file in the project root and adding your API

```bash
  OPENAI_API_KEY=your_api_key_here
```

## Usage/Examples

1. Run the Streamlit app by executing:
```bash
streamlit run main.py
```

## Project Structure

- main.py: The main Streamlit application script.
- requirements.txt: A list of required Python packages for the project.
- faiss_store_openai.pkl: A pickle file to store the FAISS index.
- .env: Configuration file for storing your OpenAI API key.
