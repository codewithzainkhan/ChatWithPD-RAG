# ChatWithPDF - Conversational Interaction with PDF Data

This project enables conversational interaction with PDF data using machine learning models. The provided notebook demonstrates how to query PDF documents using natural language and extract relevant information.

The included PDF contains data related to Pakistan, but users can replace this with any other PDF of their choice.

## Features
- **Natural Language Queries**: Interact with PDFs by asking questions in natural language.
- **Customizable PDF Input**: Replace the existing PDF with any PDF file for your own use case.
- **Machine Learning Integration**: Utilizes transformers and language models for text extraction and comprehension.

## Workflow
1. **Load PDF**: The notebook reads a PDF file, extracting text data.
2. **Preprocess Text**: Text from the PDF is cleaned and structured for better querying.
3. **Set Up Transformer Models**: Language models are loaded using the `transformers` library to enable natural language queries.
4. **Query the PDF**: Users can input questions, and the model will extract and present relevant information from the PDF.

## Example Queries
- "What is the population of Pakistan in 2021?"
- "Show me the economic data for Pakistan from the document."
- "What are the key highlights of the Pakistan census?"
