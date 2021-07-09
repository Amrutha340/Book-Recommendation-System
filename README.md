# Book Recommendation through Collaborative Filtering

Working Approach:

Here we are using Collaborative Filtering to provide high quality book  recommendations to user  based on considering user interests (or) likes/dislikes. 
We are implementing the Collaborative Filtering algorithms through algorithms like K-NN, matrix factorization and others for providing relevant and personalized recommendations.
Collaborative filtering technique predict the most likely products that the users are of interest by collecting opinions from customers in the form of ratings on items .There were two types of collaborative filtering techniques:

(1)Memory-Based Collaborative filtering
(2)model- Based Collaborative filtering

In memory based, for both, user-based & item-based approach, KNN inspired algorithms from surprise package are used.
1.	Knn basic
2.	Knn with Zscores
3.	Knn with Means
 
RMSE , MAE is used to evaluate the model built.
Lower the values of rmse and mae, better is the performance of model.
Model is optimized to provide the best predictions using GridSearchCV.
Pickle module in python is used to store models (built in this module) into files, and load them (in another module) when it is required.

In model based, Matrix factorisation is used to identify relationship between users’ and items’ entities. We use SVD & NMF (matrix-factorization based algorithms). 

1. SVD- Singular Value Decomposition is a matrix factorisation technique, which reduces the number of features of a dataset by reducing the space dimension from N-dimension to K- dimension (where K<N).

2. NMF- Non-negative Matrix Factorization is very similar to svd where user and item factors are kept positive. It is a group of algorithms in multivariate analysis and linear algebra where a matrix V is factorized into (usually) two matrices W and H, with the property that all three matrices have no negative elements. This non-negativity makes the resulting matrices easier to inspect
