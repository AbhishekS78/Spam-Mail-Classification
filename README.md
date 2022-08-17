# Spam-Mail-Classification
A classifier in Python using classification algorithms of Machine Learning to detect if a given mail is spam or ham. Mail dataset was loaded from Kaggle.
Building a spam email classifier using Naive Bayes Classifier, SVM and logistic regression and compare their performances to choose best suitable algorithm.

## Project Name: 
Spam Mail Classification

## Project Description: 
In this project, I'll create a spam email classifier that analyses an email's content to determine if it's spam or not. After preprocessing the email content, I will use three machine learning algorithms—Naive Bayes, logistic regression, and support vector machine—to train our dataset for email categorization. I can get the optimal model for these algorithms by adjusting the parameters in them. I will compute some evaluation matrices when we receive the training results from the training set so that we may discuss them and assess our models.

## Dataset: 
I do not own the data set the data is taken from [Kaggle](https://www.kaggle.com/datasets/venky73/spam-mails-dataset/code)

## Project Workflow:
- Clean up the data set. Our dataset is from https://www.kaggle.com/datasets/venky73/spam-mails-dataset/code
- Preprocessing emails using NLTK toolkit
- Build a word vocabulary, including counting the word frequency in the dataset
- Feature extraction, using TF-ITF vectorization. Choose appropriate features for classification
- Train the data (Use Naive Bayes, logistic regression and support vector machine models one by one)
- Test our parameters for test set, and get results.
- Calculate some evaluation matric to judge our model, such as precision, recall, F1-score and so on.
- Conclude and discuss the results

## Code: 
The coding was done on [Google Colaboratory Notebook](https://colab.research.google.com/drive/18727vunSHbAD7dOVd1Gu7LpqgIZISHuy?usp=sharing) as it provides pre-installed libraries for machine learning. 

