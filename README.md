# DMML2021_OMEGA

Hello !

This is the team OMEGA repository for the Kaggle project at University of Lausanne.

This project deals with the detection of the difficulty level of French texts.

The team is composed by 2 members : Alexandre Lefebvre and Robin Di Fazio.

We both are students from France in exchange for a semester at HEC Lausanne.

Our approach for this project was to test several classifier algorithms, at first without data cleaning, and to select the most efficient ones.

The best score was find with this set_up : Data cleaning (Tokenization, removing stop words and punctuations, lemmatization) and we use
a Tfidf Vectorizer then a Logisitic Regression, finding best hyper-parameters using configs tests then GridSearchCV.

We tested a lot of methods explained in the notebook to try to maximize the performance, and we ended with a final performance of 0.51333, which is satisfying considered to the base rate of 0.1649, but we think we could do better.

What we finally obtain :

[Image2](https://user-images.githubusercontent.com/96356769/146658914-d8fdfe29-84b4-4c01-ae9b-82844563a265.png)
