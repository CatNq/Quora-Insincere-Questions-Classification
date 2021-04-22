# Quora-Insincere-Questions-Classification

# Problem

An existential problem for any major website today is how to handle toxic and divisive content. 
Quora wants to tackle this problem head-on to keep its platform a place where users can feel safe sharing their knowledge with the world.
The objective is to predict whether a question asked on Quora is sincere or not. 
An insincere question is defined as a question intended to make a statement rather than look for helpful answers.

# Solution

I used Natural Language Processing for text classification. We will compare the performance of models using these pre-trained embeddings against the baseline model that doesn't use any pre-trained embeddings.
Embeddings generally represent geometrical encodings of words based on how frequently appear together in a text corpus.

# Data

The training data includes the question that was asked, and whether it was identified as insincere (target = 1). 
The ground-truth labels contain some amount of noise: they are not guaranteed to be perfect.

Note that the distribution of questions in the dataset should not be taken to be representative of the distribution of questions asked on Quora. 
This is, in part, because of the combination of sampling procedures and sanitization measures that have been applied to the final dataset.
