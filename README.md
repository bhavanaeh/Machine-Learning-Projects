# Machine Learning Projects
My attempt at learning machine learning by building basic projects.

![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)

# Breast Cancer Detection
- This is a pretty simple data set: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/breast-cancer-wisconsin.data
- Using 10 features of biopsy, classifiying whether it is cancerous(malignant or benign tumor) or not. 
- Used the pandas library to explore and prepare the data. 
- Plotted the distributions and correlation matrixes of each feature.
- Used K-nearest neighbors and suppor vector machine classifier
- Got an accuracy of 98% for the KNN model

# Credit Card Fraud Detection
- The dataset can be downloaded from kaggle.com (https://www.kaggle.com/mlg-ulb/creditcardfraud?select=creditcard.csv) 
- compares the effectiveness of outlier-detection methods using credit card transactional data.
- anomaly detection by using probability densities.
- precision score for LOF when it cames to identifying the fraudulent cases is pretty bad: 0.02 probably could identify only one accurately
- Isolation forest based on the random forest method has shown better results comparetively.Almost 30% of the time it has been succesful to detect the anomaly that is the fraud.
- I could improve my results if I took a larger sample of data, but that would be computationally expensive