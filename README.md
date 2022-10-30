# Predicting the number of insurance benefits for a new customer
The project from the Linear Algebra sprint of the Practicum DS course.

## Description
Here we have a dataset on insurance company clients. Our goal is to explore groups of similar customers and build a model for predicting the number of insurance benefits a new customer will likely receive.

First, we should do some data preprocessing: clean the data, fill in the missing values (if any), and change data types. Next, we need to scale and encode the data. Afterward, we could proceed to models development.

## Conclusion
After preprocessing, we explored several tasks: 
1. Classification of customers using the KNN method with different distance metrics. We saw that scaling is necessary for this algorithm.
2. Predicting if `insurance_benefits` is more than zero like a binary classification task; KNN gives much better results than a dummy model.
3. Prediction of insurance benefits number with a linear regression model.
4. Exploring the possibilities of data obfuscation for the regression model. We ensured that the masked data gave the same result as the raw.