# Chatbot-for-College-Website
<i>A machine learning project done under the guidance of DLithe Company.</i>
<br><b>DLithe Internship Certification Program</b></br>
<br><b>Project Topic:</b> Chatbot for College Website using NLTK</br> 
<br><b>Reference:</b> Dlithe</br>
<br><b>Website:</b> www.dlithe.com</br>
<br><b>Project done under the guidance of:</b> Dlithe</br>
<br><b>Done by:</b> SWATHI N </br>
<br><b>Chatbot for College Website Information using NLTK for Machine Learning</b></br>
<br><p>

<b>Abstract:</b>
The Main idea behind this project is to Implement Chatbots for College Website where 
the queries related College asked by the user is answered by the Chatbot.<br>

<b>Natural Language Toolkit:</b>
NLTK contains a set of libraries and programs that are written for Statistical Natural Language Processing(NLP)
in English, that is used in Python Programming Language.
To install NLTK : pip install nltk<br>

NLTK is used to support NLP in areas like Artificial Intelligence, Machine Learning etc.

<b>Classification in NLTK:</b>
1.Tokenization
2.Stemming
3.Tagging
4.Parsing
5.Semantic Reasoning Functionalities.<br>

In the Implementation of Chatbot, I have used Tokenization and Stemming.

<b>Tokenization:</b>
Tokenization is a way to split text into tokens. These tokens could be paragraphs, sentences, or individual words.
NLTK provides a number of tokenizers in the tokenize module.
The text is first tokenized into sentences using the PunktSentenceTokenizer.<br>

<b>PunktSentenceTokenizer:</b>
Punkt Sentence Tokenizer. This tokenizer divides a text into a list of sentences, by using an unsupervised algorithm to build a model for abbreviation words, collocations, 
and words that start sentences.It must be trained on a large collection of plaintext in the target language before it can be used.<br>

<b>Stemming:</b>
Stemming is the process of producing morphological variants of a root/base word. Stemming programs are commonly referred to as stemming algorithms or stemmers.
A stemming algorithm reduces the words to the root word, and reduce to the stem word.
Ex: Chocolate, chocolatey to "choco"
    Spending to "spend"<br>

Importing required libraries like io, random,strings to process random strings in the output, numpy and NLTK.

In NLTK, Import WordNetLemmatizer which is similar to stemming, but the reduced words are not random words but words with actual meanings. It is called lemmas.

A text file is given as input with all the data related to the college website which is imported to the program.
The data is read and raw data is taken from it, to give answers to the queries on the user input.

The main reason to convert all the input data into either upper case or lower case is that the data is treated same then.

<b>Response Generation:</b>
After the preprocessing phase, the text has to be transformed into meaningful array of numbers. 
The bag-of-words is a representation of text that describes the occurrence of words within a document.
It involves two things:
1)A vocabulary of known words.
2)A measure of the presence of known words.<br>

<b>Term Frequency (TF)</b>
The number of times a word appears in a document divded by the total number of words in the document. Every document has its own term frequency.

TF = (Number of times term t appears in a document)/(Number of terms in the document)<br>

<b>Inverse Data Frequency (IDF)</b>
The log of the number of documents divided by the number of documents that contain the word w.
Inverse data frequency determines the weight of rare words across all documents in the corpus.

IDF = 1+log(N/n), where, N is the number of documents and n is the number of documents a term t has appeared in.

<b>Document Similarity</b> is used to generate a response from the bot for input questions by the user. 
A function response defined, searches the user’s input for one or more known keywords and returns one of several possible responses. 
If it doesn’t find the input matching any of the keywords, it returns a response:"I am sorry! I don't know that!"

Code is written for the Bot as how to start the conversation and how to accordingly responds to the users input.
To exit the conversation with Bot, type exit and the Bot will respond "Bye! Have a Nice Day!" and then exits the program.</p>






