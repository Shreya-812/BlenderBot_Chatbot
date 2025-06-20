# BlenderBot_Chatbot
# Local Chatbot with Memory using BlenderBot

This project demonstrates a lightweight AI chatbot with short-term memory, built using Hugging Face Transformers. It uses Facebook's `blenderbot-400M-distill` model and is designed to run efficiently in Google Colab or any Python environment.

## Overview

The chatbot:
- Responds to user input in natural language
- Maintains a memory of the last 5 exchanges
- Uses a pre-trained dialogue model optimized for general conversations
- Runs in a terminal-like interface in Jupyter/Colab

## Model Used

**facebook/blenderbot-400M-distill**
- Pre-trained on large conversational datasets
- Suitable for open-domain dialogue
- Small enough to run in free-tier Colab sessions without crashing

## Files

| File | Description |
|------|-------------|
| `Chatbot_Demo_Colab.ipynb` | Colab/Jupyter-compatible notebook for demo |
| `README.md` | Project overview and instructions |

## Setup Instructions (for Google Colab)

1. Open `Chatbot_Demo_Colab.ipynb` in Google Colab.
2. Run all cells in order.
3. Use the last cell to interact with the chatbot.
4. Type `/exit` to quit the session.

Dependencies (installed automatically in Colab):
- `transformers`
- `torch`

## Sample Interaction

User: Hello
Bot: Hello! How are you today?

User: Can you tell me a joke?
Bot: Why don't scientists trust atoms? Because they make up everything.

User: /exit
Goodbye!

## Features

- Memory of the last 5 turns, improving coherence
- Pre-trained transformer-based chatbot
- Runs entirely in Python, no special deployment needed

## Demo Guidelines

- Start by showing model loading
- Ask 3–4 diverse questions (factual, creative, follow-up)
- Highlight memory working across turns
- End with `/exit`

## Notes

For heavier models like `blenderbot-3B`, use a local GPU or Colab Pro. This version is optimized for lightweight demo purposes.

