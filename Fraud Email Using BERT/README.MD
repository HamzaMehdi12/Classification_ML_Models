# Fraud Email Using BERT Classification
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
