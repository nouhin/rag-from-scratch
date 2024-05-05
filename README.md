# RAG from scratch
This is a repository for the RAG (Retrieval Augmented Generation) model from scratch.
## Overview
RAG is a tool that helps you find answers to questions using a custom dataset. Here’s how it works:
1. **Indexing** - First, the data in your custom dataset is transformed into embeddings, which are numerical representations that capture the essence of the data in a high-dimensional space.
2. **Question Processing** - When you ask a question, the system converts it into an embedding as well.
3. **Retrieval** - The system then searches for the embeddings in the dataset that are most similar to the embedding of your question.
4. **Generation** - Based on these similar embeddings, RAG generates an answer to your question.
## Indexing
* Text imbedding 
## Retrieval
Similarity search
