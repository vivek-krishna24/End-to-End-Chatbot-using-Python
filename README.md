Chatbot using Python, Streamlit, and Machine Learning
📘 **Project Overview**

This is a simple rule-based + ML-powered chatbot built using Python.
It uses TF-IDF Vectorization and Logistic Regression from scikit-learn to classify user input into predefined intents and provide relevant responses.
The app runs on Streamlit, providing a clean, interactive chat interface.
**
🧰 Tools and Libraries Used**
Library	Purpose
**os**	Manage system paths for NLTK data.
**nltk	**Tokenization and text preprocessing.
**ssl**	Allows secure downloads of NLTK packages.
**streamlit**	Creates an interactive web interface for the chatbot.
**random**	Randomly selects chatbot responses for variety.
**scikit-learn**	Machine learning (TF-IDF for text features, Logistic Regression for intent classification).
**⚙️ How It Works**

**Define Intents:**
Each intent has a tag, patterns (possible user inputs), and responses (possible replies).

**Text Vectorization:**
The TfidfVectorizer converts user input and training text into numerical form.
**
Model Training:**
A LogisticRegression model is trained to classify the text into one of the predefined intent tags.

**Response Generation:**
Based on the predicted tag, the chatbot returns a random response from that intent’s list.

**Streamlit Interface:**
Users can interact with the chatbot in a web browser through a simple chat UI.# End-to-End-Chatbot-using-Python
