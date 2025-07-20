# LangChain LLM Repository

A comprehensive collection of Jupyter notebooks demonstrating LangChain framework concepts and applications for building LLM-powered applications.

## Overview

This repository contains hands-on tutorials covering essential LangChain components from basic model interactions to advanced RAG (Retrieval-Augmented Generation) implementations and AI agents. Perfect for data scientists and developers looking to master LangChain for production-ready LLM applications.

## Repository Structure

### Core LangChain Concepts

- **01-03_langchain_models_quickstart.ipynb** - Introduction to LangChain models and basic usage
- **04_Langchain_prompts.ipynb** - Prompt engineering and template management
- **05_StructuredOP_langchain.ipynb** - Structured output generation
- **06_output_parsers.ipynb** - Parsing and formatting LLM outputs
- **07_chain.ipynb** - Building and chaining LangChain components
- **08_why_runnables.ipynb** - Understanding LangChain's runnable interface
- **09_using_runnable_primitives.ipynb** - Working with runnable primitives


### RAG Implementation

- **10_rag_document_loader.ipynb** - Loading and processing documents
- **11_rag_text_splitter.ipynb** - Text chunking strategies
- **12_vector_store.ipynb** - Vector database integration
- **13_retriever.ipynb** - Retrieval mechanisms
- **14-15_rag-using-langchain.ipynb** - Complete RAG pipeline implementation


### Tools and Agents

- **16-17_langchain_tools.ipynb** - Custom tool development
- **17_langchain_tools_ex_currency_conv.ipynb** - Currency conversion tool example
- **18_ai_agents_in_langchain.ipynb** - AI agent creation and management


### Supporting Files

- **input_files/** - Sample data and documents for tutorials
- **templates/** - Reusable prompt templates
- **requirements.txt** - Python dependencies


## Prerequisites

- Python 3.11 or higher
- Basic understanding of machine learning concepts

## Installation

1. Clone the repository:
```bash
git clone https://github.com/SamKur/langchain-llm.git
cd langchain-llm
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your API keys (OpenAI, etc.) in environment variables.
   Create a `.env` file in the root directory with the following content:
   ```plaintext
   OPENAI_API_KEY = "sk-proj-..."
   ANTHROPIC_API_KEY = "..."
   GOOGLE_API_KEY = "..."
   PPLX_API_KEY = "..."
   HUGGINGFACEHUB_ACCESS_TOKEN = "..."
   HUGGINGFACEHUB_API_TOKEN = "..."
   EXCHANGERATE_API_KEY = "..."
   LANGSMITH_API_KEY = "..."
   LANGSMITH_ENDPOINT = "..."
   TAVILY_API_KEY = "..."
   OPENWEATHERMAP_API_KEY = "..."
   PINECONE_API_KEY = "..."
   ```

## Getting Started

1. Start with **01-03_langchain_models_quickstart.ipynb** for basic LangChain concepts
2. Progress through prompts and output parsing (notebooks 04-06)
3. Learn about chains and runnables (notebooks 07-09)
4. Implement RAG systems (notebooks 10-15)
5. Explore tools and agents (notebooks 16-18)

## Key Features

- **Progressive Learning Path** - Tutorials build upon each other systematically
- **Practical Examples** - Semi-real-world use cases like currency conversion tools, weather data retrieval, and more
- **RAG Implementation** - Complete retrieval-augmented generation pipeline
- **Agent Development** - AI agent creation and tool integration
- **Production-Ready Habits** - Best practices and structured approaches


## Learning Outcomes

After completing these tutorials, you'll be able to:

- Build LLM applications using LangChain framework
- Implement RAG systems for document-based question answering
- Create custom tools and AI agents
- Structure outputs and parse LLM responses effectively
- Chain multiple LLM operations for complex workflows

## Huge Thanks and Credits

Nitish Sir (CampusX) - Langchain Playlist

## Contributing

Feel free to submit issues, feature requests, or pull requests to improve the tutorials.


