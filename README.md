# Pybot- A Chatbot for answering Python queries.
Pybot will give you answer's regarding any of your python related doubts/question's with the help of both text reply as well as text-to-speech medium .
This is retrieval based chatbot.
The GUI is created using tkinter with multiple themes & fonts to play around.

# What is a Chatbot?
Chatbot is a computer program that stimulates and processes human conversation (either written or spoken), allowing humans to interact with digital devices as if they were communicating with a real person. They are also known as digital assistants that understand human capabilities. Bots interpret and process the user requests and give prompt relevant answers. 

# How do Chatbots work?
There are broadly two variants of chatbots: Rule-Based and Self-learning.
In a Rule-based approach, a bot answers questions based on some rules on which it is trained on. The rules defined can be very simple to very complex. The bots can handle simple queries but fail to manage complex ones.
Self-learning bots are the ones that use some Machine Learning-based approaches and are definitely more efficient than rule-based bots. These bots can be of further two types: Retrieval Based or Generative.
i) In retrieval-based models, a chatbot uses some heuristic to select a response from a library of predefined responses. The chatbot uses the message and context of the conversation for selecting the best response from a predefined list of bot messages. The context can include a current position in the dialogue tree, all previous messages in the conversation, previously saved variables (e.g. username). Heuristics for selecting a response can be engineered in many different ways, from rule-based if-else conditional logic to machine learning classifiers.
ii) Generative bots can generate the answers and not always replies with one of the answers from a set of answers. This makes them more intelligent as they take word by word from the query and generates the answers.

# Requirements-
python 3.6+
tkinter
pyttsx3
threading
nltk
numpy
