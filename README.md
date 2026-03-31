
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
1 : Loading dependencies - All the libraries that are used in this project is imported.  
                                          2 : Loading the datasets - The two datasets emotion and hate datasets are uploaded.  
3 : Data Preprocessing - Dropping unwanted columns present in the dataset. Checking for null values in the dataset. Extracting equal number of rows from both the datasets.  
4 : Tokenization and Stopwords removal and Padding  - Tokenization is the process of breaking down text into smaller units known as tokens which can be words , phrases or characters.         Stopwords are the words which do not have a valid meaning individually, they are important parts of speech but does not play an important role in NLP tasks. Padding is done to make input sequences the same length within a batch to ensure efficient processing of datas. Post Padding is performed in this project.                                                                       5 : Building the model - The input and the output layers are build separately for both the datasets. The shared layers are Embedding layer, LSTM layer, Global Average Pooling layer and the Dropout layer. 6 : Training the model - The model is trained for 10 epochs with a batch size of 4  
7 : Prediction and Evaluation - The model is evaluated on the basis of accuracy.



                                    
## Final Results

The model is evaluated on the basis of Accuracy and it has achieved an accuracy of 98.78 on Emotion dataset and 99.58 on Hate dataset.