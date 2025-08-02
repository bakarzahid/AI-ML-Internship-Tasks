Task 5 – Mental Health Support Chatbot (Fine-Tuned)
🎯 Objective
Build a basic chatbot that provides supportive and empathetic responses for stress, anxiety, and emotional wellness using a fine-tuned language model.

🛠️ Tools & Libraries
Python 3
Hugging Face Transformers
Datasets
PyTorch
Streamlit
📂 Dataset Details
Name: EmpatheticDialogues
Source: Facebook AI / Custom CSV
Columns Used:
Situation (user message)
empathetic_dialogues (empathetic response)
🧠 Model & Approach
Base Model: DistilGPT2 (can use GPT-Neo or Mistral 7B as well)
Fine-tuning: Hugging Face Trainer API
Input Format:
User: <Situation>\nBot: <empathetic_dialogues>
Labels: Same as input (causal language modeling)
💻 How to Run
Install dependencies:

transformers, datasets, torch, streamlit
Train the model:

Preprocess and tokenize your data
Fine-tune DistilGPT2 for 1+ epochs
Save the model in empathetic_gpt2 folder
Run the chatbot app:

Use streamlit run app.py
Chat with your empathetic bot in the browser
🗂️ Files Included
app.py — Streamlit chatbot interface
train.py — Model training script
empathetic_gpt2/ — Saved model and tokenizer
emotion-emotion_69k.csv — Custom dataset
README.md — This file
💬 Example Conversation
You: I'm feeling really anxious these days.
Bot: I'm sorry you're feeling this way. Remember, it's okay to take things one step at a time. You're not alone.

📈 Key Points
Fine-tuned on real empathetic dialogues
Gentle, supportive, and safe responses
Simple web interface for easy testing
✅ This project demonstrates how to fine-tune a small language model for emotionally supportive chatbots using real human conversations.

