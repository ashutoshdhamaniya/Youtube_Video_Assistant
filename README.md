# 🎥 YouTube Video Assistant with LangChain & Google Gemini LLM

Developed an AI-powered assistant that extracts transcripts from YouTube videos and answers user queries based on the video content using RAG (Retrieval-Augmented Generation) technique and vector search.

## 🚀 Features

- 🔍 Fetches YouTube video transcripts using `youtube-transcript-api`
- 🧩 Splits and embeds transcript text using `Google Generative AI Embeddings`
- 🗃️ Stores embeddings in `FAISS` vector store for efficient semantic search
- 🧠 Implements Retrieval-Augmented Generation (RAG) using `LangChain`
- 💬 Uses `Google Generative AI LLM` to generate context-aware responses to user queries

## 🛠️ Tech Stack

- `LangChain`
- `YouTubeTranscriptAPI`
- `Google Generative AI (Gemini Models)`
- `FAISS Vector Store`

## 📦 Installation

Either Install the required libraries using below given command or use the requirements.txt file:

```bash
!pip install youtube-transcript-api langchain-community langchain-google-genai faiss-cpu
