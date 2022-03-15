# chatbot
ChatBot using Python
Types of Chatbots:

Text Based Chatbots
Voice Based Chatbots
Rule Based Chatbots
Self Learning Chatbots



Applications:

Helpdesk
Email 
Home Assistent
Operations Assistent
Phone Assistent
Entertainment Assistent

Architecture:

 Chat								<-->	Corpus
window		          <-->	Interface       	<-->	NLP Model	
or session					<-->	Application DB

How Chatbot Works:

1. Import Corpus.
2. Preprocess the data.
3. Text case handeling.
4. Tokenization.
5. Stemming.
6. Bag of Words.
7. One hot encoding.

Corpus:
-> Training Data needed for chatbot to learn.
-> Without corpus chatbot does not work.

Data Preprosessing - Text case handeling:
-> Convert all data input to either upper or lower case.
-> It will avoid misrepresentation and misinterpritation of words if spelt under lower or upper case.

Tokenization:

[This is a bag]	-->	[This] [is] [a] [bag]
Sentence to words.

Stemming:

Original  |	 Root	 |     Similar Words
word	 	  |  word  |
____________________________________________      
Jump		  |  Jump	 |
Jumped		|  Jump	 |   Word with similar
Jumps		  |  Jump	 |  root word i.e. JUMP
Jumping		|  Jump	 | 
