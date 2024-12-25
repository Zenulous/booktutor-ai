# BookTutor AI: Convert Any Book into an AI Tutor

## How does it work?

**Highly recommended** See https://youtu.be/GTidrAiojbg for an explainer video!

Transform any PDF book into an interactive AI tutor that can answer questions, explain concepts, and help you understand the material better. BookTutor uses advanced language models and RAG (Retrieval-Augmented Generation).

## Prerequisites

- Python 3.x
- LM Studio running a local LLM locally (default endpoint: http://localhost:1234)

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. Ensure LM Studio is running a language model locally with the API endpoint available

## Usage

Start your AI tutor with any PDF book:
```bash
python booktutor.py path/to/your/textbook.pdf
```

The system will:
1. Process your book (first run only)
2. Create a knowledge base (first run only)
3. Save the processed data for faster future access
4. Start an interactive tutoring session
