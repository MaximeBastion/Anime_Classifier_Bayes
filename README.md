# Anime Classifier: Multinomial Naïve Bayes

#### Work in Progress

## Goal
Classify animes using their synopses into genres.
We would like to have an accuracy per genre of at least 80%. It means that, for a given genre, at least 80% of animes were correctly assigned their presence or absence of this genre. We will not define our accuracy has the percentage of animes for which we guess perfectly the presence and absence of all the genres, this would be extremely hard to accomplish with this algorithm.

## Steps
* Fetch anime data using an API
* Parse this data into class instances to facilitate processing
* Create a dataframe using our data, adding, for each word of the vocabulary, its number of occurences in each synopsis
* Implement the Multinomial Naïve Bayes algorithm -> calculate constants + classify
* Compute the accuracy in details
* Analyse & Visualize these accuracies
* Interpret our results