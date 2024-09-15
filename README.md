# Negotiation Chatbot

This project contains a chatbot that simulates a negotiation process between a customer and a supplier. The chatbot uses OpenAI's GPT-3 model to handle conversations and propose counteroffers.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/negotiation-chatbot.git
    ```

2. Install required libraries:
    ```bash
    pip install openai
    ```

3. Securely set up your OpenAI API key:
    ```python
    from google.colab import userdata
    OPENAI_API_KEY = userdata.get('OPENAI_API_KEY')
    ```

4. Run the chatbot:
    ```python
    from chatbot import negotiate_with_user
    negotiate_with_user()
    ```

## How It Works

The chatbot initiates a negotiation process where users can make offers, and the chatbot will respond based on predefined pricing logic. The conversation and responses are handled using the OpenAI GPT-3 model.

## Demo

Watch the following video to see the chatbot in action:

[![Watch the demo]](https://youtu.be/8zvX0HDnsgY)
