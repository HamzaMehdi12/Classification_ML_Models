# Objective
This file and folder holds the below mentioned files for classificaiton exaamples using machine learning and deep learning models.

## Fraud_Email_Detection using Naive Bayes
Fraudulent Email Span vs Not Spam detection and classification.


The model uses an Email fraudulent classificaiton approach using machine learning model Multinomial Naive Bayes (Multinomial NB). The following is the summary of the model:

Loads and explores a labeled dataset of emails.
Cleans and preprocesses text data by removing noise and applying normalization.
Converts the text into numerical features using CountVectorizer.
Trains a MultinomialNB classifier on the transformed features.
Evaluates the model using accuracy, precision, recall, and confusion matrix.
Allows predictions on new email samples using the trained classifier.

Following are the source code images of the model.
### Model Accuracy
![alt text](https://github.com/HamzaMehdi12/Classification_ML_Models/blob/main/Fraud%20Email%20Detector/Analysis.png?raw=true)
### Spam Email
![alt text](https://github.com/HamzaMehdi12/Classification_ML_Models/blob/main/Fraud%20Email%20Detector/Fraud_Detection.png?raw=true)
### Not Spam Email
![alt text](https://github.com/HamzaMehdi12/Classification_ML_Models/blob/main/Fraud%20Email%20Detector/Not_Spam.png?raw=true)

### Notebook
Find the notebook below as follows:
https://github.com/HamzaMehdi12/Classification_ML_Models/blob/main/Fraud%20Email%20Detector/Fraud_Email_MNB.ipynb


## Fraud Email Using BERT Classification
The model uses a supervised machine learning tool for email fraud detection. Although th results are poor than naive bayes, the verall supervised algorithm is further to be corrected and made more accurate. The summary is as follows: 

Loads and preprocesses a labeled dataset of emails for binary classification. 
Tokenizes email text using BertTokenizer and prepares it for input into BertForSequenceClassification. 
Splits the data into training and validation sets. 
Defines training logic with gradient accumulation, evaluation metrics, and optimization using AdamW. 
Trains the model over multiple epochs while tracking accuracy, precision, recall, and loss. 
Includes test-time evaluation and prediction on new email examples using the trained model. 
Githib: Fraud Detection BERT. 

Following are the source code and the images:
### Model Accuracy
![alt text](https://github.com/HamzaMehdi12/Classification_ML_Models/blob/main/Fraud%20Email%20Using%20BERT/Accuracy.png?raw=true)
### Model Graphical View
![alt text](https://github.com/HamzaMehdi12/Classification_ML_Models/blob/main/Fraud%20Email%20Using%20BERT/Graphical%20Evidence.png?raw=true)

### Notebook
https://github.com/HamzaMehdi12/Classification_ML_Models/blob/main/Fraud%20Email%20Using%20BERT/Fraud_Email_BERT.ipynb
