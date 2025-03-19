# LLM-Based Chatbot with OCR & Tabulated PDF Processing  

## Project Overview  
This project is an AI-powered **Retrieval-Augmented Generation (RAG) chatbot** that extracts knowledge from **OCR-based and tabulated PDFs** to provide accurate and context-aware responses. It integrates **Large Language Models (LLMs)** with **vector-based information retrieval** to enhance transparency and reliability in chatbot interactions.  

##  Features  
- **OCR-Based PDF Processing:** Extracts text from scanned PDFs using **Tesseract OCR & PyMuPDF**.  
- **Tabulated PDF Processing:** Extracts structured table data using **pdfplumber & Camelot**.  
- **Retrieval-Augmented Generation (RAG):** Uses **FAISS/Pinecone** for document retrieval and **LLMs (GPT/Llama)** for response generation.  
- **Streamlit Frontend:** Interactive UI for user-friendly chatbot interaction.  
- **Performance Evaluation:** Uses **precision, recall, and response quality metrics** to improve chatbot accuracy.  

##  Tech Stack  
- **Programming Language:** Python 
- **Frameworks:** Streamlit, PyMuPDF, pdfplumber, Camelot  
- **Machine Learning Models:** Sentence Transformers, OpenAI GPT-4, Llama  
- **Vector Database:** FAISS / Pinecone  

##  Project Workflow  
1. **Data Extraction:**  
   - OCR for scanned PDFs (Tesseract, PyMuPDF)  
   - Table extraction for tabulated PDFs (pdfplumber, Camelot)  
2. **Data Processing:**  
   - Text cleaning & chunking  
   - Embedding generation using Sentence Transformers  
3. **Vector Storage & Retrieval:**  
   - Store embeddings in FAISS/Pinecone  
   - Retrieve relevant chunks based on user queries  
4. **LLM Response Generation:**  
   - Use GPT-4 / Llama to generate responses from retrieved data  
5. **Frontend Interaction:**  
   - Streamlit-based UI for chatbot interaction  

