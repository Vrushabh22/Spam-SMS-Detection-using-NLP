# Spam-SMS-Detection-using-NLP

The objective of this project is to employ binary classification models for the categorization of spam and ham SMS messages. In this context, an approach to identify spam SMS by employing various supervised machine-learning models and ensembling techniques for model optimization and enhancing message analysis through topic modeling.

The dataset utilized for the development of the spam and ham SMS detection system was compiled from the UCI Machine Learning Repository and accessed via the Kaggle platform. To assess the effectiveness of our approach, we conducted thorough testing and conducted a comparative analysis of the performance exhibited by various classification models across a range of experimental setups. The ultimate goal was to identify the binary classification model that demonstrates the most optimal performance in terms of accuracy and efficacy.

# Dataset Information

This dataset encompasses a total of 5574 message samples, comprising 724 spam messages and 4850 ham messages. These messages are labeled based on their classification as either ham (legitimate) or spam. The collection of these messages was drawn from the realm of mobile phone spam research and was sourced from university students. The input data consist of a file:

1. Sms_Dataset.txt

# Requirements

The project entails both general library prerequisites and specific ones tailored to individual methods. The overarching requirements encompass the following aspects: The general requirements are as follows.

- python 3x
- pandas
- numpy
- scikit-learn
- nltk
- regex
- matplotlib
- collections

The library requirements specific to some methods are:

- xgboost for XGBoost.

Note: It is recommended to use the Anaconda distribution of Python. It already has a lot of prebuild libraries installed.

# Information about files

Sms_Dataset.txt: Dataset utilized.
Spam_detection.ipynb: Contains all the functions, models, and results from the project.
report.pdf: Report of the project.
Readme.docx: Contains instructions to run the python notebook file.

# How to Run the project

To maintain simplicity, I have consolidated all components within a single Python Notebook file. By navigating through the Notebook, each cell contains comprehensive comments  which will help understand the project steps.
