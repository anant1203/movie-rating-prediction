# movie-rating-prediction
Predicted the imbd rating of the movie using machine learning algorithm and Neural Network

# Pre Processing
1) Removed the null value rows from the data
2) Removed the feature such as aspect ratio, link and many other which didnot had any impact on the prediction.
3) Convert the column having string value to numberical value

# Data Visualization:
1) Ploted the histogram of the imdb value to check the distribution.
2) Ploted the pair plot to check relation between features.
3) Ploted the joint plot of feature with imdb score to check there relation with the data and accordingly removed those features.

# Result

| Model                  	| Accuracy 	| Mean aboslute error 	|
|------------------------	|----------	|---------------------	|
| Random Forest          	| 90.49    	| 0.52                	|
| Xg boost               	| 90.3     	| 0.53                	|
| Support Vector Machine 	| 85.18    	| 0.82                	|
| Decision Tree          	| 87.2     	| 0.73                	|
| Neural Network         	| 84.83    	| 0.83                	|

### Since random forest and Xg boost performance is similar and according to theory Xg boost performace should be better than random forest because of boasting apporach. XG Boost will be better model for deployment in production.
