# 🤖 Rule-Based AI Chatbot

A simple Rule-Based AI Chatbot built using Python as part of the DecodeLabs Artificial Intelligence Internship.

---

## 📌 Project Overview

This chatbot demonstrates how Artificial Intelligence can be implemented using simple control flow and dictionary-based intent matching.

Instead of Machine Learning, the chatbot uses predefined rules to generate responses.

The project follows the IPO (Input → Process → Output) model.

---

## 🚀 Features

- Greeting detection
- About chatbot information
- DecodeLabs information
- AI related questions
- Dynamic current time response
- Help command
- Joke command
- Exit commands
- Dictionary based O(1) lookup
- Input sanitization

---

## 🛠 Technologies Used

- Python 3
- Dictionary (Hash Map)
- Control Flow
- Functions
- While Loop

---

## 📂 Project Structure

```
Rule-Based-AI-Chatbot/
│
├── main.py
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
└── screenshots/
```

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/Rule-Based-AI-Chatbot.git
```

Move into the project

```bash
cd Rule-Based-AI-Chatbot
```

Run the chatbot

```bash
python main.py
```

---

## 💬 Example

```
You: hello

Bot: Hello! 👋 Welcome to DecodeLabs AI Assistant.
How can I help you today?
```

```
You: what is ai

Bot: AI stands for Artificial Intelligence...
```

```
You: help
```

Displays all available commands.

---

## 🧠 IPO Model

### Input

User enters text.

↓

### Process

- Convert input to lowercase
- Remove extra spaces
- Match dictionary key
- Generate response

↓

### Output

Display chatbot response.

---

## 📖 Supported Commands

- hello
- hi
- hey
- who are you
- what is AI
- what is rule based AI
- what is machine learning
- what is a chatbot
- help
- joke
- tell me a joke
- what is the time
- thanks
- bye
- exit
- quit

---

## 📷 Screenshots

Add screenshots inside the `screenshots` folder.

Example:

- Chatbot Start
- Help Menu
- Exit Screen

---

## 📈 Future Improvements

- NLP support
- Synonym matching
- Voice input
- GUI using Tkinter
- Database support
- Machine Learning integration

---

## 👨‍💻 Author

Vinit Kumar

DecodeLabs AI Internship

2026
