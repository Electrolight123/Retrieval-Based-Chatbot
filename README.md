# Retrieval-Based Chatbot

This repository contains a simple retrieval-based chatbot implemented in Python. The chatbot leverages Natural Language Processing (NLP) techniques to provide responses to user inputs by identifying the most relevant sentence from a pre-defined corpus of text. Key features include:

- **Text Preprocessing:** The text corpus is preprocessed by tokenizing sentences and words, converting to lowercase, and lemmatizing.
- **Greeting Responses:** The bot can recognize and respond to common greetings.
- **TF-IDF Vectorization:** The chatbot uses TF-IDF (Term Frequency-Inverse Document Frequency) to convert the text data into numerical representations.
- **Cosine Similarity:** It employs cosine similarity to find the closest match to the user's input from the corpus and generate appropriate responses.
- **Interactive Conversation:** Users can interact with the bot, which will respond based on the processed text data.

## Setup and Usage

### Prerequisites

- Python 3.x
- nltk
- scikit-learn
- numpy

### Installation

1. Clone the repository:
git clone https://github.com/Electrolight123/Retrieval-Based-Chatbot.git
cd Retrieval-Based-Chatbot

2. Install the required packages:
pip install -r requirements.txt

### Usage
1. Prepare your text corpus and save it as data.txt in the repository directory.

2. Run the chatbot:
python chatbot.py

3. Start interacting with the bot by typing your inputs. To end the conversation, type 'bye'.

### Contributing

Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes.

### License
This project is licensed under the MIT License.
