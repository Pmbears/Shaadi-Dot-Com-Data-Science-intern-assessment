
# **Data Science Case Study: Handling Imbalanced Data and Model Predictions**

This repository contains a comprehensive data science project that demonstrates the process of handling imbalanced datasets, applying machine learning models, and generating predictions. The project focuses on using various preprocessing techniques, dimensionality reduction, and model training to achieve accurate results.

## **Project Overview**
1. **Data Preprocessing:**
   - Standardized the dataset using `StandardScaler` to normalize features.
   - Applied Principal Component Analysis (PCA) to reduce data dimensionality while retaining essential information.

2. **Handling Imbalanced Data:**
   - Used `RandomUnderSampler` to balance the dataset by reducing the majority class.
   - Verified class distribution after resampling.

3. **Model Training and Prediction:**
   - Trained multiple machine learning models, including:
     - Random Forest
     - Support Vector Classifier (SVC)
     - XGBoost
   - Used XGBoost for final predictions on the test dataset due to its superior performance.

4. **Output:**
   - Exported predictions in a structured format for downstream analysis.

## **Key Features**
- Balanced data for fairer model training using undersampling techniques.
- Dimensionality reduction with PCA to optimize computation and performance.
- Comparative analysis of multiple models to choose the best-performing one.

## **Files in the Repository**
- `Script.ipynb`: Jupyter Notebook containing the entire analysis, preprocessing, and model training steps.
- `Data`: Folder containing the training and test datasets used in the project.
- `Prediction`: Folder with output files containing predictions.

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/Pmbears/Shaadi-Dot-Com-Data-Science-intern-assessment.git
   ```
2. Open the Jupyter Notebook in your preferred environment.
3. Run the notebook to reproduce the results.

## **Dependencies**
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, imbalanced-learn, xgboost, matplotlib

## **License**
This project is licensed under the MIT License.

---

