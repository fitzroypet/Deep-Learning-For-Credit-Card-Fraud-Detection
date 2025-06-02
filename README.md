# credit-card-fraud-detection
Using customer’s transaction history to detect fraudulent transactions on Think Pacific's online payment platform. Decision trees, artificial neural networks and logistic regression ML models are used to get the best accuracy. 

## Project Aim
This project aims to design an algorithm that can read input details of a customer's transaction and then classify the transaction as either fraudulent or not fraudulent with high accuracy.

## Project Objectives
•	Use Machine Learning to create a predictive model that is an improvement of the current solution. 
•	Improve Machine Learning solutions with Deep Learning

## Method
To detect fraud, our models should be able to read input details of a customer's transaction and then classify the transaction as either fraudulent or not fraudulent, making it a Binary Classification problem (only two possible outcomes). This binary classification problem is solved by training a machine learning model by exposing it to a dataset containing credit card transactions collected over a period. The dataset amongst other variables (columns) contains one column with a class label for each instance which is either 0 for non-fraudulent or 1 for fraudulent. Model performance is then evaluated by exposing the trained model to detect fraud on new transactions (data excluded during the model training). In this experiment, python language was used to code the binary classification models: Log: Logistic Regression from Scikit-Learn Neural Networks from Tensorflow library. They are then compared to get the best prediction accuracy while avoiding errors such as overfitting and underfitting.
Here is a link to the notebook containing the codes on Kaggle: https://www.kaggle.com/code/fitzroypetgrave/credit-card-fraud-detection-scikit-and-tensorflow 

## Results 
The objective of improving the current machine learning model was fully satisfied with improved performance.
![image](https://github.com/user-attachments/assets/f781ac90-64ea-476d-a89b-2cc7984ad3d6)

The Deep Learning model also gave a high accuracy of 99.99%, which is desirable. However, there is still a chance that it can make a wrong prediction due to the vast difference between the size of the fraud and non-fraud instances.
My recommendation is to optimize this model by resampling the dataset before training the models to have an equal representation of both classes in our training data.

![image](https://github.com/user-attachments/assets/f33a22e3-6b5d-4687-8701-f99c3264d0c7)


[![Open In Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/fitzroypet/credit-card-fraud-detection/blob/master/path/to/notebook.ipynb)
