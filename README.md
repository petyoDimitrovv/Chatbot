# Chatbot - AI-powered Conversational Bot

## Overview

This project is a simple AI chatbot using a neural network trained with PyTorch. It processes user inputs and responds based on predefined intents. The chatbot is designed for learning and experimentation with Natural Language Processing (NLP) and deep learning models.

## Features

- Trained using PyTorch with a feedforward neural network
- Tokenization and bag-of-words model for text processing
- Predefined intents and responses stored in a JSON file
- Interactive console-based chat interface

## Technologies Used

- Python 3
- PyTorch
- NLTK (Natural Language Toolkit)
- JSON for data storage

## Installation

### Prerequisites

Ensure you have Python installed (preferably version 3.8 or higher) and install the required dependencies:

```sh
pip install torch nltk
```

## How to Run

1. Train the chatbot model (if not trained already):

```sh
python trainDemo.py
```

2. Start chatting with the bot:

```sh
python chat.py
```

## Project Structure

```
Chatbot-master/
│── chat.py              # Chat interface
│── model.py             # Neural network model
│── trainDemo.py         # Training script
│── nltk_utils.py        # Helper functions for NLP
│── intents.json         # Predefined intents and responses
│── data.pth             # Trained model weights
```

## Future Improvements

- Implement a web-based or GUI interface
- Add more diverse training data
- Improve response accuracy with advanced NLP techniques

## Author

PetyoDimitrov - [[GitHub Profile](https://github.com/petyoDimitrovv)]

## License

This project is licensed under the MIT License - see the LICENSE file for details.



