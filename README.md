# Credit Risk Modeling

## Project Overview
Credit risk modeling is crucial for financial institutions to assess the likelihood of a borrower defaulting on a loan. This project involves analyzing multiple datasets to identify factors influencing credit risk, ultimately leading to better decision-making processes. The project provides a credit risk assessment system powered by machine learning. It evaluates borrowers' default risk, calculates credit scores, and assigns credit ratings. The project is built using Python and Streamlit, providing an interactive and user-friendly interface.

### Overview
This project aims to develop a machine learning model to predict default risk, ensuring high accuracy and interpretability. The final model leverages advanced techniques to provide actionable insights, making it suitable for real-world deployment.

### Key Features
- **Dataset**: Imbalanced classification problem with 10% defaults.
- **Techniques**:
  - Feature engineering using domain relevance and statistical analysis.
  - Resampling methods (over-sampling via SMOTE, under-sampling).
- **Models Evaluated**:
  - Logistic Regression
  - Random Forest
  - XGBoost

### Selected Model
- **Model**: XGBoost with Optuna hyperparameter tuning and under-sampling.
- **Metrics**:
  - AUC: 0.98
  - Gini Coefficient: 0.97
  - KS Statistic: 86.87%
- **Interpretability Tools**:
  - SHAP (feature importance)

    ![FI](https://github.com/nafiul-araf/Credit-Risk-Modeling-End-to-End-Project/blob/main/images/Feature%20importance.png)

  - LIME (local interpretability)

    ![lime](https://github.com/nafiul-araf/Credit-Risk-Modeling-End-to-End-Project/blob/main/images/Lime.JPG)

### Key Results
- The model demonstrates superior ability to classify defaults with high precision and recall.
- Decile analysis confirms excellent separation of high-risk instances.


### Visualizations
1. AUC-ROC curve with near-perfect performance (AUC: 0.99).

   ![rocauc](https://github.com/nafiul-araf/Credit-Risk-Modeling-End-to-End-Project/blob/main/images/ROC%20Curve.png)
   
2. SHAP summary plot illustrating top features influencing predictions.

### How to Use
1. **Train the Model**: Scripts for data preprocessing, training, and hyperparameter tuning are included.
2. **Evaluate the Model**: Tools for generating metrics, decile analysis, and interpretability plots.

### Why This Project Stands Out
- Combines state-of-the-art machine learning techniques with interpretability.
- Addresses a real-world business problem with rigor and precision.
- Provides a clear path from model development to deployment.

---



# **Running the Project: Credit Risk Modeling**

## **Features**
- **Interactive Credit Risk Assessment**: Input borrower and loan details and get real-time predictions.
- **Advanced Machine Learning**: Uses a fine-tuned XGBoost model for robust and accurate predictions.
- **Scalable Design**: Modular structure with reusable utilities and hyperparameter tuning.



