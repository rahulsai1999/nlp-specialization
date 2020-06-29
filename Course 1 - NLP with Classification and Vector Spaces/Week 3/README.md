## Week 3 - Word Embeddings

### Vector Space Models

- Vector space models are an important idea in both supervised Machine Learning and Natural Language Processing.
- Suppose you have two sentences which contain identical parts, but completely different meaning.
  - **Where are you** heading?
  - **Where are you** from?
- Whereas we can have sentences which have the same meaning but are completely dissimilar
  - What is your age?
  - How old are you?
- Vector space models help us identify similarity of the words and capture the relationship between neighbouring words for applications such as question answering, paraphrasing and summarization.

  ![vectorspace](images/vectorspace.jpg)

### Word by Word and Word by Doc

- Vectors can be constructed based off a co-occurence matrix with two possible designs, either encoding a word or document as a vector.
- To make a vector space model using a word by word design, you have to make a co-occurence matrix and extract the vector representations for the words in the corpus.

![wordword](images/wordbyword.jpg)
![worddoc](images/worddoc.jpg)
![vectorspace2](images/vectorspace2.jpg)
