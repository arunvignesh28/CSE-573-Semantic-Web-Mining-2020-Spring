# Movie Recommender System using Deep Learning and Apache Spark

1. The submission has 3 sub-directories CODE, DATA and Evaluations
2. The CODE has 2 more sub-directories:

    a. notebook : Contains Jupyter Notebook for the implemented models


                  1. rbm_based_recommender.ipynb : Contains code for Content Based Recommender as well as Restricted Boltzmann machine      based Collabrative filtering. It also contains code for Hybrid Recommender


                  2. sgd.ipynb : Contains code for Matrix Factorizaion using Stochastic Gradient Descent Recommmender


                  3. Copy_of_Movie_recommender.ipynb : Contains code for Matrix Factorizaion using Alternating Least Square Recommmender


                  4. USER_based.ipynb : Contains code for User Based Collabrative filtering


                  5. Item_based.ipynb : Contains code for Item Based Collabrative filtering

    b. app : Contains code for web  application. There is a main.py file that contains REST APIs written in flask. There is also a UI folder that contains index.html which contains UI code.
3. The DATA sub-directory contains dataset that we used. It contains MovieLens100K dataset and The Movies Dataset. We also reffered MovieLens20M dataset which can be referred here http://dx.doi.org/10.1145/2827872.
4. The EVALUATIONS contain RMSE plots for RBM, Matrix Factorizaion using SGD and ALS. It also contains a matrix to illustrate user based similarity matching.

