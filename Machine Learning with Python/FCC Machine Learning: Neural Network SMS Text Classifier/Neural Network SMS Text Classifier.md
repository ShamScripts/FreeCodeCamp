# Neural Network SMS Text Classifier

Welcome to the **Neural Network SMS Text Classifier** project! In this challenge, you will create a machine learning model to classify SMS messages as either **"ham"** (a normal message) or **"spam"** (an advertisement or unwanted message).

## Project Overview
In this project, you will:
- Use the **SMS Spam Collection dataset**, which contains labeled SMS messages.
- Build a **Neural Network model** that will classify SMS messages as either "ham" or "spam".
- Implement a function called `predict_message` to predict whether a given message is "ham" or "spam".

## Dataset Information
The dataset contains SMS messages that have been labeled as either "ham" (normal messages) or "spam" (advertisements or unsolicited messages). The data is already pre-split into:
- **Training Data**: Used to train the machine learning model.
- **Test Data**: Used to evaluate the model's performance.

## Steps:

1. **Setting up Google Colaboratory Notebook**:
   - Open the provided [Google Colaboratory link](#) and create a copy in your Google Drive or download it for local use.
   - Complete the tasks as described in the notebook, following the instructions provided for each code cell.

2. **Data Preprocessing**:
   - The first two cells will import the necessary libraries and load the dataset into your notebook.
   - Preprocess the data by:
     - **Cleaning** the SMS messages (removing punctuation, stop words, etc.).
     - **Vectorizing** the text data to convert the messages into numerical representations that the model can understand.

3. **Building the Model**:
   - Create a **Neural Network model** that can be trained on the SMS dataset to classify messages as "ham" or "spam".
   - Train the model using the training dataset.

4. **Prediction Function**:
   - Create a function named `predict_message` that:
     - Takes a message string as input.
     - Returns a list containing:
       1. A number between **0 and 1** that indicates the likelihood of the message being "ham" (0) or "spam" (1).
       2. The word "ham" or "spam", depending on which category is more likely.

5. **Model Evaluation**:
   - Once the model is trained, test it using the **test dataset** and evaluate its performance.
   - Ensure that the model correctly classifies messages as either "ham" or "spam" based on the likelihood.

6. **Testing**:
   - The final cell will test your model and function to check how well your classifier performs.
   - Use various SMS message samples to check the accuracy of the model's predictions.

## Submission:
- After completing the project and passing the tests, submit your project by sharing the link to your Google Colaboratory notebook (ensure link sharing is enabled for "anyone with the link").
- If submitting a local copy, ensure the project is hosted on GitHub and provide the link.

## Goal:
- The ultimate goal is to build a **Neural Network model** that can accurately classify SMS messages as either "ham" or "spam" based on their content.

Good luck and happy coding!
