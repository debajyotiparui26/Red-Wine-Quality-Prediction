# Red-Wine-Quality-Prediction
This project evaluates wine quality by comparing chemical properties with standard good-wine ranges using Python and Matplotlib visualizations.
#  Red Wine Quality Prediction

This project predicts the quality of red wine using machine learning based on physicochemical properties.

# Objective
- Predict whether a wine is *Good* or *Not Good*
- Perform EDA and feature analysis
- Compare multiple ML models

# Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Joblib

# Dataset
- Red Wine Quality Dataset (UCI ML Repository)
- Binary classification:
  - 1 → Good Quality (quality ≥ 7)
  - 0 → Not Good Quality (quality < 7)

# Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier (Best Model)

# Evaluation Metrics
- Accuracy (Train & Test)
- Classification Report
- Confusion Matrix
- ROC-AUC Score

#  Model Saving
- `red_wine_quality_model.pkl`
- `scaler.pkl`

#  How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
python red_wine_quality_prediction.py
