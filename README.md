📚 RAG Based Chat Bot
A Retrieval-Augmented Generation (RAG) chatbot that allows users to upload documents and ask questions based on their content.

The system uses:

FastAPI (Backend)
HTML, CSS, JavaScript (Frontend)
FAISS Vector Database
Sentence Transformers (Embeddings)
Mistral 7B GGUF Local LLM
Memory Management System
Smart Study Tools
🚀 Features
📂 Multi File Upload
Supports:

PDF
DOCX
TXT
CSV
JSON
PPT
PPTX
Images (PNG, JPG, JPEG)
Users can upload multiple files simultaneously.

🤖 RAG Question Answering
Ask questions directly from uploaded documents.

Examples:

Explain Neural Networks
What is Deep Learning?
Summarize Unit 3
Give key points from page 5
📝 Smart Summarization
Generate:

Full Summary
Page Summary
Key Points
🧠 Memory Management
Similar to ChatGPT memory.

Users can:

Add Memory
Edit Memory
Delete Memory
Clear Memory
Example:

My team name is Orchid
The chatbot remembers and uses this information in future responses.

Memory stored in:

backend/memory/memory.txt
🎓 Smart Study Tools
Generate Questions
Automatically creates study questions from uploaded documents.

Example:

What is Deep Learning?
Explain CNN architecture.
What are the applications of AI?
Create Quiz
Generates Top 5 MCQ Questions.

Example:

1. What is AI?

A) Artificial Intelligence
B) Automatic Input
C) Advanced Internet
D) None

Answer: A
📄 Export Notes
Export generated notes and summaries.

⚙️ Technologies Used
Backend
Python
FastAPI
Uvicorn
Vector Search
FAISS
Embedding Model
sentence-transformers/all-MiniLM-L6-v2
LLM
Mistral-7B-Instruct-v0.1.Q4_K_M.gguf
Loaded locally using:

ctransformers
📦 Installation
Clone Repository
git clone https://github.com/your-username/RAG-ChatBot.git

cd RAG-ChatBot
📸 Screenshots
Main Interface
Upload documents
Ask questions
View responses
Memory System
Save custom user preferences
Edit/Delete memories
