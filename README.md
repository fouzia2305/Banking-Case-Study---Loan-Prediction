# Predicting Loan Approval Status Using Machine Learning

## Project Overview
This project aims to predict loan approval status using a Random Forest classifier. The trained model and preprocessor are saved for real-time prediction based on input data.

## Dataset
The dataset includes features related to loan applicants such as:
- Age
- Income
- Employment length
- Loan amount
- Interest rate
- Home ownership
- Loan intent
- Loan grade
- Credit history length
- Default history

## Project Steps

### 1. Data Loading and Exploration
- Load the dataset.
- Identify and handle duplicates and missing values.
- Conduct univariate and bivariate analysis to understand feature distributions and relationships.

### 2. Data Preprocessing
- Impute missing values with median values.
- Identify and handle outliers.
- Encode categorical variables and scale numerical features.
- Split the dataset into training and testing sets.
- Apply SMOTE to address class imbalance.

### 3. Model Training
- Train several classification models including K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machine (SVM), Decision Tree, and Random Forest.
- Evaluate model performance using accuracy and confusion matrices.

### 4. Model Saving
- Save the trained Random Forest model and the preprocessor using `joblib`.

### 5. Real-Time Prediction
- Create a function to load the saved model and preprocessor.
- Make predictions based on input data and provide approval status.

## Conclusions
- **Random Forest** showed the highest accuracy among all models, indicating its effectiveness in handling loan approval predictions.
- The **preprocessor** ensures that the input data is consistently prepared for accurate predictions.
- Real-time predictions can be made efficiently using the saved model and preprocessor, aiding in quick decision-making for loan approvals.
