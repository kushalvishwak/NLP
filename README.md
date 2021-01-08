# NLP
What Is Natural Language Processing?
Natural language processing (NLP) refers to the branch of computer science and more specifically, the department of AI, concerned with giving computers the capacity to recognize the text and spoken phrases in a great deal the same way people can.
We can use NLP to developing systems like machine translation, speech recognition, spam detection, sentiment analysis, text simplifications, and plenty more.
Few Real-Time examples include:
Google Translate
Grammarly
Cortana
Alexa
OK Google
nlp-use-cases

 

How Does Machine Understand Text?
We do know that machines only understand numbers i.e. 010101 not words or sentences.
So, before building Natural language processing models, we want to specialize in an intermediate step, which is the text representation.
Text representation was created on a basic idea, which is one-hot encodings.
In one-hot encodings, a sentence is represented as a matrix of shape (NxN) where N represents the number of particular tokens within the sentence.
For example, in the below picture, each word is expressed as sparse vectors except one cell (occurrences of the word in the sentence).
one-hot-encodings

###Parts of NLP (Natural Language Processing)
1) Lexical Analysis: With Lexical Analysis, we divide a complete part of the text into paragraphs, sentences, and words, which involves identifying and analyzing the structure of words.

2) Syntactic evaluation: The syntactic analysis includes the evaluation of phrases in a sentence for grammar and arranging phrases in a way that suggests the connection of many of the phrases. as an example, the sentence “the shop is going to the house” does no longer passes.

3) Semantic evaluation: Semantic evaluation attracts the precise meaning for the words, and it analyzes the textual content meaningfulness. Sentences that include “hot ice-cream” do now not skip.

4) Disclosure Integration: Disclosure integration takes into consideration the context of the text. It considers the which means of the sentence before it ends. as an instance: “He works at Google.” in this sentence, “he” needs to be referenced within the sentence earlier than it.

5) Pragmatic evaluation: Pragmatic evaluation offers with normal conversation and interpretation of language. It offers with deriving meaningful use of language in diverse conditions.

NaturalLanguage_Diagram-1

Natural Language Processing Algorithms
Before diving into the coding part, we will first understand the concepts beneath them. The foremost frequently used algorithms in Natural language processing when defining the 

vocabulary of terms:

1) Bag of Words
Is a regularly used model that permits us to count all words in a piece of text. Basically, it makes an occurrence matrix for the sentence or document, disregarding grammar, and word order.
These word occurrences or frequencies are then used as features for training a classifier.


2) Tokenization
The process of separating the running text into sentences and words is termed Tokenization. Basically, it’s the task of cutting a text into items called tokens, and at the same time push away certain characters, like punctuation.


3) Lemmatization
Lemmatization settles words into their dictionary form for which it needs detailed dictionaries in which the algorithm can view and link words to their corresponding form.


4) Stemming
In this process, we slicing the end or the beginning of words with the purpose of removing affixes.
The issue is that affixes can make or expand new forms of the same word or even make new words themselves.

NLP is divided into two major components :-

1. NLU(Natural language understanding)
It refers to map given input in natural language(the language we speak or write) into useful representation and analyze the different aspects of the language. (SEE five processes of NLP)


 
2. NLG(Natural language generation)
After understanding the input(natural language), NLG produces meaningful phrases and sentences from the representation that NLU does. It involves

Text planning:- It finds the relevant content from the representation.
Sentence planning:-It choose the required word and then forms meaningful phrases.
Text realisation:-At last, it maps the sentence planning and makes the full structure.
NLU is harder than NLG because it takes lots of time and processes to understand a particular language, especially for machines.

How does NLP work?
There are five processes in NLP:-


 
1. Tokenization
It divides(tokenizes) the given sentence into words. Input: Students are going to school. Output: [‘Students’ , ‘are’ , ‘going’ , ‘to’ , ‘school’]

2. Stemming
With the help of stemming, we can find the root of any word by removing the end or beginning of the word. For example, ‘go’ root has variations like ‘gone’ , ‘going’ , ‘goes’ etc. The problem of stemming is that it doesn’t get success always.

3. Lemmatization
The role of stemming and lemmatization is almost similar but in a different way. Let me make you clear. In stemming, to find the root of the word, it removes the beginning or end of the word like going–> go, worked–>work. But in terms of ‘went’, it won’t work. Here lemmatization will help to find the root of the word. For example:- went–>go , drunk–>drink , brought–>bring etc.


 
4. POS Tags
POS stands for Parts of speech. What does it do? It identifies the part of speech of each word. Ex:- Input: Rahul went to market. Output: [(‘Rahul’, NNP),(‘went’, VBD), (‘to’, TO), (‘market’, NN)]. Here NNP refers to a Proper noun, VBD refers to verb past tense, TO refers to infinite, NN refers to a singular common noun.

5. Named Entity Recognition
NER is used to detect the named entity like the given word is related to which part of speech. Is it the name of a person, company name, quantity, or location? For example:- “Google something on the Internet”. Here Google is not a company, it is a verb. “Bat flies at night”. Here Bat is a mammal, not that one used in cricket. Named entity recognition does all that stuff.

6. Chunking
Chunking is used to add more structures. It picks up an individual piece of a word and grouping them together into the full sentence. For example:-“Farmers killed the snake”. According to the structure or part of speech, Chunking forms the sentence, which helps in getting insights and meaningful information.

