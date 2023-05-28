# Advanced Business Analytics Assignment 3 Text Miningw with Spark Streaming

Steam is a popular digital distribution platform for video games. It allows users to purchase and
download games directly to their computers. With features like automatic updates, a strong social
community which in turn generates good deal of data. It includes game reviews that can be both
negative and positive. The goal of the project is to build a model that can use labelled data to train a
model to predict the sentiment of the review. First, data pre‐processing is conducted on the dataset
(punctuation and stop‐word removal, etc). Second, Word2Vec [7] is applied on the TF‐IDF. Third, the
following three methods are used for classification: Logistic Regression, Gradient‐Boosted Trees and
Support Vector Classification. The latter achieves the highest accuracy, 79.3% on the validation set.
