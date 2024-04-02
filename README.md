# AAAVI-chatbot-
AAAVI (Artificial Assistant Available Virtually) is an AI-powered chatbot built using TensorFlow and NLTK. It offers personalized interactions based on user input, trained on a dataset of intents. Users can engage with AAAVI for assistance across various topics, making it a versatile virtual assistant.

## Overview

This project implements a simple chatbot using TensorFlow and NLTK (Natural Language Toolkit). The chatbot is trained on a dataset of intents stored in a JSON file, where each intent contains patterns of user input and corresponding responses. The chatbot uses a neural network model built with TensorFlow to classify user input and generate appropriate responses.

## Files

1. **aaavi.py**: This file contains the main code for the chatbot. It loads the intents dataset, preprocesses the data, builds and trains the neural network model using TensorFlow, and defines functions for user interaction.

2. **intents.json**: JSON file containing the dataset of intents. Each intent consists of patterns and corresponding responses for the chatbot.

3. **data.pickle**: Serialized data file containing processed words, labels, training data, and output for the chatbot model.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/Ananyaearth/AAAVI-chatbot-.git
    ```

2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. **Train the Chatbot Model**: Run the `aaavi.py` script to train the chatbot model:

    ```
    python aaavi.py
    ```

2. **Interact with the Chatbot**: After training, the chatbot will be ready to interact with users. Start talking with the bot by typing your messages and pressing Enter. Type "quit" to stop the conversation.

## Dataset

The chatbot is trained on a dataset of intents stored in `intents.json`. This file contains a collection of intents, each consisting of patterns and responses. Update this file to customize the chatbot's behavior and add new intents.

## Dependencies

- TensorFlow
- NLTK

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
