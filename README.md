# machine learning regression model to predict the solubility of chemical compounds (logS) using molecular descriptors.
First Machine Learning Model – Solubility Prediction

 Introduction
This project demonstrates the end-to-end process of building a Machine Learning Regression Model to predict the aqueous solubility (logS) of chemical compounds. It uses molecular descriptors as input features and applies a supervised learning approach to evaluate prediction accuracy.

 Dataset
Source: Delaney Solubility [Dataset](https://github.com/dataprofessor/data/blob/master/delaney_solubility_with_descriptors.csv) 

Target Variable: logS (solubility of compounds)

Features: Multiple molecular descriptors describing each compound

 Methodology:

Data Loading & Exploration

Imported the dataset using pandas
Separated target (y = logS) and features (X)

Data Preparation

Split dataset into training (80%) and testing (20%) sets using train_test_split

Model Building

Applied Linear Regression model from scikit-learn
Model Evaluation
Evaluated using:R² Score (coefficient of determination),Mean Squared Error (MSE),Compared predicted vs actual solubility values

 Results

The model achieved a reasonable prediction accuracy (based on R² and MSE values).
Visualization confirmed a close alignment between predicted and actual solubility.

 Conclusion

This project illustrates the basic ML workflow:

Loading data
Preparing features & targets
Training a regression model
Evaluating performance with metrics & visualization

It serves as a beginner-friendly introduction to Machine Learning using scikit-learn.
