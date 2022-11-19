# Prediction-of-Graduate-Admissions-from-International-Prespectiv with KNIME
## Dataset
*500 records data of Indian students applying for Graduate admissions.
*8 attributes provided in the data including the predictive attribute ‘chance of admit’.
*1 Categorical attribute, 6 Numerical attributes, 1 Target attribute.

![Picture1](https://user-images.githubusercontent.com/81937480/202825043-039c3562-b3c5-4081-be02-fbf04a1c7b39.png)

##Data Understanding & Preparation 
*No missing values & no erroneous entries, typos. 
*Syntactic and Semantic accuracy observed.
*Scatterplot was used to check the linear dependencies between features & chance of admit.
*CGPA, GRE, TOEFL attributes had a significant correlation with Target attribute


![Picture2](https://user-images.githubusercontent.com/81937480/202825346-3856ef08-41eb-4777-91bf-a43eb7676a41.png)

##Modeling 
Decided to follow implement both Classification1 & Regression2 algorithms to predict the Target.
1. Classified the Predict attribute into 3 bins & chose the below models.
*Decision Tree
*Naive Bayes
2. Linear Regression fetching better results than Polynomial. 

##Knime-Workflow

![Picture4](https://user-images.githubusercontent.com/81937480/202825460-367b9ba4-c319-4360-89b9-7bf18a692a31.png)

##Conclusion
#The classification models failed to give an exact prediction because the target feature is not a categorical attribute.
#The best model to predict the chance of admit(having continuous values) proved to be possible by “Linear Regression”.
#Linear Regression model gives an exact, precise numerical value for the chance of admit.



