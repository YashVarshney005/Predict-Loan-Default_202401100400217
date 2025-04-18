Loan Default Prediction using Random Forest

This project performs classification on a loan dataset to predict whether a loan will default or not. It includes preprocessing, model training, and evaluation using key classification metrics and visualization.

Objective

Predict loan default (Default column) using various customer and loan-related features.

Use a Random Forest Classifier.

Evaluate the model using:

Accuracy

Precision

Recall

Confusion Matrix (with heatmap)

Dataset

The dataset should be in CSV format and must contain a LoanID column along with features like Age, Income, LoanAmount, CreditScore, and more, ending with a target column named Default.

Example columns include:

LoanID

Age, Income, LoanAmount, CreditScore, MonthsEmployed, etc.

Education, EmploymentType, MaritalStatus, etc.

Default (Target: 0 = No Default, 1 = Default)

How to Run

Open the project in Google Colab.

Upload the CSV file.

The script will:

Preprocess data (encode categorical variables)

Sample 10% of the data for faster training

Train a Random Forest classifier

Output Accuracy, Precision, Recall

Display a confusion matrix as a heatmap

Output

Accuracy, Precision, Recall scores printed in the console.

Heatmap of Confusion Matrix showing predicted vs actual loan default classification.

Requirements

Python libraries used:

pandas

seaborn

scikit-learn

matplotlib
