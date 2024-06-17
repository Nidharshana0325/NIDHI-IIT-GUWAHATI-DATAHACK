# NIDHI-IIT-GUWAHATI-DATAHACK
This is my submission for the data hack conducted by GeeksForGeeks and IIT Guwahati.
🚀Project Objective:
The goal of this project is to predict the likelihood that individuals received two types of vaccines: the xyz flu vaccine and the seasonal flu vaccine. This is a multilabel classification problem where we predict two probabilities for each individual: one for each type of vaccine.

🚀Dataset Description
The project uses three datasets:
📊Training Set Features: Contains 35 features describing respondents.
📊Training Set Labels: Contains the target labels indicating whether each respondent received the xyz and seasonal vaccines.
📊Test Set Features: Contains the same 35 features for a separate set of respondents, without the target labels.

Steps :
📊Load the Test Set Features: Ensure you have the test set features loaded into a DataFrame.
📊Preprocess the Test Set: Apply the same preprocessing steps used for the training set to the test set.
📊Predict Probabilities: Use the trained models to predict probabilities for xyz_vaccine and seasonal_vaccine and calculate ROC AUC scores for validation set
📊Create the Submission DataFrame: Combine respondent_id from the test set with the predicted probabilities into a new DataFrame.
📊Save to CSV: Save this DataFrame as a CSV file 

🚀Key Points
Preprocessing: Handling missing values and encoding categorical variables.
Model Training and Evaluation: Using logistic regression and evaluating with ROC AUC scores.
Submission Preparation: Generating the final CSV file in the required format for submission.
This end-to-end approach ensures that all steps from data loading to submission preparation are covered systematically, leading to a robust predictive model for vaccine reception probabilities.
