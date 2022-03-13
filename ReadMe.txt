
Fake News Prediction using Classifiers

In this project, we have used various natural language processing techniques and machine learning algorithms to classify fake news articles using sci-kit libraries from python.

Getting Started
These instructions will get you a copy of the project up and running on your local machine for model testing purposes.
Prerequisites
* Python 3.6
1. This setup requires that your machine has python 3.6 installed on it. you can refer to this url https://www.python.org/downloads/  to download python. Once you have python downloaded and installed, you will need to setup PATH variables (if you want to run python program directly, detail instructions are below in how to run software section). To do that check this: https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/ . Setting up PATH variable is optional as you can also run program without it and more instructions are given below on this topic.
2. Second and easier option is to download anaconda and use its anaconda prompt to run the commands. To install anaconda, check this url https://www.anaconda.com/download/ 

* Dataset used - https://www.kaggle.com/¶
The data source used for this project is news article dataset which contains 2 files with .csv format for test and train. Below is some description about the data files used for this project.
Dataset Description
train.csv: A full training dataset with the following attributes:
* id: unique id for a news article
* title: the title of a news article
* author: author of the news article
* text: the text of the article
* label: a label that marks the article as potentially fake/real
* 1: fake
* 0: real
test.csv: A testing training dataset with all the same attributes at train.csv without the label.

File description:
--Code.ipynp
This file contains the source code of the project.

 If you want to run the code follow the belowsteps.
Open the command prompt and change the directory to project folder as mentioned in above by running below command
cd <your cloned project folder path goes here>/Code
run below command(change the file type from .ipynp to .py)
python <your cloned project folder path goes here>/Code/file_name.py

or open the file in jupitor notebook or spider and execute all the steps one by one.

After hitting the enter, program will run below process step by step:
1. Importing all the required libraries
2. Data Pre-processing and Analysis
a. Loading and exploratory data analysis : visualize the proportion of real and fake news.
b. Visualizing top 10 Authors
c. Checking for missing values
d. replacing the null values with empty strings
e. processing for wordcloud and ngram
f. removing special characters, stopwords, applying Stemming & Tf-IDF
3. Modeling & Model Evaluation
a. Training Model1 : Passive Aggressive Classiifier
b. Training Model2 : Multinomial Naive Bayes
c. Training Model3 : Logistic Regression
d. Training Model4 : Random Forest
e. Training Model5 : Support Vector Machine
f. Comparison of all algorithms Results
4. Making a Prediction with test.csv file


