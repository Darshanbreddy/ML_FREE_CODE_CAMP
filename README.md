# ML_FREE_CODE_CAMP

What is Machine Learning: The ability of computer to learn from data with the use of algorithms, without the programer telling the computer what excatly to do(explicit programming)

TYPES OF ML: Supervised- The input will have corresponding output labels, Training the models to learn the output.
Unspuervised-Unlabled data to learn the patterns in the data.
Reinforcement learning- Agent(computer) learning in environment based rewards and penalties.

Qualitative Data: Categorical data, eg: gender, different countires. This is nominal data which means the no inherit order( we can't say USA is 1, India is 2), To feed it into our computer we can use one hot encoding. What is one hot encoding: Converting a nominal data to computer understanding data(numbers), if it matches a category make it a 1 or else make it 0 for eg:(male 0, female 1). There is also ordinal data which inherit values for example ratings from 1-5

Quntitaive data: Numerical data, which can be continuoues or discret. 

SUPERVISED LEARNING:

1: Classification- predict discret classes( wheather it is a hot dog or pizza or burger) this is also multiclass classification. Binary classficiation is predicting whether it is hotdog or not. 

2: Regression- Predict countiounes values like price of stock, temperature of tomorrow.

METRICS OF PERFORMENCE:

True Positive (TP) – Predicted positive and actually positive.
False Positive (FP) – Predicted positive but actually negative.
True Negative (TN) – Predicted negative and actually negative.
False Negative (FN) – Predicted negative but actually positive.

A quick memory trick:
First word (True/False) → Was the prediction correct?
Second word (Positive/Negative) → What was the predicted label?
LOSS- Diffrence between predicited value and actual values

ACCURACY-THe actaul % of values model got right.
1. Precision – Of all the samples predicted positive, how many were actually positive?
2. Recall – Of all the samples that are actually positive, how many did I correctly predict as positive?
3. F1 Score – Harmonic mean of Precision and Recall, balancing both.

CLASSIFICATION ALGO:

KNN algorithm: If it is a binary classification we need a distance so we can use eculidan distance. What is K it is how many nebhiours are using to jurdge what the class is.

Naive Bayes: It is a simple, fast, and surprisingly effective machine learning algorithm used for classification — deciding which “category” something belongs to. It’s based on Bayes’ Theorem, which is about updating your belief when you get new evidence.

Logistic Regression: It is a way for a computer to predict a yes/no outcome based on some information (features). It doesn’t give just “yes” or “no” — it first gives a probability, then decides yes/no based on that. Sigmod function

SVM: It is a machine learning algorithm that tries to separate data into classes by drawing the best possible boundary between them. In 2D it is a line, In 3D it is a plain

REGRESSIO ALGO:

Residual/ Error: How far off is the prediction from the data point we already have.

Linear Regression.ipynb file explanation(Dataset Creation & Visualization Generates a synthetic dataset (House Size → Price) with realistic noise. Plots the data points so you can visually understand the relationship.

Gradient Descent Intuition
Explains slope direction:
Positive slope → decrease it.
Negative slope → increase it.
Shows cost decreasing as we move towards the global minima.

Finding the Best Fit Line: Runs Gradient Descent for multiple epochs until it converges. Plots the final regression line over the dataset.

R² (Coefficient of Determination), Calculates R² for a model with one feature, Adds a correlated feature and shows how R² increases, Adjusted R², Adds a random (useless) feature to show how R² can still increase. Calculates Adjusted R² to demonstrate how it penalizes useless features.)






