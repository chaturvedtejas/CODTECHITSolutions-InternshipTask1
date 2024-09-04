# CODTECHITSolutions-InternshipTask1

_Name:_ M CHATURVED TEJAS

_Company:_ CODTECH IT SOLUTIONS

*ID:* CT6AI335

*Domain:* ARTIFICAL INTELLIGENCE

*Duration:*  from JULY 20th, 2024 to SEPTEMBER 5th, 2024.

*Mentor:* MUZAMMIL AHMED

**Overview**
This repository provides a script for evaluating and comparing the performance of different machine learning models on a given dataset. The primary goal is to automate the process of model selection and evaluation, helping to determine the most effective model for solving a particular problem.

**Features**

**Data Loading and Preprocessing:**
The script loads data from a CSV file and preprocesses it by encoding categorical variables into numeric format.
The data is then split into features (X) and target labels (y).
Model Training with Hyperparameter Tuning:

**The script supports multiple machine learning models, including:**
LogisticRegression
RandomForestClassifier
Support Vector Classifier (SVC)
Hyperparameter tuning is performed using GridSearchCV to find the optimal parameters for each model.
Model Evaluation:

**After training, each model is evaluated on a test set using various metrics:**
Accuracy
Precision
Recall
F1 Score
Area Under the Curve (AUC)
Confusion Matrix
These metrics are printed out for each model, allowing for easy comparison.

**Usage**
**Clone the repository:**
git clone 
cd model-evaluation-comparison

**Ensure you have the required libraries installed:**
pip install -r requirements.txt
Place your dataset (RawData.csv) in the root directory of the project.

**Run the script:**
python model_comparison.py

**View the output:**
The script will output the best hyperparameters and evaluation metrics for each model, helping you choose the best-performing one.

**CONCULSION**
This project sets up a very strong platform for not just evaluating but also comparing many different machine learning models on a particular dataset. By using the automated hyperparameter tuning and model evaluation process, it becomes easy to determine the most suitable model for a specific problem. Thanks to its flexibility, this script provides users with the opportunity to either append more models or modify the hyperparameters to make it either a beginner-level or an experienced practitioner-level tool for machines learning. Moreover, it is very helpful for everyone.

RehumanizeIn the end, this method guarantees that the model, which has been selected, is not only trained but also evaluated in detail with respect to multiple metrics. Hence, this leads to more informed decisions and better-performing solutions.

**Output**
![Screenshot 2024-09-04 165418](https://github.com/user-attachments/assets/d7396b08-0a43-4466-a4d9-499a7b6ed298)
