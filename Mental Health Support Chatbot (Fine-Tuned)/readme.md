Mental Health Support Chatbot 🤗
A basic chatbot that provides supportive and empathetic responses for stress, anxiety, and emotional wellness.
Fine-tuned on real human dialogues using the EmpatheticDialogues dataset.

Features
Fine-tuned DistilGPT2 for empathetic conversation
Handles stress, anxiety, and emotional wellness topics
Simple Streamlit web interface for chatting
Easy to run locally
Dataset
Source: EmpatheticDialogues (Facebook AI)
Custom CSV: You can use your own CSV with columns for user message and empathetic response.
How It Works
Preprocesses the dataset to create prompt-response pairs.
Tokenizes the data for the model.
Fine-tunes DistilGPT2 using Hugging Face Trainer API.
Saves the trained model and tokenizer.
Runs a Streamlit app for chatting with the bot.
Setup & Installation
Clone the repository.
Install dependencies (transformers, datasets, torch, streamlit).
(Optional) Download or prepare your dataset.
Training the Model
Edit and run the training script.
Make sure your CSV is in the correct path.
Update column names if needed.
Running the Chatbot
Make sure your trained model is saved in empathetic_gpt2 folder.
Run the Streamlit app.
Chat with your empathetic bot in the browser!
Example Conversation
You: I'm feeling really stressed about my exams.
Bot: That sounds tough. It's normal to feel stressed, but remember to take breaks and take care of yourself. You're doing your best!

Project Structure
app.py
train.py
empathetic_gpt2/ (Saved model and tokenizer)
your_dataset.csv
requirements.txt
README.md
License
This project is for educational purposes.

Credits
EmpatheticDialogues Dataset (Facebook AI)
Hugging Face Transformers
Streamlit
