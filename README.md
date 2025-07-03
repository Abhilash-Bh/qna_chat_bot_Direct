# qna_chat_bot_Direct
# End To End Powerful Document Q&A Chatbot using Llama3, Langchain, and Groq API

## Overview

This project aims to create a powerful Document Q&A Chatbot utilizing the capabilities of Llama3, Langchain, and the Groq API. The chatbot is designed to efficiently parse and comprehend documents, providing precise answers to user queries.


## Features

- **Llama3 Integration:** Leveraging Llama3 for natural language processing and understanding.
- **Langchain:** Utilizing Langchain for managing chains of LLMs, APIs, and custom actions.
- **Groq API:** Integrating with the Groq API to accelerate and optimize machine learning model inference.
- **End-to-End Pipeline:** A complete pipeline from document ingestion to question answering.

## Architecture



1. **Document Ingestion:** Documents are uploaded and preprocessed for efficient querying.
2. **Question Understanding:** The chatbot uses Llama3 to comprehend and break down the user query.
3. **Answer Retrieval:** Langchain orchestrates the flow between components, ensuring accurate answers.
4. **Optimized Inference:** The Groq API enhances the performance of the underlying models, delivering quick responses.

## Installation

### Prerequisites

- Python 3.8+
- Pip
- Groq API credentials

### Clone the Repository

```bash
git clone https://github.com/TLILIFIRAS/Document-Q-A-Chatbot-using-Llama3-Langchain-and-Groq-API.git
cd Document-Q-A-Chatbot-using-Llama3-Langchain-and-Groq-API
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Set Up Environment Variables
Create a .env file in the root directory with your Groq API and OpenAI API credentials:
```bash
GROQ_API_KEY=your_api_key_here
OPENAI_API_KEY=your_llama3_api_key_here
```
### Run the Application

```bash
python application.py
```

### Usage

- Place your Documents:  Place your documents in the input folder .
- Ask Questions: Type your question in the chat interface.
- Receive Answers: The chatbot will process your query and return the most relevant answer from the document.
### Example :
```bash
**User:** What are the main benefits of using Llama3?
**Chatbot:** Llama3 offers advanced natural language processing capabilities, enabling high accuracy in text comprehension and generation. It is also highly scalable for various NLP tasks.
```
