# 🤖 Mini LLM App

A lightweight, local AI-powered chatbot using OpenAI's GPT API. Built with Python and Streamlit, this app helps you interact with LLMs in a clean UI.

---

## 📌 Features

- Ask anything to GPT-3.5 / GPT-4
- Clean chat interface using Streamlit
- Local development setup
- Easily expandable for RAG, image generation, or code features

---

## 🛠️ Tech Stack

| Layer        | Technology        |
|--------------|-------------------|
| Frontend     | Streamlit         |
| Backend      | Python            |
| LLM API      | OpenAI (GPT-3.5/4)|
| Version Ctrl | Git + GitHub      |

---

## 🖼️ Architecture Diagram

![Mini LLM App Flow](assets/mini-llm-flow.png)

> **Flow:**
1. User types a message in Streamlit UI  
2. Message is sent to `OpenAI API`  
3. LLM processes and returns response  
4. Streamlit updates chat window  

---

## ⚙️ Local Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/mini-llm-app.git
cd mini-llm-app

