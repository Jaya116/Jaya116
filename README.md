LearnProg Chatbot

Welcome to the LearnProg Chatbot project! This chatbot is designed to answer common questions and provide assistance related to programming and learning resources.

Project Structure

The project directory is structured as follows: LearnProg_Chatbot/

├── intents.json

├── chat_model/

│ └── # Keep this folder empty to store the chatbot model files

├── label_encoder/

│ └── label_encoder.pickle

├── tokenizer/

│ └── tokenizer.pickle

├── static/

│ └── style.css

│ └──script.js

├── templates/

│ └── index.html

├── app.py

├── simple_chatbot.py

├── train_chatbot.py

├── chatbot-env/ # Create a virtual environment

├──_pycache_

└── README.md

chat_model/: Store the chatbot model files (folder is empty).
label_encoder/: Label encoder files.
tokenizer/: Tokenizer files.
static/: Contains CSS file for styling the chat interface.
script.js/: Contains JavaScript file for adding interactive features
templates/: Includes HTML template for the chat interface.
app.py: The Flask application for web interaction.
simple_chatbot.py: Script to interact with the trained chatbot model.
train_chatbot.py: Script to train the chatbot model.
chatbot-env/: Create a virtual environment for the project.
README.md: The file you're currently reading.
Running the Chatbot To run the chatbot, you need to follow these steps:

Environment Setup: • Navigate to the project directory. • Create a virtual environment (if not already created) and activate it: python -m venv LearnProg Chatbot venv\Scripts\activate
• Install the required packages:

pip install tensorflow 
pip install scikit-learn 
pip install Flask 
pip install numpy 
pip install flask_cors
Train the Chatbot: • Run the train_chatbot.py script to train the chatbot model:

python train_chatbot.py

• The script will process the dataset and save the trained model, tokenizer, and label encoder.

Run the Web Application: • Start the Flask web application by running app.py:

python app.py

• The chatbot web interface will be accessible at http://127.0.0.1:5000 in your web browser.

Interact with the Chatbot: • Open the chat interface in your web browser. • Ask questions and interact with the chatbot.
Feel free to explore the code and make any necessary modifications or improvements.

Dataset Source

The dataset used in this project is stored in the intents.json file within the data directory. The dataset includes various intents and responses relevant to programming and learning. The data structure is designed to train the chatbot in understanding user queries and providing informative answers. Let's take a peek at our dataset: Source: Our dataset is meticulously crafted to provide programming-related knowledge. Description: It's packed with questions, answers, and helpful information on various programming topics. Preprocessing: The dataset is preprocessed to ensure the chatbot understands and responds effectively.

Enjoy chatting and learning with the LearnProg Chatbot!

