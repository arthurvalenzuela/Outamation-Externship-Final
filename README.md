# RAG-Pipeline-Externship
## Project Overview

This repository contains the final project for the Outamation externship, featuring an AI-powered **RAG (Retrieval-Augmented Generation) Pipeline** nicknamed "Lucky". This project demonstrates expertise in building intelligent document question-answering systems using state-of-the-art AI technologies and vector databases.

The RAG pipeline processes PDF documents, creates searchable embeddings, and enables natural language question-answering by combining information retrieval with large language models.

## Features

- **PDF Document Processing**: Extracts and processes text from PDF files using PyMuPDF and Surya OCR
- **Vector Store Integration**: Utilizes LlamaIndex with Qdrant for efficient document embeddings and retrieval
- **AI-Powered Question Answering**: Leverages large language models for intelligent responses to user queries
- **Embeddings Management**: Implements HuggingFace sentence transformers for semantic search capabilities
- **Google Colab Ready**: Fully configured to run in Google Colab environment with all dependencies

## Technologies Used

- **Python 3.x**: Core programming language
- **LlamaIndex**: Framework for building LLM applications with RAG capabilities
- **Qdrant**: Vector database for storing and retrieving document embeddings
- **PyMuPDF & Surya**: PDF processing and OCR libraries
- **PyTorch**: Deep learning framework for AI models
- **HuggingFace Transformers**: Pre-trained models for embeddings and NLP tasks
- **Google Colab**: Development and execution environment

## Getting Started

### Prerequisites

- Google account for Colab access (recommended), or
- Python 3.7 or higher installed locally
- Basic understanding of AI/ML concepts and Jupyter notebooks

### Installation

1. **Open in Google Colab** (Recommended):
   - Click on the notebook file `RAG_Pipeline_"Lucky".ipynb`
   - Click "Open in Colab" button at the top

2. **Or Clone the repository** for local use:
   ```bash
   git clone https://github.com/arthurvalenzuela/RAG-Pipeline-Externship.git
   cd RAG-Pipeline-Externship
   ```

3. **Install required dependencies**:
   - If using Colab, run Cell 1 in the notebook to install all dependencies
   - If running locally, install packages manually:
   ```bash
   pip install PyMuPDF surya-ocr torch
   pip install llama-index llama-index-embeddings-huggingface
   pip install llama-index-vector-stores-qdrant
   ```

## Usage

1. **Run the notebook cells in sequence**:
   - Cell 1: Installs all required libraries
   - Cell 2: Imports necessary modules and dependencies
   - Subsequent cells: Follow the pipeline flow for document processing and Q&A

2. **Upload your PDF documents** when prompted

3. **Ask questions** about your documents in natural language

4. **Receive AI-generated answers** based on document content

## Project Structure

```
RAG-Pipeline-Externship/
│
├── RAG_Pipeline_"Lucky".ipynb    # Main Jupyter notebook with RAG implementation
├── README.md                      # Project documentation
└── LICENSE                        # MIT License
```

## Key Capabilities

- **Semantic Search**: Find relevant information across documents using meaning, not just keywords
- **Context-Aware Responses**: Generate answers that synthesize information from multiple sources
- **Scalable Architecture**: Built to handle multiple documents and large datasets
- **API Integration**: Uses Google Colab's secure userdata storage for API keys

## License

This project is available for educational and portfolio purposes under the MIT License. Please refer to the LICENSE file for specific terms and conditions regarding use, modification, and distribution.

## Contact

**Arthur Valenzuela**

For questions, feedback, or collaboration opportunities, please feel free to reach out through GitHub or connect via the repository's Issues section.

---

*Developed as part of the Outamation Externship Program*
