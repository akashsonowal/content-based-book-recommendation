# content-based-book-recommendation

## Project Description:

Recommendation systems are at the heart of many products such as Netflix or Amazon. They generally rely on metadata (e.g., the actors or director of a movie) or on user tastes (e.g., the movies you liked before) to determine which you are most likely to enjoy. But when you are working with text-heavy datasets, you have access to a much richer resource—the whole text! In this project, you will learn how to build the basis of a book recommendation system based on their content. You will use Charles Darwin's bibliography to find out which books might interest you.

## Approach:

- Performed text stop words removal, tokenization, stemming, explored character counts in each book; Created dictionary corpus from all of the 20 raw textbook files of Charles Darwin’s collection. 
- Applied bag-of-word, tf-idf models to vectorize our textbooks; Calculated cosine-similarity matrix from pairwise distance of all textbooks; Plotted dendrogram to understand the similarities. 

## Result:

Recommended books by sorting similarity score value to a user’s initial pick in the collection.  

## Data Description:

The dataset was manually collected from Project Gutenberg.

## Acknowledgement:

[DataCamp](https://www.datacamp.com/projects/607)

Project Tasks

Darwin's bibliography
Load the contents of each book into Python
Find "On the Origin of Species"
Tokenize the corpus
Stemming of the tokenized corpus
Building a bag-of-words model
The most common words of a given book
Build a tf-idf model
The results of the tf-idf model
Compute distance between texts
The book most similar to "On the Origin of Species"
Which books have similar content?
