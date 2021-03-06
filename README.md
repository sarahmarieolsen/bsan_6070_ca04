# bsan_6070_ca04

**Using Ensemble Models to Predict Income Class**

*Introduction:* In this project, a four different machine learning ensemble algorithms are implemented to predict whether the income of a person is greater than or less than 50k. The data was sourced from the US Census. There are seven categorical independent variables that factor into the outcome of the prediction. The independent variables include capital gain or loss, age, education, occupation, marital status, race and sex, and hours of work per week; the dependent variable, signaling the outcome of the prediction is labeled 'y'. The outcome variable is a binary classifier; if y == 1, then a person is predicted to have an income greater than 50k.

*Process:* First, the data is cleaned and prepared for analysis. This process entails separating the original data into a test set and training set and cleaning characters out of the dummy column names. Next, each algorithm is implemented individually. For each algorithm, we iterate through a list of n_estimators values and plot the accuracy of each n_estimator value. After each model is deployed individually, specific hyperparameters are selected and used on all four algorithms. The accuracy and AUC scores are displayed in a tabular form. You can use the table to quickly compare model performance.

*Instructions:* The data used in this file is publicly available at a github raw url. To run this program, execute each cell in order and the results will be displayed accordingly.
