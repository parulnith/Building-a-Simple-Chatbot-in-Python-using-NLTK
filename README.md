# Building a Simple Chatbot from Scratch in Python (using NLTK)

![Alt text](https://cdn-images-1.medium.com/max/800/1*pPcVfZ7i-gLMabUol3zezA.gif)

History of chatbots dates back to 1966 when a computer program called ELIZA was invented by Weizenbaum. It imitated the language of a psychotherapist from only 200 lines of code. You can still converse with it here: [Eliza](http://psych.fullerton.edu/mbirnbaum/psych101/Eliza.htm?utm_source=ubisend.com&utm_medium=blog-link&utm_campaign=ubisend). 

On similar lines let's create a very basic chatbot utlising the Python's NLTK library.It's a very simple bot with hardly any cognitive skills,but still a good way to get into NLP and get to know about chatbots.

 the accompanying blog titled:**[Building a Simple Chatbot in Python (using NLTK]**(https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e)

# Outline
* Motivation
* Blogpost
* Pre-requisites
* How to run


## Motivation
The idea of this project was not to create some SOTA chatbot with exceptional cognitive skills but just to utilise and test my Python skills.This was one of my very first projects, created  when I just stepped into the world of NLP and I thought of creating a simple chatbot just to make use of my newly acquired knowledge.

## BlogPost
For detailed overview, here is the accompanying blog titled:**[Building a Simple Chatbot in Python (using NLTK](https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e)**


## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```

## How to run
* You can run the [chatbot.ipynb](https://github.com/parulnith/Building-a-Simple-Chatbot-in-Python-using-NLTK/blob/master/Chatbot.ipynb) which also includes step by step instructions.


