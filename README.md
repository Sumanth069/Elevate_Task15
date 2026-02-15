# Elevate_Task15
End-to-end machine learning pipeline using Scikit-learn with preprocessing, model training, evaluation, and deployment-ready pipeline serialization.

This project demonstrates a production-style end-to-end Machine Learning pipeline using Scikit-learn.
It includes data preprocessing, model training, evaluation, and model serialization for deployment.

The implementation follows best practices used in real-world ML systems.

🎯 Objective

Build a complete ML workflow

Prevent data leakage using Pipelines

Apply feature preprocessing using ColumnTransformer

Train and evaluate a classification model

Save the trained pipeline for deployment

📊 Dataset Used

Primary: Breast Cancer Dataset (from sklearn.datasets)
Type: Binary Classification
Features: Numerical features
Target: Malignant (0) / Benign (1)

🛠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook / VS Code

Joblib

⚙️ Workflow

Load dataset

Split into training and testing sets

Apply preprocessing using ColumnTransformer

Standard Scaling for numerical features

Create ML Pipeline combining:

Preprocessing

Logistic Regression model

Train pipeline

Evaluate using:

Accuracy

Precision

Recall

F1-score

Save trained pipeline as .pkl file

📈 Evaluation Metrics

The model is evaluated using:

Accuracy

Precision

Recall

F1 Score

These metrics provide a balanced view of model performance.

💾 Model Saving

The trained pipeline is saved using:

joblib.dump(pipeline, "breast_cancer_pipeline.pkl")


This ensures:

Same preprocessing during inference

Deployment-ready model

No manual preprocessing required

# Output

<img width="720" height="329" alt="Image" src="https://github.com/user-attachments/assets/da1038bc-20e5-4fe8-9fa3-f090b45e0b32" />

