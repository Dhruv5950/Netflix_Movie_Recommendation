# Netflix_Movie_Recommendation
Predicting the movie for a user i.e building a movie recommendation system
![Netflix](https://news-cdn.softpedia.com/images/news2/Netflix-Wants-Personalized-Recommendations-Instead-of-Current-Interface-443094-2.jpg)

Requirements

python-3.6.0
conda-5.2
numpy-1.15.0
pandas-0.23.2
sqlite-3.24.0
scikit-learn-0.19.2
Simple Python RecommendatIon System Engine(Surprise) library.

Took the dataset from https://www.kaggle.com/netflix-inc/netflix-prize-data 

We first took all the text files and combined them to a single csv file and then did all the pre-processing and EDA.
Then, we trained or models on the data after cleaning and pre-procesing of the data with the help of surprise libray and took the result from each model as feature for our next model.

We took a sample of dataset to see the performance of our model and used XGBoost as our final model after feature engineering.

The performance metric used was RMSE. For a sample of dataset the RMSE reduced slightly but applying on the complete dataset will reduce the RMSE significantly, resulting in appropriate results.
