# 🤖 Rule-Based Interactive Chatbot

## 📝 Overview
A lightweight, interactive rule-based command-line chatbot built in Python. This program evaluates user inputs in real-time, matching specific keywords and control flows to provide pre-defined conversational responses, greetings, identity declarations, and capabilities explanations.

## 🎯 Features & Core Functionality
* **Interactive Command Loop:** Continuously listens for user input inside a persistent `while` loop until an exit command is triggered.
* **Rule-Based Intent Matching:** Uses conditional logic (`if`, `elif`, `else`) to categorize text inputs into specific intent branches.
* **Graceful Exit Handling:** Recognizes multiple termination keywords (`exit`, `bye`, `quit`, `goodbye`) to politely close the session.
* **Fallback Mechanism:** Handles unrecognized inputs gracefully by providing a default fallback message prompting the user with valid commands.

## 🛠️ Tech Stack & Requirements
* **Language:** Python 3.x
* **Dependencies:** None (uses built-in Python standard functions like `input()` and `print()`).

