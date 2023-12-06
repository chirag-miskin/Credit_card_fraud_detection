# Credit_card_fraud_detection
Credit Card Fraud Detection using Logistic Regression 
* Name - Chirag Miskin 
* Project - Credit Card Fraud Detection 
* Skills - Logistic regression , Support Vector Machine, K Nearest Neighbours, F1 Score, ROC-AUC Curve, Data Visualisation , Exploratory Data Analysis , Data Science application in Finance , Machine Learning 
* Tools - Google Colab , Jupyter Notebooks , Python , Numpy , Pandas , Matplotlib , Seaborn , Sklearn 


## The Dataset :

The data was taken from Kaggle site : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud .

The Columns do not have physical significance directly visible since as per the source (Kaggle) , the data was compressed using Principle Component Analysis (PCA) in order to protect the privacy of the individuals while making a realistic secnario dataset availaible to public . 


### Class Imbalance in dataset :

To cure imbalance , we can use undersampling or oversampling . Here , I have decided to use SMOTE to counter the class imbalance in the dataset . 


### Training the model :


I have trained a Logistic Regression Model here . The model was showing a not converging warning , so I read its documentation and added the code to make it run for 150 iterations . 

### Results :

The F1 score came 0.99 meaning the Classifier is working great . It managed to catch 91 out of 101 frauds , thus preventing frauds 90% of the time . 
The confusion matrix , precision , recall and F1 score has been displayed for your convenience . The confusion matrix readings and the F1 show the success of the project .


