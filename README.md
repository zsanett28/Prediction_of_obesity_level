# Prediction_of_obesity_level
*Machine Learning project to predict the obesity level of persons based on their lifestyle habits, such as meals, sport activity, smoking or genetic traits.*

## Problem description
Many people from our society moved from traditional foods to high-calorie fast food. They do not do physical activity either, which is driving to the rise of overweight even faster and faster. The more we do not pay attention to our meals and sport activities, the more we risk of developing weight related diseases like diabetes or heart disease. Obesity is already a global problem, but we have a chance to live as a normal weight person, if we find out in time, that we have a tendency to be obese, or if we already have such habits, that ruin our healthy life.

## Dataset
The dataset presents data of a survey for the estimation of obesity levels in people from Mexico, Peru and Colombia, based on their eating habits and physical condition.

### Observations
After analysing the dataset and creating different diagrams, the following observations can be concluded:

* *The average age of people who took this survey is 24 years. The youngest person is 14 years old, and the oldest one is 61 years old.*
* *Most of the survey participants are young, between 19 and 27 years old.*
* *The average weight of the people is 86 kilograms.*
* *The maximum liter of drinked water is 3 liters.*
* *Most of the people do physical activity very rare.*
* *Most of the participants eat 3 times and drink 2 liters of water per day.*
* *The physical activity frequency has in average a lower value, similarly to the use of technological devices.*

## Data preparation
* First step of data preparation was the transformation of categorical features with the help of one-hot encoding and ordinal encoding.
* Next step was creating artificial features, such as BMI index.
* After these steps came the splitting of the data to *train* and *test* datasets.
* Finally the correlation between attributes were inspected as well.

## Classification
The estimation of obesity levels was realized with classification, including **Support Vector Classifier** and **Random Forest Classifier**. These two models were compared during the second part of this project. The used scores for these methods are: Accuracy classification score, Precision score, Recall score.

### Support Vector Classifier
The estimation of this method using accuracy, precision and recall score gave the following values: 0.7257, 0.7417, 0.7269.

### Random Forest Classifier
The estimation of this method using accuracy, precision and recall score gave the following values: 0.9787, 0.9788, 0.9781.

## Conclusion
The confusion matrices and decision boundaries diagrams show that the Random Forest Classifier gives a better prediction than the Support Vector Classifier and the precision score is the best.
