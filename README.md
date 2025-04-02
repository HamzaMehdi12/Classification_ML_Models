# Fraud_Email_Detection
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
## Model Accuracy
![alt text](https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Fraud_em.png?raw=true)
## Spam Email
![alt text](https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Email%20Scam.png?raw=true)
## Not Spam Email
![alt text](https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Not%20Scam.png?raw=true)

## Notebook
Find the notebook below as follows:
https://github.com/HamzaMehdi12/Fraud_Email_Detection/blob/main/Fraud_Email.ipynb
