# Anime Classifier: Multinomial Naive Bayes

## The Project in 3 Videos
Note: My native language is French.

<a href="https://www.youtube.com/watch?v=ZdGfkNaPNVc">
         <kbd><img alt="Anime Classifier Video Part 1" src="https://img.youtube.com/vi/ZdGfkNaPNVc/maxresdefault.jpg"
         width=50%" height="50%"></kbd>
</a>
                                

<a href="https://www.youtube.com/watch?v=qjvyhCJLsN4">
         <kbd><img alt="Anime Classifier Video Part 2" src="https://img.youtube.com/vi/qjvyhCJLsN4/maxresdefault.jpg"
         width=50%" height="50%"></kbd>
</a>    
                                  
<a href="https://www.youtube.com/watch?v=C2ObEp81JOU">
         <kbd><img alt="Anime Classifier Video Part 3" src="https://img.youtube.com/vi/C2ObEp81JOU/maxresdefault.jpg"
         width=50%" height="50%"></kbd>
</a>


## Goal
Classify animes using their synopses into genres.

| Synopsis | Classification
| --- | --- |
| Centuries ago, mankind was slaughtered to near extinction by monstrous humanoid creatures called titans[...] | Action, Military, Mystery, Super Power, Drama, Fantasy, Shounen

## What is the Naive Bayes algorithm?
The algorithm we are going to use is the Multinomial Naive Bayes algorithm. It is a simple probabilistic classifier based on applying Bayes' theorem.

Bayes' theorem describes a conditional probability: the probability of an event happening given the fact that another event happened.

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
* Visualize the most significant words for given genres
* Conclude the project, comment it & visualize the duration of the project

#### There are more explanations in the notebook file.
