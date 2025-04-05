 Diabetes Prediction and Data Exploration
This project focuses on exploring, cleaning, and modeling a diabetes dataset using various machine learning algorithms. It provides a complete pipeline from loading and analyzing the data to training and evaluating classification models.

📊 Project Phases
✅ Phase 1: Data Exploration
Loaded the diabetes dataset using pandas.

Displayed summary statistics and dataset structure.

Visualized the distribution of the target variable (Outcome) using pie charts and count plots.

Generated correlation matrices and heatmaps to understand feature relationships.

🧹 Phase 2: Data Cleaning
Identified and handled missing or zero-value entries in key medical fields (e.g., Glucose, BMI, BloodPressure, etc.).

Replaced missing values using median imputation based on the target class (diabetic vs non-diabetic).

Removed extreme outliers and zero-value entries to prepare the dataset for modeling.

🤖 Phase 3: Model Building (Optional - if added later)
Planned to apply multiple classification algorithms (e.g., KNN, SVM, Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, MLPClassifier).

Aim: To evaluate and compare their performance using metrics like accuracy and cross-validation scores.

📁 Dataset
Source: Pima Indians Diabetes Dataset

Features:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Outcome (Target)

🛠️ Libraries Used
pandas, numpy

matplotlib, seaborn

sklearn (for modeling and evaluation)

📌 How to Run
Clone this repository.

Make sure the diabetes.csv file is located in the appropriate path.

Run the Jupyter Notebook or Python script to see the results.

📍 Notes
The dataset contains several zero values in features where zero is not a valid measurement. These are treated as missing values and handled accordingly.

Correlation and distribution plots help guide the feature selection and model design.
