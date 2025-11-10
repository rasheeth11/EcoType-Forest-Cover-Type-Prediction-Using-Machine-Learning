# EcoType-Forest-Cover-Type-Prediction-Using-Machine-Learning
To develop a machine learning classification model that predicts the type of forest cover in a given geographical area based on cartographic variables like elevation, soil type, slope, and wilderness area information. The goal is to assist in environmental monitoring, forestry management.
# Data Collection
Download and load the complete Forest Cover Type dataset using Pandas.
Understand the dataset’s structure, column descriptions, and target classes
# Data Understanding
Explore and understand the dataset using Pandas functions like .shape, .info(), .describe(), and .value_counts().
Check for duplicate records, missing values, and class distribution imbalance.
# Data Cleaning & Transformation
Handle missing values by imputing with appropriate techniques (like median,mean,mode).
Detect and handle outliers using Z-score or IQR method for numeric features.
Fix skewness in continuous variables using suitable transformations (e.g., log1p).
# Class Imbalance Handling
Use RandomOverSampler or SMOTE or other resampling techniques to balance class distribution in the training data.
# Feature Selection
Apply feature importance analysis using Random Forest or correlation-based methods.
Drop less relevant or low-variance features to simplify the model and improve training efficiency.

<img width="557" height="326" alt="image" src="https://github.com/user-attachments/assets/a22b49eb-f463-4e0b-983c-8687211280a7" />

# Model Building
Build and evaluate at least 5 different classification models:
Random Forest

<img width="413" height="307" alt="image" src="https://github.com/user-attachments/assets/c4ae6974-3f25-4e17-bf87-90e2cc2f80ff" />

Decision Tree

<img width="792" height="603" alt="image" src="https://github.com/user-attachments/assets/e633d8f3-6e4e-4c47-9a91-0445662b8eef" />

Logistic Regression

<img width="389" height="302" alt="image" src="https://github.com/user-attachments/assets/e2addea3-9691-4707-830a-3cbbdfae812a" />

K-Nearest Neighbors (KNN)

<img width="412" height="308" alt="image" src="https://github.com/user-attachments/assets/cad9f96e-e055-468b-b875-0f038e455d7b" />

XGBoost

<img width="397" height="298" alt="image" src="https://github.com/user-attachments/assets/4da63882-106a-4074-8537-0719507a1c46" />

Compare models using Accuracy, Confusion Matrix, and Classification Report metrics.
# Finalize and Save Best Model
Choose the best-performing model based on evaluation metrics.
Save this trained model as a .pkl file for deployment. (pickle /joblib)

<img width="578" height="356" alt="image" src="https://github.com/user-attachments/assets/6f15bb67-725b-4451-9e9a-db6d756730c3" />
# Final Task: Build a Streamlit UI
Design a clean, interactive Streamlit application.
Allow users to manually input values for all model features through numeric input fields and dropdowns.
Use the saved model to predict the forest cover type and display the result clearly.
Inverse transform the target variables while displaying the output.

<img width="272" height="378" alt="image" src="https://github.com/user-attachments/assets/dc355267-681d-4e20-92a5-9590b24abf8b" />
