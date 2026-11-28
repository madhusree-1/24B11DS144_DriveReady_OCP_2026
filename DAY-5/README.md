# Routine Rescue AI — Day 5

## Overview
Routine Rescue AI is extended with a PDF-based Study Assistant using Retrieval-Augmented Generation (RAG).

Students can upload study PDFs, extract their content, search relevant information and ask questions based on the uploaded study material.

## Objectives
- Compare Sentence Transformer embedding models.
- Extract text from PDF files.
- Handle scanned PDFs using OCR.
- Divide extracted text into chunks.
- Generate embeddings.
- Store embeddings using FAISS.
- Retrieve relevant chunks for a question.
- Generate answers using retrieved context and Groq.

## Technologies Used
- Python
- Google Colab
- PyMuPDF
- Tesseract OCR
- Sentence Transformers
- FAISS
- NumPy
- Groq API

## Implementation

### 1. Embedding Model Comparison
Compared `all-MiniLM-L6-v2` and `all-mpnet-base-v2` using a sample sentence.

### 2. PDF Text Extraction
Used PyMuPDF to extract text from PDFs and Tesseract OCR for scanned pages.

### 3. Text Chunking
Split PDF text into chunks using a chunk size of 500 characters and an overlap of 100 characters.

### 4. Embeddings
Converted text chunks into vector representations using `all-MiniLM-L6-v2`.

### 5. FAISS Vector Index
Stored embeddings in a FAISS index to support similarity search.

### 6. Retrieval
Converted student questions into embeddings and retrieved the top relevant chunks.

### 7. RAG Answer Generation
Passed retrieved PDF context and the question to Groq's LLM to generate a context-based answer.

### 8. Interactive Study Assistant
Implemented an interactive question-answering loop for students.

## Architecture

PDF Upload → Text Extraction / OCR → Chunking → Embeddings → FAISS Index → Question Retrieval → Groq LLM → Answer

## Testing
- PDF upload
- Text extraction
- OCR fallback
- Chunk creation
- Vector generation
- FAISS search
- PDF-based questions
- Interactive question-answering

## Outcome
Routine Rescue AI gained a PDF-based study assistant that retrieves relevant information from uploaded notes and generates contextual answers.

**Routine Rescue AI — From managing tasks to learning from study material.**
