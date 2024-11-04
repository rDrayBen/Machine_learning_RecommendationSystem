# Machine_learning_RecommendationSystem

In this notebook, the recommendation model algorithm was implemented based on KNNBaseline using the Surprise library. For this, a given dataset containing information about various bundles and their attributes was used.
The structure of the dataset and the characteristics of the algorithm were studied.
The implemented recommender system is based on this dataset and algorithm, and was cross-validated.
In the process of analyzing the results, it was found that the system makes the most mistakes on subjects with a small number of similar users or subjects in the training data set.
Some items have a large number of similar users, which contributes to more accurate recommendations.
To improve the accuracy of the model, hyperparametric tuning was performed using GridSearchCV and ranking normalization, which allowed to reduce the values ​​of the RMSE and MAE metrics. Compared to a random recommender system,
the system based on KNNBaseline showed significantly better results, highlighting the importance of using specialized algorithms for the recommendation task.
