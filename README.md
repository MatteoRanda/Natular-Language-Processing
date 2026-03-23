# Natular-Language-Processing
This branch is about laboratories of university course Natural Language Processing. The first project is about text classification

- As the first task, we were asked to use a tokenizer to count the occurrence of words. We had to get a distribution as close as possible to the Zipf's law distribution.
- The second task asked to build a model for sentiment analysis, given in input a corpus text. I defined my own tokenizer, and used CountVectorizer as my vectorizer. The model for sentimen analysis is Logistic regression; grid search cross-validation was implemented. The accuracy reached was 0.85 ish on the validation set and 0.83 for the test set. There are many improvements to the code that can be done.
