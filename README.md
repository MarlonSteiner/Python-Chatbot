Python Chatbot - ChatGPT Prompt Engineering

Overview

This is a Python-based chatbot developed as part of the ChatGPT Prompt Engineering for Developers exercise. The chatbot leverages OpenAI's GPT model to generate intelligent and context-aware responses, demonstrating effective prompt engineering techniques.

Features

Utilizes OpenAI's GPT API for generating responses

Implements structured and optimized prompts

Interactive command-line interface

Customizable conversation flow

Installation

Prerequisites

Ensure you have the following installed:

Python 3.7+

OpenAI API key

Setup

Clone this repository:

git clone https://github.com/yourusername/python-chatbot.git
cd python-chatbot

Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install dependencies:

pip install -r requirements.txt

Set up your OpenAI API key:

export OPENAI_API_KEY='your-api-key-here'  # On Windows use `set`

Usage

Run the chatbot with:

python chatbot.py

Then, enter messages to interact with the AI.

Configuration

You can modify the chatbot behavior by editing chatbot.py, adjusting the system prompt, or tweaking model parameters such as temperature and max_tokens.

Example Interaction

User: Hello!
Bot: Hi there! How can I assist you today?
User: Tell me a joke.
Bot: Why don’t skeletons fight each other? Because they don’t have the guts!

Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

License

This project is licensed under the MIT License.

Acknowledgments

ChatGPT Prompt Engineering for Developers Course

OpenAI for providing the API

