# Alteryx-Machine-Learning-Workflow
This repository demonstrates how to efficiently use Alteryx for machine learning projects, focusing on key features like Assisted Modeling, Auto Field, Imputation, and the Select and Output tools.

Alteryx is a powerful platform that simplifies and accelerates machine learning workflows, making them easier and more efficient. This exercise outlines the steps for retrieving data sets, using Assisted Modeling for model selection, handling missing data, and forecasting exports.Here is a detailed look at how Alteryx Workflows were prepared in the project:


Input
To bring in the training and test datasets

Assisted Modeling
This tool appears under the Machine Learning Tab. Select the “target variable” and Alteryx will recommend the “ML Methods” to choose like Classification, Regression, etc. For this project, I used Classification followed by choosing the “Step-by-Step Automation” Level. Once done, set the “data types” of fields then “Clean Up Missing Values” and replace them with Mean or Median (check the skewness and select accordingly). Finally, select the features that look like a good predictor and run the different suggested “ML Algorithms” and check the accuracy level and add them to the Alteryx Workflow.

Auto Field
Automatically set the correct data types for the fields in the datasets

Imputation
Handles missing data by replacing null values or NaN with mean or median or other specified values.

Select and Output 
Choose, and rename specific fields, and then export the predictions in the favorable format.

