# YouTube Question Answering System

## Overview
The **YouTube Question Answering System** processes video transcripts, dynamically chunks text, and summarizes key dialogues using **generative AI**. It implements a **hybrid search mechanism** to retrieve relevant information based on user queries, enhancing the accessibility and efficiency of extracting insights from video content.

## Features
- **Transcript Processing**: Extracts and processes video transcripts for analysis.  
- **Dynamic Text Chunking**: Segments transcripts into meaningful chunks for better context understanding.  
- **Generative AI Summarization**: Summarizes key dialogues to highlight important information.  
- **Hybrid Search Mechanism**: Combines keyword-based and semantic search to retrieve relevant responses.  
- **Efficient Query Handling**: Provides accurate answers based on user input.  

## Tech Stack
- **Backend**: Python, Flask  
- **Machine Learning**: OpenAI GPT, NLP models  
- **Database**: MongoDB (or SQLite for lightweight usage)  
- **Search Mechanism**: FAISS, BM25  
- **Frontend**: React (optional, for UI)  

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/youtube-qna-system.git
   cd youtube-qna-system
