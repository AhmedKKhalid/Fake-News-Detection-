# Fake News Detection Classification Project
* the project is for data science Fraud Detection Classification problem to know if the News Fake or Real .
* Data Analysis .
* Machine Learning 
* Choosing the best model 
* Evaluation Matrix

# Libraries
* pandas  
* matplotlib 
* seaborn 
* sklearn

# EDA
![](https://github.com/AhmedKKhalid/Fake-News-Detection-/blob/main/Screenshots/1.PNG) ![](https://github.com/AhmedKKhalid/Fake-News-Detection-/blob/main/Screenshots/2.PNG)


# Model Building
* First,I also split the data into train and tests sets with a test size of 20%.
* Second , I vectorized the texts in data-set
* Third, I Used GridSearchCV to define the best model with the best parameters 
* finally, I used confusion matrix and classification report to measure the performance of my model

I tried 4 different models 
 * Random Forest 
 * Logistic Regression
 * Naive Bayes
 * Decision Tree 

# Model performance
 * Random Forest : score = 0.8721361939753617 
 * Logistic Regression : score = 0.9360687784637971
 * Naive Bayes (Multinomial) : score = 0.7847290937730607
 * Decision Tree : score = 0.8137344696460802 
