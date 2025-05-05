# 💊 Pharma Knowledge Assistant

A smart, AI-powered chatbot that serves as a virtual pharmacist — answering medical queries, suggesting alternatives, and summarizing drug information using cutting-edge LLM and RAG technologies.

## 🚀 Project Overview

This project was built during a Hackathon focused on practical applications of **Large Language Models (LLMs)**. The Pharma Knowledge Assistant helps users:
- Get accurate answers about medicines and their uses.
- Discover alternative drugs with fewer side effects.
- Summarize lengthy pharmaceutical documents.
- Receive health-based recommendations.

All of this is powered by **Retrieval-Augmented Generation (RAG)**, ensuring that responses are context-aware, grounded, and reliable.

## 🧠 How It Works

1. **User Query**: A question is submitted via the web interface.
2. **Retrieval (FAISS)**: Relevant documents are fetched from a local vector store.
3. **Augmentation**: Retrieved info is combined with the original query.
4. **Generation (LLM)**: A response is generated using an LLM like GPT.
5. **Display**: The answer is shown in a user-friendly interface (Streamlit).

## 🔧 Tech Stack

- **Language Model**: OpenAI / HuggingFace LLMs
- **Retrieval**: FAISS (vector similarity search)
- **Interface**: Streamlit
- **Backend**: Python
- **Data Preprocessing**: LangChain

## 📁 Features

- ✅ Question Answering about Drugs
- ✅ Alternative Medicine Suggestions
- ✅ Summarization of Drug Info
- ✅ Agent-based Modular Design
- ✅ RAG for Fact-Based Responses

### Prerequisites

- Python 3.8+
- OpenAI API Key (or any LLM API)
- `requirements.txt` dependencies

### Installation

```bash
git clone https://github.com/yourusername/pharma-knowledge-assistant.git
cd pharma-knowledge-assistant
pip install -r requirements.txt
