# 🤖 Task 4 – General Health Query Chatbot (Prompt Engineering Based)

---

## 🎯 Objective

Create a chatbot that can answer general health-related questions using a Large Language Model (LLM) with prompt engineering and safety filters.

---

## 🛠️ Tools & Libraries

- Python 3  
- OpenAI GPT-3.5 API *(or)*  
- Hugging Face Transformers (e.g., Mistral-7B-Instruct)  
- requests (for API calls)

---

## 📂 Project Details

- **Model:** OpenAI GPT-3.5 (or open-source LLM like Mistral-7B-Instruct)
- **Interface:** Simple Python script or Jupyter Notebook
- **Prompt Engineering:** Custom system prompt to act as a helpful, safe medical assistant
- **Safety:** Filters to avoid harmful or unsafe medical advice

---

## ⚙️ Workflow Steps

- **User Input:** Accept health-related queries from the user  
- **Prompt Engineering:** Add a system prompt (e.g., "Act like a helpful medical assistant. Do not give dangerous or prescription advice.")  
- **LLM API Call:** Send the prompt and user query to the LLM via API  
- **Safety Filter:** Check and filter responses for unsafe or inappropriate advice  
- **Response:** Display the friendly, safe answer to the user

---

## 💬 Example Queries

- "What causes a sore throat?"
- "Is paracetamol safe for children?"
- "How can I improve my sleep quality?"

---

## 📁 Files Included

- `Task4_Health_Chatbot.ipynb` — Jupyter Notebook or Python script with code  
- `README.md` — This file

---

> ✅ *This task demonstrates prompt engineering, LLM API usage, and safety handling in conversational AI.*
