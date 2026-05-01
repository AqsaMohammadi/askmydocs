AskMyDocs



AskMyDocs lets you upload any document — a resume, research paper, lecture notes, business report — and just *talk* to it. 
Ask questions in plain English and get instant, accurate answers powered by Google Gemini AI.

## What it can do

Upload a file and start a conversation with it. That's the core idea. But there's more:

- Supports multiple file types — PDF, Word docs, PowerPoint, plain text, and images
- Remembers your chats — every conversation is saved so you can come back to it later
- Summarize in one click — get the key points of any document or conversation as bullet points
- Generate flowcharts — turn complex processes into visual diagrams automatically
- Voice input & output — speak your questions and listen to the answers
- Secure by default — every user has their own private data, nobody else can see your documents

## How it works

When you upload a file, the app breaks it into small chunks, converts them into embeddings (numerical representations of meaning),
and stores them in a vector database. When you ask a question, it finds the most relevant chunks and sends them to Gemini along with your question.
Gemini then answers based only on what's in your document — no hallucinations, no made-up facts.

This pattern is called RAG (Retrieval-Augmented Generation) and it's how most production AI document tools work.

## Tech used

**Backend** — FastAPI, Python, ChromaDB, sentence-transformers, SQLite, JWT auth

testing pr

**Frontend** — React, TypeScript, Vite, Tailwind CSS

**AI** — Google Gemini API

**File parsing** — pdfplumber, python-docx, python-pptx, pytesseract (for images) it' s enought right
