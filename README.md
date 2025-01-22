# Ensemble Model of Random Forest and Support Vector Machine for Detecting Pneumonia Using Protein Sequence Data 
This project implements an ensemble model combining Random Forest and SVM to detect pneumonia using protein sequence data. 

-- Project status: completed.

## Objective
The objective of this project is to develop an ensemble model combining Random Forest and Support Vector Machine using the weighted majority algorithm to detect pneumonia based on protein sequence data.

## Methods Used
1. Random Forest is an ensemble learning method that combines multiple decision trees to improve classification accuracy. In this project, RF is used to classify protein sequence data into categories (pneumonia or not). The model uses bootstrapping and feature bagging to build diverse trees, which then vote on the final classification.
2. Support Vector Machine is a supervised machine learning algorithm used for classification tasks. It works by finding the optimal hyperplane that best separates data points into different classes. In this research, SVM is applied to classify protein sequences and detect pneumonia based on their features.
3. The weighted majority algorithm (WMA) combines multiple models by assigning different weights to each model's prediction. The final prediction is made based on a weighted vote, where models with better performance are given higher weights. This ensemble method is used to combine the predictions of Random Forest and SVM to improve the overall accuracy and robustness of the model.
4. Performance evaluation metrics: accuracy, sensitivity (recall), specificity, and ROC-AUC.
5. Discere for feature extraction from protein sequences.

## Technologies Used
- Python
- scikit-learn
- pandas
- numpy
- matplotlib/seaborn
- Jupyter Notebook
- Google Colab

## Data
The protein sequence data used in this research was obtained from the UniProt website (www.uniprot.org), a comprehensive resource for protein sequence and functional information. UniProt provides a wide variety of data on protein sequences, including detailed annotations, which are essential for bioinformatics research and analysis. In this project, the protein sequences were preprocessed and used to train the ensemble model for pneumonia detection.
