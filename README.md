# Laptop-Price-Prediction-using-Python
This project presents a complete  Data analysis with all steps including data cleaning, EDA, machine learning pipeline for predicting laptop prices using selected hardware features: RAM_GB, CPU_core, CPU_frequency, Storage_GB_SSD, GPU. The workflow includes data pre_processing, EDA, feature selection, model development, and evaluation. 
Note: This is a summary of the project (for full report please see the attached report file)

📌 Data Analysis Process


Data preprocessing & cleaning
Exploratory Data Analysis (EDA)
Feature selection
Multiple ML models
Hyperparameter tuning
Model evaluation
Final deployment-ready pipeline

📌 Best Model


✔ Gradient Boosting Regressor
✔ CV R² = 0.6747


📌 Tech Stack



Python
Pandas, NumPy
Scikit-learn
XGBoost
Matplotlib, Seaborn



📌 How to Run



pip install -r requirements.txt
python pipeline/training_pipeline.py
python pipeline/prediction_pipeline.py


📌 Results Summary



Best Model: Gradient Boosting
Strong nonlinear relationship captured
Improved performance over linear models


📦 5. requirements.txt


pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost
joblib



🚀 Final Summary


This GitHub project is structured as a professional end-to-end machine learning system, including:
✔ EDA
✔ Feature Engineering
✔ Model Comparison
✔ Hyperparameter tuning
✔ Final pipeline deployment



📌Pipeline Flow


Model Workflow Diagram (Pipeline Flow)


        ┌────────────────────┐
        │   Raw Dataset      │
        └─────────┬──────────┘
                  ↓
        ┌────────────────────┐
        │ Data Preprocessing │
        └─────────┬──────────┘
                  ↓
        ┌────────────────────┐
        │       EDA          │
        └─────────┬──────────┘
                  ↓
        ┌────────────────────┐
        │ Feature Selection  │
        └─────────┬──────────┘
                  ↓
        ┌────────────────────┐
        │ Model Training     │
        │ (LR, RF, XGB, GB)  │
        └─────────┬──────────┘
                  ↓
        ┌────────────────────┐
        │ Model Evaluation   │
        │ (R², MSE, CV)      │
        └─────────┬──────────┘
                  ↓
        ┌────────────────────┐
        │ Best Model         │
        │ Gradient Boosting  │
        └─────────┬──────────┘
                  ↓
        ┌────────────────────┐
        │ Prediction System  │
        └────────────────────┘


📌Conclusion


After evaluating multiple regression and ensemble models, Tuned Gradient Boosting performed the best with a CV R² score of 0.6747. It provides the best balance between accuracy and generalization, making it the recommended final model.
        
        │ Prediction System  │
        └────────────────────┘
