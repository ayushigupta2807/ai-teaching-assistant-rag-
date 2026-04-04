# RAG-based AI Teaching Assistant
## Overview
This project builds an AI-powered teaching assistant using Retrieval-Augmented Generation (RAG) on custom video data.

## Workflow
- Convert video to audio (mp3)
- Convert audio to text (JSON)
- Generate embeddings from text
- Store embeddings for retrieval
- Use LLM to answer user queries

## Tech Stack
- Python
- NLP
- LLM
- (Add tools like OpenAI, Whisper if used)

## Features
- Question-answering on custom data
- Semantic search using embeddings
- Context-based response generation

## How to Run
1. Add videos to folder
2. Run video_to_mp3
3. Run mp3_to_json
4. Run preprocess_json
5. Ask queries using LLM
