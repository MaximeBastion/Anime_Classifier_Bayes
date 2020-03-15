# Anime Classifier: Multinomial Naive Bayes

#### Work in Progress

## Goal
Classify animes using their synopses into genres.

| Synopsis | Classification
| --- | --- |
| Centuries ago, mankind was slaughtered to near extinction by monstrous humanoid creatures called titans[...] | Action, Military, Mystery, Super Power, Drama, Fantasy, Shounen

## What is the Naive Bayes algorithm?
The algorithm we are going to use is the Multinomial Naive Bayes algorithm. It is a simple probabilistic classifier based on applying Bayes' theorem.

Bayes' theorem describes a conditional probability: the probability of a event given another event.

The general idea, applied to our problem, is that we are going to compute the "probability" of an anime being of or not being of a particular genre given its synopsis, which means given each word in its synopsis. The highest "probability" between the two will be our verdict.
The algorithm learns from previously classified animes to classify new ones.

## What is our accuracy goal?
We would like to have an accuracy per genre of at least 80%. It means that, for a given genre, at least 80% of animes were assigned an accurate presence or absence value for this genre.

## Steps
* Fetch anime data using an API
* Clean it
* Prepare for the Naive Bayes algorithm
* Apply the algorithm to classify animes into genres
* Analyze our accuracies per anime and per genre in details
* Look for correlations to explore what makes genres easy or hard to predict
* Explore the relationships between genres
* Visualized the most significant words for given genres

#### There are more explanations in the notebook file.