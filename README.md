# Rule-Based-ChatBot
Chatbots are computer programs that simulate conversation with humans. They’re used in a variety of applications, from providing customer service to answering questions on a website.
# Building Rule-Based Chatbot Using Python NLTK Library
NLTK stands for Natural language toolkit used to deal with NLP applications and chatbot is one among them. Now we will advance our Rule-based chatbots using the NLTK library. Please install the NLTK library first before working using the pip command.

pip instal nltk

The first thing is to import the necessary library and classes we need to use.

import nltk
from nltk.chat.util import Chat, reflections

Chat – Chat is a class that contains complete logic for processing the text data that the chatbot receives and finding useful information out of it.

reflections – Another import we have done is reflections which is a dictionary containing basic input and corresponding outputs. You can also create your own dictionary with more responses you want. if you print reflections it will be something like this.

reflections = {

  "i am"       : "you are",
  
  "i was"      : "you were",
  
  "i"          : "you",
  
  "i'm"        : "you are",
  
  "i'd"        : "you would",
  
  "i've"       : "you have",
  
  "i'll"       : "you will",
  
  "my"         : "your",
  
  "you are"    : "I am",
  
  "you were"   : "I was",
  
  "you've"     : "I have",
  
  "you'll"     : "I will",
  
  "your"       : "my",
  
  "yours"      : "mine",
  
  "you"        : "me",
  
  "me"         : "you"
  
}

let’s start building logic for the NLTK chatbot.

After importing the libraries, First, we have to create rules.
After creating pairs of rules, we will define a function to initiate the chat process. The function is very simple which first greets the user and asks for any help. The conversation starts from here by calling a Chat class and passing pairs and reflections to it.

An amazing Rule-based chatbot is created just by using Python and NLTK library. The bot works on various regex patterns present in user Intent and corresponding to it, presents the output to a user.
