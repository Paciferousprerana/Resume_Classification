# Resume Classification using Naive Bayes

## Objectives

The project aims to categorize resumes into different classes based on their content using the Naive Bayes classifier.
* perform data preprocessing, EDA and feature extraction on the Resume dataset
* perform multinomial Naive Bayes classification on the Resume dataset

## Project Overview
The resume classification project focuses on categorizing resumes into specific classes or categories using TFID concept. The Naive Bayes algorithm is a popular choice for text classification tasks due to its simplicity and effectiveness. It assumes that the features (words or phrases) in the input data are independent, which allows for fast and efficient classification.

## Dataset description

The data is in CSV format, with two features: Category, and Resume. 

**Category** -  Industry sector to which the resume belongs to, and 

**Resume** - The complete CV (text) of the candidate.

*(Download the data using the link given in the notebook)

## Project Setup
Follow the steps below to set up the project:

1. Clone the project repository or download the project files to your local machine.

2. Open it in Jupyter notebook or Google Colab.

3. Install the required dependencies. (Included in the notebook)

## Usage
1. Open the Python script.

2. Customize the code to read and preprocess the training data. This may involve tokenizing the resumes, removing stop words or punctuation, and converting the text into numerical features that can be fed into the Naive Bayes classifier.

3. Train the Naive Bayes classifier using the preprocessed training data. Split the data into training and testing sets to evaluate the performance of the classifier.

4. Once the classifier is trained, you can use it to predict the category of new, unseen resumes. Customize the code to read and preprocess the new resumes, and then use the trained classifier to predict their categories.

5. Evaluate the performance of the classifier by comparing the predicted categories with the true categories of the test resumes. You can use various evaluation metrics such as accuracy.

6. Experiment with different preprocessing techniques, feature extraction methods, or hyperparameter tuning to improve the performance of the classifier.

## Troubleshooting
* Make sure the training data is properly labeled.

* Consider handling edge cases, such as resumes with no content or resumes that do not fit into any of the defined categories.
