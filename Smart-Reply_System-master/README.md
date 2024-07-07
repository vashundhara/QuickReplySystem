# SRS with Python.
Smart Reply is a predictive text feature, which currently works in apps like Allo, Gmail, Inbox and from now on, Android Messages too. Functionality gives you the ability to answer messages by selecting pre-written responses based on machine learning and AI. The Smart reply system is based upon the responses being fed in intents.json file. It is a dataset used in the project. This system is focused to answer the medical and drug related queries.

•	Intents.json – The data file which has predefined patterns and responses.


•	train_chatbot.py – In this Python file, we wrote a script to build the model and train our system.


•	Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.


•	Classes.pkl – The classes pickle file contains the list of categories.


•	Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.


•	Chatgui.py – This is the Python script in which we implemented GUI for our system. Users can easily interact with the system.

