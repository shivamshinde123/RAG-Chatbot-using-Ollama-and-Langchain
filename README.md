# RAG Chatbot using OpenAI and Langchain

This chatbot will answer the question related to pdf that you upload.

## How to run the code locally

**Step 1:**

Run the following command in the command prompt to initiate the git operations

```
git init
```

**Step 2:**

Run the following command in the command promt to clone this repository

```
https://github.com/shivamshinde123/RAG-Chatbot-using-Ollama-and-Langchain.git
```

**Step 3:**

Replace the Langsmith API keys in the .env file

**Step 4:**

Go to following website and download Ollama

```
https://ollama.com/
```

**Step 5:**

Run the following command in the command prompt download generation and embedding models

Generation Model:

```
ollama run qwen2.5:0.5b
```
Embedding Model:

```
ollama run granite-embedding:30m
```

**Step 4:**

Run the following command in the command prompt to run the chatbot app

```
streamlit run app.py
```

