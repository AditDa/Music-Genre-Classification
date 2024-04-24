# Music-Genre-Classification
# Music Genre Classification Project

## Contribution
Adit Dahiya (U2323943D)   
Advik Dahiya (U2323843G)  
Dhairya Kakkar (U2323283F)  
Everyone contributed equally

## Motivation
In today's world, where platforms like Spotify and Apple Music host over 100,000 new song uploads daily, discovering new music within preferred genres becomes challenging. Our motivation stemmed from the common frustration of not easily finding desired songs, leading us to work on this project.

## Problem Statement
To Predict the music genres after analyzing the characteristics of the songs to improve user experience on music platforms.

## Exploratory Data Analysis
Upon importing the dataset titled "Prediction of music genre" by VICSUPERSTAR from Kaggle, we observed it contained 50,005 rows and 18 columns. We selected 10 variables we deemed relevant to music genre prediction, excluding variables like track name and release date, and included other numerical variables.

## Data Cleaning
Some rows had the “?” symbol in the ‘tempo’ variable making it of object type instead of float. We removed these rows and other NA rows and converted the ‘tempo’ into the float data type resulting in a final dataset with 45,020 rows.

## Visual Analysis
We visually analyzed the variables using box plots, KDE plots, violin plots, and heat maps to understand each variable's distribution, range, details, and correlation with the other variable.

## Machine Learning
We applied the machine learning technique of classification and implemented 4 classification methods: Random Forest Classifier, Decision Tree Classifier, Gradient Boosting Classifier, and the Gaussian Naive Bayes method.

### Random Forest Classifier
It achieved an accuracy of approximately 97% for the training dataset and 55% for the test dataset. 

### Decision Tree Classifier
It achieved an accuracy of approximately 97% for the training dataset and 44% for the test dataset.

### Gradient Boosting Classifier
It achieved an accuracy of approximately 66% for the training dataset and 57% for the test dataset, performing the best among the models tested.

### Gaussian Naive Bayes Method
It Achieved an accuracy of approximately 44% for both the training and test datasets and had the lowest performance among all models.

### Confusion Matrix
We printed out the confusion matrix for each model to visually interpret the accuracy. The diagonals show the correct predictions and the rest are the incorrect predictions.

## Outcome
The Gradient Boosting Classifier achieved the highest accuracy at 57% which shows a moderate success in genre classification. More enhancements are required for a larger usage and applicability in the future and music platforms. An interesting fact is that even basic features like tempo, energy, loudness etc. can moderately predict music genres, laying a starting point for developing more robust and advanced systems.

## Conclusion
Our project addresses the challenge of music genre classification, providing insights into the potential of various machine-learning techniques and the potency for further enhancements.

