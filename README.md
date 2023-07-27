# OIBSIP_EmailSpamDetection_with_ML

# Email Spam Detection With Machine Learning 

## Introduction
Email Spam Detector is a Python-based project that aims to distinguish between spam (junk) emails and non-spam (ham) emails using machine learning. The project involves training a model on a labeled dataset of emails and then evaluating its performance. Additionally, the project provides a visualization of the model's classification results.

## Dataset
The dataset used in this project is stored in a CSV file named 'spam.csv'. The file contains two columns: 'v1' and 'v2'. The 'v1' column contains the email labels, where 'ham' represents non-spam emails and 'spam' represents spam emails. The 'v2' column contains the email content.

## Dependencies
To run the code, you need to have the following libraries installed:

- Pandas
- scikit-learn
- Seaborn
- Matplotlib

You can install these libraries using pip:

```bash
pip install pandas scikit-learn seaborn matplotlib
`````
## Steps
1. Import Libraries
2. Import the 'spam.csv' file in the project directory. The CSV file should have the 'v1' and 'v2' columns as described in the Dataset section.
3. Data Preprocessing
4. Split Data into Training and Testing Sets
5. Build the Model
6. Evaluate the Model
7. Cheking it gives correct output or not by taking example
8. Visualization of Dataset

As new data becomes available or to improve the model's performance, you can update the 'spam.csv' file with additional labeled emails and retrain the model using the latest data. Keeping the model up to date is essential for accurate spam detection.
