# 🤖 Chatbot with Flask and JavaScript

## 📚 Project Overview

This project features a chatbot application developed using Flask and PyTorch. The chatbot is designed to interact with users by understanding their intents and generating appropriate responses.

## 🌟 Features

- **Intent Recognition**: Utilizes a neural network to understand user messages and identify intents.
- **Customizable Responses**: Easily modify the `intents.json` file to update chatbot responses based on different intents.
- **Training and Testing**: Includes scripts to train the model with your dataset and test it in the console.
- **User Interface**: Provides a web-based UI for seamless interaction with the chatbot.

## 🛠️ Project Structure

- **`intents.json`**: Configuration file where you define intents and their responses.
- **`train.py`**: Script to train the chatbot model.
- **`chat.py`**: Script to interact with the chatbot in the console.
- **`Source/`**: Contains model definition and utility functions for tokenization and data processing.
- **`static/`**: Directory for static files such as CSS and JavaScript.
- **`templates/`**: Directory for HTML files that define the web-based UI for the chatbot.

## 📈 How It Works

1. **Training**: The `train.py` script processes data from `intents.json`, trains the model, and saves it to a file (`data.pth`).
2. **Interaction**: 
   - **Console Interaction**: The `chat.py` script loads the trained model and allows you to chat with the bot by typing messages in the console.
   - **Web Interaction**: Use the provided web UI to interact with the chatbot through a web browser.
   - 
## 🖼️ Output

Below is a screenshot of the chatbot's output:

![Chatbot Screenshot](Screenshots/demo.png)
