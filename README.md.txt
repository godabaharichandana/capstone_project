Breast Cancer Wisconsin Diagnostic Data set
Using the Wisconsin breast cancer diagnostic data set for predictive analysis
Data source:
https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/
This dataset consists of 569 instances with 32 attributes and it is a multivariate because it consists Categorical, real and integer valued attributes. For the best result I will split the data into training and testing sets. On a whole I will assign 70% of data to training set and 30% of data testing set.                                                                                                                                                            
Attributes are:
1.  ID number
2.  Diagnosis (M = malignant, B = benign) 
3-32) Ten real-valued features are computed for each cell nucleus: 
a) radius (mean of distances from center to points on the perimeter) 
b) texture (standard deviation of gray-scale values) 
c) perimeter 
d) area 
e) smoothness (local variation in radius lengths) 
f) compactness (perimeter^2 / area - 1.0) 
g) concavity (severity of concave portions of the contour) 
h) concave points (number of concave portions of the contour) 
i) symmetry 
j) fractal dimension ("coastline approximation" - 1)
The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius. All feature values are recoded with four significant digits. 
 Missing attribute values: none 
 Class distribution: 357 benign, 212 malignant 
Result:
Before feature reduction the accuracy scores given by different models are:
Random Forest Classifier     -- 94%
Support Vector Classifier     --60%
KNeighborsClassifier             --95%
GaussianNB                              --94%
Decision Tree Classifier        --92%
Logistic Regression                --95%
After feature reduction the accuracy scores given by different models are:
Random Forest Classifier    -- 90%
Support Vector Classifier     --80%
 KNeighborsClassifier           --82%
 GaussianNB                             --88%
 Decision Tree Classifier       --81%
Logistic Regression                 --90%


