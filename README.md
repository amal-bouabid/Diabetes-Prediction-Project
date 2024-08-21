## Diabetes Prediction Project
### Overview
This project involves building and evaluating machine learning models for predicting diabetes based on various health-related features. The dataset used includes features such as age, gender, hypertension, heart disease, BMI, and glucose levels.

### Dataset
The dataset used in this project is diabetes_prediction_dataset.csv. It includes the following features:

gender
age
hypertension
heart_disease
smoking_history
bmi
HbA1c_level
blood_glucose_level
diabetes (target variable)

### Code Description
#### 1. Load and Explore the Dataset
The code begins by loading the dataset and displaying the first 15 rows, the shape of the dataset, and its information.

#### 2. Extract Numerical and Categorical Columns
It separates the dataset into numerical and categorical columns and prints them.

#### 3. Dataset Statistical Summary
Provides a statistical summary of the dataset and displays the last 5 rows.

#### 4. Data Visualization
Gender Countplot: Visualizes the distribution of genders in the dataset.
Hypertension Countplot: Visualizes the distribution of hypertension cases.
Diabetes Countplot: Visualizes the distribution of diabetes cases.
#### 5. Encode Categorical Variables
Encodes categorical variables such as gender and smoking_history using label encoding.

#### 6. Correlation Matrix Visualization
Computes and visualizes the correlation matrix of the features to understand their relationships.

#### 7. Split the Data into Training and Testing Sets
Splits the dataset into training and testing sets with an 80-20 ratio.

#### 8. Train and Evaluate Logistic Regression Model
Trains a Logistic Regression model and evaluates its performance using accuracy, confusion matrix, and classification report.

#### 9. Train and Evaluate Support Vector Machine (SVM) Model
Trains an SVM model with a linear kernel and evaluates its performance.

#### 10. Train and Evaluate Gradient Boosting Classifier
Trains a Gradient Boosting Classifier and evaluates its performance.

### Requirements
- pandas
- seaborn
- matplotlib
- scikit-learn
