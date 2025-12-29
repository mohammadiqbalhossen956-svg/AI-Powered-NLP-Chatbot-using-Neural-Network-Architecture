# Intelligent NLP Chatbot using Neural Networks (MLP)

## Project Overview
This project is a functional, English-speaking AI chatbot developed within the **Pydroid 3** mobile environment. It utilizes a **Multi-layer Perceptron (MLP)** neural network to understand user queries and provide contextually relevant responses.

## Key Technical Contributions
* **Neural Architecture:** Implemented an **MLP Classifier** with multiple hidden layers (16, 8) to recognize intent and map user questions to learned answers.
* **Text Embedding (TF-IDF):** Leveraged **Term Frequency-Inverse Document Frequency (TF-IDF)** vectorization to convert human language into weighted numerical feature vectors.
* **Confidence Thresholding:** Integrated a logic-based probability check to ensure the bot only responds when it is mathematically confident (Threshold > 0.3) in its prediction.
* **Optimized for Mobile:** Engineered the solution using **Scikit-Learn** as a high-performance, free alternative to heavy neural network frameworks.

## Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-Learn
* **Data Processing:** Pandas & NumPy
* **Environment:** Pydroid 3 (Mobile Development)

## Live Demo Output
```text
Bot: Hello! Start chatting with me (Type 'Goodbye' to exit)
You: Hi
Bot: Hello! I am your AI chatbot.
You: What can you do?
Bot: I can answer your questions based on my training.
