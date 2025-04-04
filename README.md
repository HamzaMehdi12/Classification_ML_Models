# Objective
This file and folder holds the below mentioned files for classificaiton exaamples using machine learning and deep learning models.

## Fraud_Email_Detection using Naive Bayes
Fraudulent Email Span vs Not Spam detection and classification.


The model uses an Email fraudulent classificaiton approach using machine learning model Multinomial Naive Bayes (Multinomial NB). The following is the summary of the model:

Detects fraudulent emails using Multinomial Naive Bayes ML model
Preprocesses text by removing URLs, numbers, and punctuation
Uses CountVectorizer to convert text into numerical features
Achieves 100% accuracy in the example (potential overfitting warning)
Supports PDF text extraction via PyPDF2 and pdfplumber
Includes interactive tkinter GUI for email input and classification
Visualizes scam/non-scam distribution with seaborn
Fixed issues with PDF extraction and text cleaning
Resolved GUI variable scope problems
Key libraries: pandas, sklearn, tkinter, PyPDF2, seaborn
Note: High accuracy suggests need for real-world validation

Following are the source code images of the model.
### Model Accuracy
![alt text](https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Fraud_Email_Detector/Fraud_em.png?raw=true)
### Spam Email
![alt text](https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Fraud_Email_Detector/Email%20Scam.png?raw=true)
### Not Spam Email
![alt text](https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Fraud_Email_Detector/Not%20Scam.png?raw=true)
### Classification model
![alt text](https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Fraud_Email_Detector/Email_Spam_Classification.png?raw=true)

### Notebook
Find the notebook below as follows:
https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Fraud_Email_Detector/Fraud_Email.ipynb


## Animal Kingdom clssification using Naive Bayes
