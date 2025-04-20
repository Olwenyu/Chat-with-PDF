# PDF QA App using LangChain and Ollama

This application allows users to upload PDF documents and interact with them by asking natural language questions. Built using **LangChain** and **Ollama**, it leverages **embeddings** and **vector storage** to perform efficient document retrieval and generate **concise, context-aware answers**.

The project is implemented based on the video tutorial: [Chat with PDFs with Deepseek Ollama LangChain](https://www.youtube.com/watch?v=vfpe2S22g4c)

---

## Features

- Upload and process PDF documents
- Ask questions about the content of uploaded documents
- Intelligent responses powered by LangChain and Ollama
- Uses vector embeddings for fast and relevant retrieval
- Contextual answers grounded in document content

---

## Tech Stack

- **LangChain** – Framework for context-aware LLM applications
- **Ollama** – Local LLM runtime for fast and private inference
- **FAISS** – Vector database for semantic search
- **PyPDF** – PDF text extraction
- **Streamlit** – Frontend and Backend

---

## Installation
1. Ollama installed through [install](https://ollama.com/) and Deepseek downloaded in Ollama:
```bash
   ollama run deepseek-r1:1.5b
```
2. Clone the repository:
```bash
  git clone https://github.com/Olwenyu/Chat-with-PDF.git
  cd Chat-with-PDF
```
3. Install the required packages:
```bash
   pip install -r requirements.txt
```
## Run Application
1. Run the Streamlit application:
```bash
  streamlit run app.py
```
2. Access application in the web browser through [link](http://localhost:8501/)
3. Upload a PDF file and start Q&A


