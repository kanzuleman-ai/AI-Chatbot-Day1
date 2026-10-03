# 🤖 AI Chatbot

A conversational AI chatbot built with **Python and Google's Gemini API**, developed progressively through Day 1, Day 2, and Day 3 of my AI internship.

The project demonstrates practical implementation of **AI API integration, prompt engineering, conversation context, error handling, input validation, and interactive UI development**.

---

## 📌 Project Overview

The chatbot started as a basic API-based conversational application and was progressively upgraded to make it more structured, reliable, and user-friendly.

### Development Progress

**Day 1:** Basic chatbot and Gemini API integration
**Day 2:** System prompt, validation, loading state, error handling, and interactive UI
**Day 3:** Improved context handling, Clear Chat, structured prompts, Markdown responses, and better interaction

---

## 🚀 Day 1 — Basic AI Chatbot

The first version focused on building the core conversational functionality.

### Implemented

* User message input
* Gemini API integration
* AI-generated responses
* Conversation history
* Context-aware replies
* Continuous conversation
* Basic chatbot interface

---

## ⚙️ Day 2 — Chatbot Upgrade

The chatbot was upgraded to improve reliability and user experience.

### Improvements

* Added a defined **system prompt** for the AI's role and personality
* Added **loading feedback** while generating responses
* Added **error handling** for API and response issues
* Added **input validation** for empty messages
* Added an interactive interface using `ipywidgets`
* Continued secure API key management through **Google Colab Secrets**

---

## 🚀 Day 3 — Further Improvements

The chatbot was further improved with better conversation management and interaction.

### Improvements

* Improved **conversation history and context handling**
* Added **Clear Chat** functionality
* Added structured **prompt building**
* Added **Markdown response formatting**
* Improved response and error handling
* Improved the overall chatbot interface

---

## ✨ Final Features

* AI-powered conversational responses
* Defined AI personality and system prompt
* Conversation history and context
* Structured prompt construction
* Loading state
* Input validation
* Error handling
* Markdown responses
* Clear Chat functionality
* Interactive chatbot interface
* Secure API key handling

---

## 🛠️ Technologies Used

* **Python**
* **Google Gemini API**
* **Google GenAI Python SDK**
* **Google Colab**
* **ipywidgets**
* **Markdown**

### AI Model

**Gemini 3.6 Flash**

---

## 🏗️ Architecture

```text
User Input
    ↓
Input Validation
    ↓
Prompt Builder
    ↓
System Prompt + Conversation History + Current Message
    ↓
Gemini API
    ↓
Response / Error Handling
    ↓
Markdown Output
    ↓
Conversation History
```

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**.
2. Add your Gemini API key to **Colab Secrets** using the name `GEMINI_API_KEY`.
3. Run the Gemini connection cell.
4. Run the final chatbot implementation.
5. Enter a message and click **Send**.
6. Use **Clear Chat** to start a new conversation.

> The API key is accessed through Colab Secrets and is not hardcoded in the notebook.

---

## 🎥 Demo

The chatbot can be run directly through the Google Colab notebook.

**Notebook:** [Open AI Chatbot Notebook](https://colab.research.google.com/drive/18PVOt6CbgraAs0Xaa0MJj8L30SavdGqh?usp=sharing)

---

## 🧪 Testing

The final chatbot was tested for:

* Normal AI responses
* Follow-up questions using conversation context
* Empty input validation
* Clear Chat functionality
* Markdown-formatted responses
* API response and error handling

---

## 📸 Screenshots

### Main Chatbot

<img width="1356" height="624" alt="Main Chatbot Interface" src="https://github.com/user-attachments/assets/891dff41-7e68-4cbe-aff5-a02a4ca4df00" />

### Conversation Context

<img width="1356" height="624" alt="Conversation Context" src="https://github.com/user-attachments/assets/4bab1c27-9a1f-45a2-85e3-519c7d4b6832" />

<img width="1366" height="608" alt="Follow-up Conversation" src="https://github.com/user-attachments/assets/ddb51834-1e8a-4e9d-ab98-6ec1c49e8af6" />

### Input Validation

<img width="1252" height="122" alt="Input Validation" src="https://github.com/user-attachments/assets/ba66d8d2-feae-44e3-b298-86eb42472f3e" />

### Clear Chat

<img width="1366" height="622" alt="Clear Chat" src="https://github.com/user-attachments/assets/7e54fd24-33db-49d1-a3e3-6b0207dcf8ff" />

---

## 📚 What I Learned

* Integrating AI APIs with Python
* Secure API key management
* Writing system prompts and structured prompts
* Managing conversation context
* Handling API errors and invalid input
* Building an interactive AI interface
* Testing and improving an AI application
* Documenting a project using GitHub

---

## 🧩 Problems & Solutions

### API Availability Issue

A temporary Gemini API service error occurred during development.

**Solution:** The API connection was tested again successfully once the service became available.

### API Key Security

Hardcoding an API key could expose sensitive credentials.

**Solution:** The API key was stored securely using Google Colab Secrets.

### Conversation Context

Follow-up questions require access to relevant previous messages.

**Solution:** Conversation history was structured and included when building the prompt.

---

## 🎯 Project Outcome

The chatbot evolved from a basic Gemini API implementation into a more structured and interactive conversational AI application through three development stages.

This project provided hands-on experience with **AI API integration, prompt engineering, conversational context, error handling, input validation, and interactive AI application development**.

---

## 👩‍💻 Internship Project

Developed as part of my **AI Internship** to gain practical experience in building, testing, improving, and documenting AI-powered applications.
