# Naïve-Bayes-Classifier-for-YouTube-Comments

## Project Overview
This project focuses on the application of a Naïve Bayes Classifier to analyze a dataset of YouTube comments. The objective is to build a predictive model that can classify comments as either "Ham" (non-spam) or "Spam." This analysis provides valuable insights into classifying comments and can be used for comment moderation on YouTube.

## Project Objectives
The primary objectives of this project are as follows:

1. Data Preparation: Import and preprocess the YouTube comments dataset.
2. Text Classification: Utilize the Multinomial Naïve Bayes Classifier to classify comments as "Ham" or "Spam."
3. Evaluation: Assess the performance of the classifier using metrics such as precision, recall, and F1-score.
4. Visualization: Create visualizations to better understand the distribution of comments and prediction probabilities.

## Methodology
The project follows a structured methodology:

#### Data Import and Preprocessing
- Import necessary libraries for data manipulation and machine learning.
- Read multiple CSV files containing YouTube comments and remove irrelevant columns.
  
#### Text Vectorization
- Use the CountVectorizer from scikit-learn to convert text comments into numerical features.
- Split the dataset into training and testing sets for model development and evaluation.

#### Multinomial Naïve Bayes Classification
- Implement the Multinomial Naïve Bayes classifier from scikit-learn.
- Fit the classifier to the training data to learn the patterns in the comments.

#### Model Evaluation
- Evaluate the classifier's performance on the testing dataset using metrics such as precision, recall, and F1-score.
- Create a confusion matrix display for a visual representation of classification results.

#### Probability Distribution Visualization
- Generate probability distribution figures to understand how the classifier predicts "Ham" and "Spam" comments.
- Visualize the predicted probability of comments belonging to each class.

#### Dataset Description
The dataset contains YouTube comments and includes the following variables:

- CONTENT: The text of the YouTube comment.
- CLASS: The class label, where 1 represents "Spam" and 0 represents "Ham."

## Results
The Naïve Bayes Classifier achieved promising results in classifying YouTube comments as "Ham" or "Spam." The classifier's performance was evaluated using precision, recall, and F1-score, showing a high level of accuracy in distinguishing between the two classes.

## Making Predictions
The classifier can also be used to make predictions on new data. In the example provided, predictions were made for two comment samples, and the classifier correctly classified them as "Ham" and "Spam."

## Production Dataset and Output File
#### Production Dataset: 
For the production phase, a separate dataset named "YoutubeProductionSet.csv" was used. This dataset contains new YouTube comments that need to be classified. 

#### Output File: 
The results of the classifier, including the predicted class labels, were saved to a new CSV file named "NewData.csv" for further analysis and use.

## Credits
This project was implemented by Aleksandar Dimitrov and is licensed under the MIT License. If you have any questions or comments, please feel free to contact me at alexi.zein@gmail.com.






