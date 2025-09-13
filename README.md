# Medical RAG Chatbot

A **medical question-answering chatbot** that uses **retrieval-augmented generation (RAG)** to provide concise, context-aware answers from medical documents. The system combines PDF ingestion, semantic search, and GPT-4o to deliver accurate responses in real-time.

---

## **Features**
- **Contextual Q&A:** Uses GPT-4o to answer medical questions based on uploaded PDFs.  
- **Semantic Search:** Retrieves relevant document chunks using **Pinecone vector database** and Hugging Face embeddings.  
- **PDF Processing:** Extracts, filters, and chunks PDFs for embedding and efficient retrieval.  
- **Web Interface:** Flask-based frontend for user-friendly interaction.  
- **Dockerized Deployment:** Runs in Docker containers for easy portability.  
- **CI/CD Pipeline:** Automated builds and deployment to AWS EC2 via GitHub Actions.  

---

## **Tech Stack**
- **Programming:** Python  
- **Web Framework:** Flask  
- **Embeddings:** Hugging Face Sentence Transformers (`all-MiniLM-L6-v2`)  
- **Vector Database:** Pinecone (serverless, cosine similarity)  
- **LLM:** OpenAI GPT-4o  
- **Containerization & Deployment:** Docker, AWS EC2  
- **CI/CD:** GitHub Actions, Amazon ECR  

---
