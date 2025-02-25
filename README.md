# ChikitSaar
# AI-Powered Medical Report Simplifier

##  Overview
Imagine getting your medical report and actually understanding what it says, without needing a medical degree or a frantic Google deep dive. That’s what this AI-powered system does. It deciphers complex medical jargon, breaks down test results into simple language, and even provides context so you know what your numbers actually mean.
At its core, the system uses Retrieval-Augmented Generation (RAG), a fancy way of saying it pulls from a vast medical knowledge base to give you accurate, evidence-based explanations instead of just making things up. It processes your report, identifies key medical terms, and retrieves the most relevant information to help you understand what’s going on. It even answers follow-up questions, just like a doctor would, except it won’t rush you through an appointment.

##  Tech Stack
- **Backend:** Flask (Handles authentication, report processing, and AI integration)
- **Frontend:** React (Provides a clean and user-friendly interface)
- **OCR:** Tesseract (Extracts text from scanned medical reports)
- **AI Model:** Gemini (Generates accurate medical explanations)
- **Vector Database:** ChromaDB (Stores and retrieves relevant medical context)
- **Web Scraping:** BeautifulSoup (Fetches medical data from WebMD, Mayo Clinic, WHO)
- **Development & Testing:** Jupyter Notebook (For model testing and refinement)

## Features
- Upload medical reports (PDFs or images)
- Extract text using OCR
- Identify key medical terms using Named Entity Recognition (NER)
- Retrieve relevant medical literature via ChromaDB
- Generate easy-to-understand explanations using Gemini


## 📝 Setup & Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/xmwriam/ChikitSaar.git
2. Start the backend:
    ```sh
    cd backend
    flask run

3. Start the frontend:
    ```sh
    cd frontend
    npm start

