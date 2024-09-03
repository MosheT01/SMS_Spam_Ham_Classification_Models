# SMS Spam Ham Classification Models

This project aims to classify sms as either spam or ham (non-spam) using various machine learning techniques. The primary objective is to investigate the factors that affect the accuracy of specific classification algorithms in detecting spam smss.

## Project Structure

- **data/**: Contains datasets of sms labeled as spam or ham, used for training, testing, and evaluation.
- **SpamHamRevisted;TheRemaster/**: Contains the main notebook (`remaster.ipynb`) with updated experiments and techniques for sms classification.

### Model Training

Use the notebooks or the training scripts to build and train classification models.


### Evaluation

Evaluate the trained models using the test data and generate performance metrics such as accuracy, precision, recall, and F1-score.



## Notebook Overview

### Remaster.ipynb

The `remaster.ipynb` notebook focuses on:

- **Goal**: Investigating the parameters and factors that affect the performance of classification algorithms for spam detection.
- **Data Extraction**: Functions to read and extract sms content from various directories containing ham and spam smss.
- **Preprocessing**: Techniques such as text normalization, stopword removal, and tokenization.
- **Feature Engineering**: Use of TF-IDF to convert text data into numerical format suitable for model training.
- **Model Training**: Implementation of machine learning models like Naive Bayes, Decision Tree, and SVM to classify smss.
- **Evaluation**: Analysis of models using confusion matrices, precision, recall, and accuracy metrics.
- **Visualizations**: Use of plots and charts to interpret the performance of the models.

## Results

- **Performance Metrics**: Detailed analysis of model performance using precision, recall, and F1-scores.
- **Sample smss**: Random examples of spam and ham smss to visualize the classification results.
- **Confusion Matrices**: Visualization of the model predictions compared to actual labels.

## Contact

For questions or feedback, please contact `mousatams@hotmail.com`.
