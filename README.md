# Classification_Model_For_Star_Type
Classification model using decision tree classifier from Scikit learn Library to identify star types from NASA dataset.
The diagram below shows most of the major types of stars (the majority of stars are main sequence stars).
Stars just like our own Sun that burn hydrogen into helium to produce energy.
![image](https://user-images.githubusercontent.com/114074370/230721832-72458a65-6fa4-4058-863b-e06aec4ab821.png)
This system is referred to as the Morgan Keenan system. The Morgan-Keenan (MK) system is used in modern astronomy a classification system to organize stars according to their 
spectral type and luminosity class. 
The system was introduced by William Wilson Morgan and Philip C Keenan in 1943.

The data provided in the Val file can be represented via heatmaps and different graph against the different properties of the 
star.
![image](https://user-images.githubusercontent.com/114074370/230721932-477c079a-7240-4c1a-8ab3-9f00e0d6b30d.png)
![image](https://user-images.githubusercontent.com/114074370/230721968-353e05e5-6987-4fcc-af50-f8ab9db9a92c.png)

<<One Hot Encoder>>
One hot encoding is one method of converting data to prepare it for an algorithm and get a better prediction.
With one-hot, we convert each categorical value into a new categorical column and assign a binary value of 1 or 0 to those columns. Each integer value is 
represented as a binary vector.
In this case we use the encoder to convert categorical values of star types and assign binary values to them.

<<Random Forest Classifier>> 
Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive 
accuracy of that dataset. Instead of relying on one decision tree, the random forest takes the prediction from each tree and based on the majority votes of predictions,
and it predicts the final output.

The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.
![image](https://user-images.githubusercontent.com/114074370/230722199-0b0bbc68-9cd5-4d05-88b2-0e497b63a481.png)
