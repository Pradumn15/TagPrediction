# Stack Overflow Questions Tag Prediction

Built a Machine Learning model to identify the Tags associated with the questions asked on StackOverflow.

## Dataset

Source: https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data 

All of the data is in 2 files: Train and Test.

Train.csv contains 4 columns: Id,Title,Body,Tags

Id - Unique identifier for each question
Title - The question's title
Body - The body of the question
Tags - The tags associated with the question (all lowercase, should not contain tabs '\t' or ampersands '&')
Test.csv contains the same columns but without the Tags, which you are to predict.

The questions are randomized and contains a mix of verbose text sites as well as sites related to math and programming. The number of questions from each site may vary, and no filtering has been performed on the questions (such as closed questions).
