# Langchain_OpenAI_Chroma_QA
A repository to highlight examples of using the Chroma (vector database) with LangChain (framework for developing LLM applications).

![Alt text](langchain-chroma-light.png)

Document Question-Answering
For an example of using Chroma+LangChain to do question answering over your own custom document.

**Packages Installed:**

langchain: This package is the main LangChain library, which facilitates seamless integration with OpenAI models for creating interactive chat experiences with text documents.

openai: This is the official Python package for OpenAI's API, enabling you to work with the powerful language models provided by OpenAI, such as GPT-4.

chromadb: ChromaDB is a lightweight, high-performance, schema-less vector database designed for use with AI applications. It allows you to store, retrieve, and manage the vector data (embeddings) required for your LangChain and OpenAI-powered document chat applications.

**Summary:**

The code reads a text document, splits it into smaller chunks, and generates embeddings using OpenAI models. Then, it creates and persists a Chroma database containing the embeddings and associated metadata. This allows for efficient storage and retrieval of document embeddings for AI-driven text analysis and interactions.

In summary, this code creates a simple QA system using LangChain, OpenAI models, and a Chroma database. It prompts the user for a question, processes the question using the QA system, and returns the answer.

The powerful combination of OpenAI models and LangChain has opened up new possibilities for transforming the way we interact with text documents. 


