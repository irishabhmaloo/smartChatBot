# Chatbot Project

This project implements a simple chatbot using Python, TensorFlow, and NLTK.

## Features

- Train the chatbot with a set of predefined intents.
- Interact with the chatbot in a conversation.

## Usage

### Training the Model

1. Install dependencies:

    ```bash
    !pip install tflearn nltk
    ```

2. Run the training notebook:

    - Open `train_chatbot.ipynb` and execute the cells.

3. The model will be saved as `model.tflearn`, and training data will be stored in `training_data`.

### Running the Chatbot

1. Run the chatbot notebook:

    - Open `run_chatbot.ipynb` and execute the cells.

2. Interact with the chatbot by entering your messages.

    - To stop the chatbot, type `exit`.

## File Structure

- `train_chatbot.ipynb`: Notebook for training the chatbot model.
- `run_chatbot.ipynb`: Notebook for interacting with the trained chatbot.
- `intents.json`: File containing intents and responses for training.
- `model.tflearn`: Saved model file.
- `training_data`: Pickle file containing training data.

## Requirements

- Python 3.x
- TensorFlow
- NLTK


Feel free to contribute, report issues, or provide feedback!
