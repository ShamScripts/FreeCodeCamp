# Linear Regression Health Costs Calculator

Welcome to the **Linear Regression Health Costs Calculator** project! In this challenge, you will build a model to predict healthcare costs using a regression algorithm.

## Project Overview
In this project, you will:
- Use a given dataset containing information about different individuals and their healthcare costs.
- Implement a **linear regression model** to predict healthcare expenses based on the features in the dataset.

## Dataset Information
The dataset contains various details about individuals, including:
- Age
- Sex
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Region
- Healthcare costs (expenses)

## Steps:

1. **Setting up Google Colaboratory Notebook**:
   - Open the provided [Google Colaboratory link](#) and create a copy in your Google Drive or download it for local use.
   - Complete the tasks as described in the notebook, following the instructions provided for each code cell.

2. **Data Preprocessing**:
   - The first two cells will import the necessary libraries and load the dataset.
   - **Categorical Data Conversion**: Ensure that any categorical data (e.g., sex and region) is converted into numeric values that the model can process.
   - **Dataset Splitting**: Split the data into:
     - **Training Set (80%)**: This will be used to train the model.
     - **Test Set (20%)**: This will be used to evaluate the model's performance.
   - **Create Labels**: Remove the `expenses` column from both datasets and create new datasets (`train_labels` and `test_labels`) to be used as labels for training the model.

3. **Building the Model**:
   - **Model Creation**: Use a regression model, likely **Linear Regression**, to fit the training data and predict the healthcare costs based on the features.
   - **Model Training**: Train the model with the training dataset (`train_dataset`).
   
4. **Model Evaluation**:
   - Once the model is trained, use `model.evaluate` to evaluate the model's performance on the test dataset.
   - To pass the challenge, ensure that the **Mean Absolute Error (MAE)** is **under 3500**. This means that the model should predict healthcare costs within a $3500 margin of error.

5. **Prediction and Graphing**:
   - The final cell will use the model to predict healthcare costs on the test dataset.
   - The results will be visualized using a graph to compare predicted expenses vs. actual expenses.

## Submission:
- Once you complete the project and pass the test, submit your project by sharing the link to your Google Colaboratory notebook (ensure link sharing is enabled for "anyone with the link").
- If submitting a local copy, ensure the project is hosted on GitHub and provide the link.

## Goal:
- The ultimate goal is to build a linear regression model that predicts healthcare costs with a **Mean Absolute Error (MAE)** of **less than 3500**.

