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
Before diving into the coding part, we will first understand the concepts beneath them. The foremost frequently used algorithms in Natural language processing when defining the vocabulary of terms:

1) Bag of Words
Is a regularly used model that permits us to count all words in a piece of text. Basically, it makes an occurrence matrix for the sentence or document, disregarding grammar, and word order.
These word occurrences or frequencies are then used as features for training a classifier.
bag-of-words

2) Tokenization
The process of separating the running text into sentences and words is termed Tokenization. Basically, it’s the task of cutting a text into items called tokens, and at the same time push away certain characters, like punctuation.
tokenization-sample

3) Lemmatization
Lemmatization settles words into their dictionary form for which it needs detailed dictionaries in which the algorithm can view and link words to their corresponding form.
lemmatization-sample

4) Stemming
In this process, we slicing the end or the beginning of words with the purpose of removing affixes.
The issue is that affixes can make or expand new forms of the same word or even make new words themselves.
stemming-sample
