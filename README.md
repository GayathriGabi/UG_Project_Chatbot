# UG_Project_Chatbot
History of chatbots dates back to 1966 when a computer program called ELIZA was invented by Weizenbaum. It imitated the language of a psychotherapist from only 200 lines of code. You can still converse with it here: Eliza.
On similar lines let's create a very basic chatbot utlising the Python's NLTK library.It's a very simple bot with hardly any cognitive skills,but still a good way to get into NLP and get to know about chatbots.

# ABSTRACT
The development of chatbot has become trendier and so far several conversational chatbots were designed which replaces the traditional chatbots. A chatbot is a computer program which is used to interact with humans and fulfill their needs. Chatbot gives the response for the user query and sometimes they are capable of executing tasks also. Early development of chatbots became so difficult whereas recent chatbots development is much easier because of the wide availability of development platforms and source code. A chatbot can be developed using either Natural Language Processing (NLP) or Deep Learning. When compared to traditional chatbots, bots designed using Deep Learning requires huge amount of data to train. A chatbot is a service, powered by rules and sometimes artificial intelligence, that you interact with via a chat interface. A chatbot can be deployed on various platforms such as mobile apps, web apps, messaging apps, personal assistant and what not. It’s job to provide human like interaction and assistance to the user. The best chatbot in the world would be one in which the user would be one in which the user would not be able to differentiate it from an actual human being. Natural Language Processing is an area of research and application that explores how computer can be used to understand and manipulate.
# MODULES
# Preprocessing:
In this pre-processing, we first load the metadata into this and then this metadata will be attached to the data and replace the converted data with metadata. Then this data will be moved further and remove the unwanted data in the list and it will divide the data into the train and the test data. White space tokenization: Non white space sequences are identified by
tokens
# Simple tokenization:
A character class tokenizer,sequences of same character class are tokens.
# Learnable tokenization:
A maximum entropy tokenizer , detects token boundaries based on probability model.
# TOKENIZATION
Tokenization is essentially splitting a phrase, sentence, paragraph, or an entire text document into smaller units, such as individual words or terms. Each of these smaller units are called tokens. The tokens could be words, numbers or punctuation
marks. In tokenization, smaller units are created by locating word boundaries. Tokenization is the first step in text analytics. The process of breaking down a text paragraph into smaller chunks such as words or sentence is called Tokenization. Token is a single entity that is building blocks for sentence or paragraph.

# STEMMING
Stemming is a process of linguistic normalization, which reduces words to their word root word or chops off the derivational affixes. For example, connection, connected, connecting word reduce to a common word "connect".
#  LEMMATIZATION
Lemmatization reduces words to their base word, which is linguistically correct lemmas. It transforms root word with the use of vocabulary and morphological analysis. Lemmatization is usually more sophisticated than stemming. Stemmer works on an individual word without knowledge of the context. For example, The word "better" has "good" as its lemma. This thing will miss by stemming because it requires a dictionary look-up.
# Personal Query Response System
Pre-processing is applied to the input text to standardize the input as per the system’s requirement. Based on the keywords used in the text, appropriate context is recognized. Upon receiving personal queries like CGPA, attendance, etc., the
authenticity of the user is checked through user-id and password. If the user detail is invalid, an appropriate response is sent. If the user authenticates successfully, the input text is processed to extract keywords. Based on the keywords, information required by the user is understood and the information is provided from the database
# Training and testing the dataset
The training data is used to make sure that machine recognises patterns in the data,the cross-validation of the data is used to ensure better accuracy and efficiency of the algorithm used to train machine.Initially, bot has to greet the user who using the website.so,greeting and specified person response is generated using code and their outputs are displayed.There are various approachs for designing a chatbot. In this rule based approach. There is a fixed set of response available and based on a certain rule, a response is selected. For example users says “hello” generate a response ”hi, how are you?”. The main advantage of this approach they often provide perfect response for the user quries. Developing a chatbot is a simple task which is capable of responding to the user queries related to college and will generate answers based on cosine similarity. Download the required libraries using NLTK to create our chatbot.
# Handling Greetings: 
We want our chatbot to reply to greetings.For that,we will create a function that handles greetings.We will create two lists with different types of greeting messages.
# Response Generation:
We need to create a method for general response generation using Cosine similarity.
# RULE BASED ALGORITHM
Rules typically take the form of an {IF:THEN} expression, (e.g. {IF 'condition' THEN 'result'}, or as a more specific example, {IF 'red' AND 'octagon' THEN 'stop-sign'}). An individual rule is not in itself a model, since the
rule is only applicable when its condition is satisfied. Therefore rule-based machine learning methods typically comprise a set of rules, or knowledge base, that collectively make up the prediction model.
# CONCLUSION
Chatbots are extremely valuable for businesses and the value will only increase as time goes by. While the technology to simulate conversation with a computer has been around for decades, bots are adaptable version with a powerful integration of
Artificial Intelligence and Natural Language Processing. It creates an assisting guide to all users. It increases the efficiency by maintaining known standard responses. Improved question responsiveness and accuracy. Increased ability to
track and monitor queries, highlighting gaps in available information. The impact of NLP by machine will be greater than the impact of microprocessor technology in the last 20 years, because Natural Language is fundamental to almost all business, military & social activities. Therefore, the application of NLP has no end. In future the proposed system will be able interpret the textual description in a much better way.
