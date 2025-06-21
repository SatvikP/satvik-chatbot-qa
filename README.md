# satvik-chatbot-qa
Ask Anything to Satvik's Chatbot

# Personal Blog Q&A Bot

A semantic search-powered Q&A system that answers questions about my blog content using RAG (Retrieval Augmented Generation).

## Features
- 🔍 Semantic search through blog content using FAISS
- 🤖 Powered by Claude 3.7 Sonnet via Anthropic API
- 📝 Answers questions in my personal voice and style
- 🆓 Uses free HuggingFace embeddings (runs locally)


## Setup
1. Clone this repo
2. Create virtual environment: `python -m venv venv`
3. Activate it: `source venv/bin/activate` (Mac/Linux) or `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Set API key: `export ANTHROPIC_API_KEY="your-key"`
6. Run: `python main.py`

## Usage
Ask questions about the content and get AI-powered responses based on the blog posts.
