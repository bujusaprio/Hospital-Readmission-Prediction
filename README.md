# Hospital Readmission Prediction Using Machine Learning

## Project Overview
This project focuses on predicting hospital readmission using patient-related data and machine learning techniques. The notebook explores patient information, performs data preprocessing, and compares classification models to predict readmission outcomes.

## Objectives
- Explore and understand hospital patient data.
- Handle missing values and examine duplicate records.
- Detect and remove age outliers using the Interquartile Range (IQR) method.
- Perform exploratory data analysis and correlation analysis.
- Encode categorical variables for machine learning.
- Train and compare classification models for readmission prediction.

## Dataset
**File:** `hospital_readmissions(2).csv`

The dataset includes patient-related information such as:
- Patient ID
- Age and gender
- Admission type
- Diagnosis
- Number of laboratory procedures
- Number of medications
- Outpatient and emergency visits
- A1C result
- Readmission status

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Data Preprocessing
- Inspected dataset structure and descriptive statistics.
- Checked missing values and duplicate records.
- Removed the Patient ID column because it is not used as a predictive feature.
- Detected age outliers using the IQR method.
- Applied one-hot encoding and label encoding to categorical features.
- Examined correlations between features and readmission status.

## Machine Learning Models
The notebook explores the following classification algorithms:

1. Logistic Regression
2. Decision Tree Classifier
3. Support Vector Machine (SVM)
4. Random Forest Classifier
5. K-Nearest Neighbors (KNN)

Model performance is evaluated using accuracy and classification reports.

## Project Workflow
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory data analysis and visualization
4. Feature encoding and preparation
5. Model training and evaluation
6. Model comparison

## Files
- `RA3.ipynb` — Jupyter Notebook containing the analysis and model implementation.
- `hospital_readmissions(2).csv` — Dataset used for the project.

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open the notebook:
   ```bash
   jupyter notebook RA3.ipynb
   ```
4. Ensure the dataset filename and notebook path match.
5. Run the notebook cells in order.

## Results
The notebook compares several machine learning classifiers for predicting readmission. Refer to the executed notebook for the actual accuracy scores and classification reports.

## Disclaimer
This project is for educational and analytical purposes only. It is not intended to replace professional medical judgment or clinical decision-making.
