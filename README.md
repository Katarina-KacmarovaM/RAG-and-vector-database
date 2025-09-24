# My own Knowledge Worker

This repository contains a Jupyter notebook (`knowledge_worker.ipynb`) that demonstrates the creation of a personal knowledge worker using LangChain, ChromaDB, OpenAI embeddings, and Gradio for a user interface. The project aims to build a conversational AI that can answer questions based on a custom knowledge base.

## Features

- **Custom Knowledge Base Integration**: Easily integrate your own documents (e.g., Markdown files) to create a personalized knowledge base.
- **Vector Database**: Utilizes ChromaDB for efficient storage and retrieval of document embeddings.
- **OpenAI Embeddings**: Leverages OpenAI's powerful embeddings for semantic understanding of text.
- **Conversational AI**: Built with LangChain's `ConversationalRetrievalChain` to enable natural language interactions with the knowledge base.
- **Interactive User Interface**: Provides a user-friendly chat interface powered by Gradio.
- **Visualization**: Includes 2D and 3D visualizations of the vector database using Plotly to understand the distribution of document embeddings.

## Getting Started

To get this project up and running, follow these steps:

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.8+
- `pip` (Python package installer)
- An OpenAI API key (set as an environment variable `OPENAI_API_KEY`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name

   ```
2. Create a virtual environment and activate it:
   
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt

   ```

4. Set up your OPENAI API KEY
   


