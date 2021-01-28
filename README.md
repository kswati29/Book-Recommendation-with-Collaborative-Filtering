# Book-Recommendation-with-Collaborative-Filtering
Using Memory and Model based Collaborative Filtering 

## Introduction and Goal
 Analysing the needs of the user and providing recommendations to find what they like without searching is prevalent in almost every aspect like in e-commerce, music, books, social media, advertising, etc. To achieve this collaborative filtering is one such effective technique to provide data-driven recommendations.
This notebook gives book recommendations to a particular user best suited to their tastes and traits.
 
 ## Task
 This notebook demonstrates utilizing different approaches for Book Recommendation using collaborative filtering. Performed are memory and model based Collaborative Filtering(CF) and recommendations are provided for one particular user using the 4 methods. 

1. Memory-based -> Content-Based CF 
a. User-based with Eucledean Distance measure
b. Item-based with Cosine Similarity measure

2. Model-based -> Matrix Factorization based CF
a. Matrix Factorization
b. SVD++

## Result
The top 15 book recommendations for user 1839 are significantly different in the approaches.
The comparison between results shows that model based recommendations with Matrix Factorization and SVD++ somewhat match (8 out of 15) match. However, memory based recommendations do not match among themselves and even with model based recommendations. Evaluation of recommendation systems has not been covered and is worth exploring.
 
