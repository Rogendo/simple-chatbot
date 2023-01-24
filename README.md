# simple-chatbot

This chatbot uses the Chat class from the nltk.chat.util module. It takes in a list of pairs,
where each pair consists of a regular expression pattern to match user input and a list of responses. 
The reflections dictionary is used to handle basic user input like "I am" or "I'm".

When the chatbot is run, it will continuously prompt the user for input and match it against the patterns 
in the pairs list.
When a match is found, the chatbot will respond with one of the responses in the corresponding list. 
The chatbot will continue until the user inputs "quit" or the conversation is ended by the user.
