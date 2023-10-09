# Heart Attack Prediction Mini Project 
This mini project focuses on Heart Attack Prediction using two machine learning models: Decision Tree and Logistic Regression. The analysis utilizes a heart attack dataset containing various features and attributes related to individuals who have experienced heart attacks.

## Project Description
The goal of this project is to predict the occurrence of heart attacks using machine learning models. The heart attack dataset includes features such as age, gender, cholesterol levels, blood pressure, and other medical indicators, which serve as the foundation for training and evaluating the predictive models.

## Models Used
1. **Decision Tree Model:**
   - Decision trees are versatile machine learning algorithms that handle both categorical and numerical data. They construct a tree-like structure by partitioning the dataset based on available features to predict the occurrence of heart attacks.

2. **Logistic Regression Model:**
   - Logistic regression is a statistical technique used to predict binary outcomes. It examines the relationship between input variables and the prediction of heart attacks.

## Workflow
1. **Loading and Preprocessing Data:**
   - The workflow begins with loading the dataset using a CSV Reader, handling missing values, and selecting informative features.
  
2. **Model Training and Testing:**
   - The dataset is partitioned into training and testing sets.
   - Both the Logistic Regression and Decision Tree models are trained using the training set.
   - The Predictor node generates predictions on the testing set.

3. **Model Evaluation:**
   - The Scorer node evaluates the models' performance by assessing accuracy.

## Model Performance
- **Logistic Regression Model:**
  - Achieved an impressive accuracy of 94.43%, indicating its effectiveness in predicting heart attacks.

- **Decision Tree Model:**
  - Achieved an accuracy of 91.038%, showcasing its strong predictive ability for heart attack prediction.

## Model Comparison
- The Logistic Regression model outperformed the Decision Tree model with a higher accuracy of 94.43% compared to 91.038%. This suggests that Logistic Regression was slightly more effective in predicting heart attacks based on the given dataset.

## Scatter Plot
- A scatter plot was used to visualize the positive correlation between the "oldpeak" variable and the predicted output column in the heart attack dataset. Higher values of "oldpeak" were associated with an increased likelihood of a heart attack, indicating its importance as a risk factor in predicting heart attacks.

