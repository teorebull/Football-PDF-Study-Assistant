# Personal Study Assistant

A simple RAG-based study assistant that answers questions from PDFs (football tutorial in this case).  

The assistant:
- Takes a question about your PDF
- Retrieves relevant chunks using a vector store
- Uses an LLM to explain the concept in plain language and give examples

## Features
- Upload any PDF and ask questions about it
- Uses embeddings to retrieve relevant content
- Provides clear answers using a language model
- Currently uses **local models via Ollama**, but thanks to LangChain, it is easy to switch to **cloud-hosted LLMs** (like OpenAI, Cohere, etc.)

## Data
The data from this project can be found here: https://www.tutorialspoint.com/football/football_tutorial.pdf

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/study-assistant.git
cd study-assistant

