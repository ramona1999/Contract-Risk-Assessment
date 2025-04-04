# AI-Powered Contract Risk Assessment and Legal Assistant

📌 Disclaimer
This AI-powered tool is not a replacement for legal advice. Always consult a professional lawyer for critical contract decisions.

## 📌 Project Overview
This project automates contract analysis, risk assessment, and legal Q&A** using state-of-the-art **Generative AI and NLP** techniques. It extracts key clauses, identifies potential legal risks, and suggests recommendations. A fine-tuned chatbot is also included for **conversational Q&A** on contract-related queries.

## 🚀 Features
- **Contract Clause Extraction**: Identifies key clauses (liability, confidentiality, termination, etc.).
- **Risk Assessment**: Classifies risks (legal, financial, compliance) and rates severity.
- **Recommended Actions**: Provides mitigation strategies for identified risks.
- **Conversational Legal Assistant**: Fine-tuned chatbot for interactive contract-related Q&A.
- **Efficient Retrieval**: Uses hybrid chunking and Milvus vector database for precise legal text retrieval.
  

## 🛠️ Tech Stack
- **LangChain** (RAG-based legal text processing)
- **Langgraph**(State-based workflows)
- **Milvus** (Vector database for efficient retrieval)
- **Hugging Face Transformers** (LLMs for text generation)
- **Docling** (Document processing & chunking)
- **Streamlit** (Interactive UI)
- **Unsloth** (Optimized fine-tuned LLM deployment)

## 📂 Project Structure
📦 contract-risk-analysis
┣ 📜 app.py         # Main Streamlit app
┣ 📜 requirements.txt  # Dependencies
┣ 📜 README.md      # Project documentation
┗ 📂 models/        # Fine-tuned LLMs (if applicable)




## 🎯 How It Works
1. **Upload a contract (PDF)**
2. **AI extracts key clauses** and presents them in a structured format.
3. **Risk assessment** is performed to classify risks and suggest mitigation.
4. **Fine-tuned chatbot** provides real-time answers for legal Q&A.

## ✨ Future Enhancements

Add support for multiple legal jurisdictions.
Improve chatbot accuracy with more fine-tuned legal datasets.
Implement contract comparison for risk benchmarking.

## 🔧 Setup & Installation
 1️⃣ Install dependencies:
```bash
pip install -r requirements.txt

streamlit run app.py


