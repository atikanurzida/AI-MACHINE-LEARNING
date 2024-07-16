# Linear Regression & Decision Tree

## About Dataset
This dataset is obtained from the Data Series 10.0 AI Machine Learning bootcamp by dibimbingid. This dataset contains columns of student study time (Hours) and student scores (Scores). The purpose of the analysis is to predict the effect of study time (Hours) on the scores obtained from the exam results (Scores). The methods used are Linear Regression and Decision Tree.


#### _**Why use two methods?**_

Two methods are used to minimize the prediction error measured by the difference between the observed value and the value predicted by the model.


### **Linear Regression**

    Linear regression is a statistical and machine learning method used to model the relationship between one or more independent variables (features) and a dependent variable (target). The goal of linear regression is to find a straight line (or hyperplane in the case of multivariate) that best fits the data so that it can be used to predict target values based on feature values.

    There are two types of regression: simple linear regression and multiple linear regression. In this case, simple regression analysis is used because there is only one independent variable.

    Life applications are for example for Sales Prediction, Modeling Stock Returns, Modeling Production Time to Modeling the Number of Patients.

##### *Formula*

![Rumus Linear Regression](https://static.wixstatic.com/media/a27d24_e9c02dbb8bbd4d39b027d43f8160fe81~mv2.png/v1/fill/w_360,h_102,al_c,lg_1,q_85,enc_auto/a27d24_e9c02dbb8bbd4d39b027d43f8160fe81~mv2.png)

where 

_*x*_ is feature, _*B0*_ is intercept, and _*B1*_ is slope coefficient

### *Decision Tree*

    Decision Tree algorithms work by dividing data into smaller, more homogeneous subsets using a series of decision rules that are applied iteratively until each final node represents the final decision or prediction. The structure of a decision tree resembles a tree diagram where each internal node represents a test on an attribute (feature), each branch represents the result of that test, and each leaf node represents a class label or target value.

##### *Formula*

*Entropy*: Measures the uncertainty or impurity in the dataset. The lower the entropy, the more "pure" the data. In this case, entropy values that result in a value of 0 are labeled with "No".

![Rumus Entropy Decision Tree](https://www.ejable.com/wp-content/uploads/2023/10/entropy-formula-2.webp)

where _*Pi*_ is the probability, and _*i*_ is the number of classes

*Gain*: Measures the reduction in uncertainty or impurity after dividing the dataset by features.

![Rumus Gain Decision Tree](https://www.researchgate.net/publication/380382571/figure/fig1/AS:11431281241340994@1715088325697/Gambar-3-Rumus-Matematika-Gain.png)

where _*A*_ is feature, _*Sv*_ is subset from _*S*_ for feature _*v*_






