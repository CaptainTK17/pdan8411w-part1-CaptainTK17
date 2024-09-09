News Classification
Author: Ntsika Shangase
Student Number: ST10117400
Dataset reference:
https://www.kaggle.com/datasets/rmisra/news-category-dataset
1. Misra, Rishabh. "News Category Dataset." arXiv preprint arXiv:2209.11429 (2022).
2. Misra, Rishabh and Jigyasa Grover. "Sculpting Data for ML: The first act of Machine Learning." ISBN 9798585463570 (2021).

Necessary features to run:
due note current project was built using .conda(python 3.11.9) kernel
any package install code seen in notebook must be installed in order for notebook cells to run

 Dataset description:
About 210 000 news headlines from HuffPost from 2012 to 2022 are included in this collection. It can be used as a benchmark for several computational linguistic problems. This is one of the largest news databases. As of some point following this dataset's first collection in 2018, HuffPost ceased maintaining a sizable archive of news items, making it impossible to gather such a dataset today. There were around 200k headlines between 2012 and May 2018, and 10k headlines between May 2018 and 2022, because of website updates.
Why this dataset
This data set was chosen for its large capacity of items having a data size of over 200000, it is a natural language data set and can be analysed using RNN, LSTM and psyspark
Attributes for dataset:
•	category: category in which the article was published.
•	headline: the headline of the news article.
•	authors: list of authors who contributed to the article.
•	link: link to the original news article.
•	short_description: Abstract of the news article.
•	date: publication date of the article.


What is a recurrent neural network
A sort of artificial neural network called a recurrent neural network (RNN) is made to handle sequential data or time-series data. RNNs, in contrast to conventional feedforward neural networks, have loops that enable data to be transmitted from one stage of the network to the next. RNNs are well suited for problems involving sequences or temporal dependencies because of their looping structure, which allows them to keep some sort of recollection of past inputs.
The most pivotal feature of a an RNN is its hidden layer which let the network to store data from earlier inputs and use it to process incoming data later. The network receives as inputs from each time step of the sequence both the current input and the hidden layer from the previous time step.

Analysis
The analysis preformed on the data is as follows:
•	Data Cleaning: To manage missing values, eliminate extraneous letters or symbols, and standardise the text data for subsequent processing, the dataset may require cleaning steps.
•	Exploratory Data Analysis (EDA): EDA techniques can be used to acquire insights into a dataset, such as assessing the distribution of true and fake news, analysing the frequency of various subjects, or discovering patterns and relationships between variables.
•	Visualisation: Visualisations can be made to help users better grasp the data. Word clouds, bar graphs, and histograms, for example, might provide visual representations of frequently occurring terms, subject categories, or other significant characteristics of the collection.
•	Text Pre-processing: Text pre-processing stages can include tokenization (splitting text into individual words or tokens), stemming (reducing words to their root form), and lemmatization (reducing words to their base form). These strategies aid in standardising and normalising text data.

Terminology:
•	Corpus: A corpus of text data is a group of documents.
•	Vocabulary(BoW): The amount of distinct words found in a corpus of text is what is known as a vocabulary or bag of words.
•	Stop words: Stop words lack significance in the context of the text and are among the most often used terms in any language, such as "the" and "a."
•	N-grams: To extract meaning and context from each phrase or paragraph, text is represented in the form of N-word sequences.
•	Tokenization: Text phrases are first broken up into smaller words or tokens as part of the NLP process.
•	Vectorization: Because machines cannot comprehend text or words, text data or tokens must be transformed into word vectors or word indices that may be used to process text and create models. A procedure known as vectorization transforms tokenized words into numerical vectors.




