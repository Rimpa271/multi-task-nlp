
# Multi-Task NLP model using LSTM : Detect emotion and hate from text

Multi-Task NLP model is a Machine Learning model that is trained simultaneously on related tasks.


## Problem Statement
This Multi-Task NLP model is capable of taking inputs separately for every task and produces the output separately too with a shared LSTM architecture.   
Task 1 : Emotion detection from text

Task 2 : Hate detection from text



## Dataset

The two datasets are collected from the Kaggle website that are publicly available.

1. Emotion dataset : https://www.kaggle.com/datasets/nelgiriyewithana/emotions

Total of 6 labels:  
0 : Sadness  
1 : Joy  
2 : Love  
3 : Anger  
4 : Fear  
5 : Surprise

2. Hate dataset : https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset

Total of 3 labels:  
0 : Hate speech  
1 : Offensive speech  
2 : Neither
## Tools and Technologies

Libraries used :  
1 : numpy  
2 : pandas  
3 : nltk  
4 : scikit-learn  
5 : tensorflow  
6 : seaborn  
7 : matplotlib
## Project Architecture

## Steps
1 : Loading dependencies                                          2 : Loading the datasets
3 : Data Preprocessing
4 : Tokenization and Stopwords removal and Padding                5 : Building the model
6 : Training the model
7 : Prediction and Evaluation




## Final Results

The model is evaluated on the basis of Accuracy and it has achieved aa accuracy of 98.78 on Emotion dataset and 99.58 on Hate dataset.