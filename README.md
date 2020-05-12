# Netflix-Movie-Recommendation--0-00
Netflix-Movie-Recommendation-(Collaborative based recommendation)
===================================================================

<img width=100% src="https://github.com/Raman-Raje/Netflix-Movie-Recommendation-/blob/master/netflix.jpg">

## Objective: 
For the given movie and user predict the rating given by him/her to the movie

## Description: 
The dataset was obtained from kaggle. Matrix factorization was used to get similarity
matrices. Tried and tested various ML models to get minimum Root Mean Square. Best result was
obtained for model with Matrix Factorization SVD with RMS value of 1.072

## Observation:

* All the models have tuned on 25k user dataset
* Slight reduction in RMSE found for tuned models.
* Best train result are found in case of knn_bsl_m with minimum rmse of 0.323167
* Uavg and Mavg features found most important for most of the models.
