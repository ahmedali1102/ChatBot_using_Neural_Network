# Overview
This project implements a chatbot that leverages neural networks for intent classification. The chatbot is trained to recognize various patterns in user input and respond appropriately based on predefined intents. The model is built using TensorFlow and tflearn and is trained on a dataset (intents.json) containing sample queries and responses.

# Features
Pattern Recognition: The chatbot can understand and classify user input into different categories (intents) such as greetings, goodbyes, and queries about hours of operation, menu items, and more.
Natural Language Processing: The chatbot uses NLP techniques like tokenization and stemming to process the input text.
Neural Network Model: A neural network is trained to classify input sentences into appropriate intents.
Extensible: The chatbot's capabilities can be easily extended by updating the intents.json file.
# Project Structure
intents.json: Contains the dataset with intents, patterns, and responses.
ChatBot_using_Neural_Network.ipynb: The Jupyter notebook that contains the code for loading the data, preprocessing, and building the neural network model.
Model Training: The notebook includes sections for data preprocessing, neural network training, and evaluation.
Dependencies: Key libraries include nltk, tensorflow, tflearn, and numpy.

Install the required dependencies:

pip install nltk tensorflow tflearn numpy
Load the notebook (ChatBot_using_Neural_Network.ipynb) and execute the cells in order.

Modify the intents.json file to add new intents or update existing ones.

Train the model by running the training cells, and test the chatbot interactively.

# Future Work
Add more intents to improve chatbot capabilities.
Implement additional NLP techniques for improved accuracy.
Integrate with a web-based or messaging interface for live deployment.
