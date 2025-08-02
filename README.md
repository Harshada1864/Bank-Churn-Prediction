# Bank Customer Churn Prediction
This project predicts bank customer churn using machine learning and SHAP for explainability. It includes EDA, model training, and an HTML page that auto-saves and opens.

## Setup
1. Download `Churn_Modeling.csv` from [Kaggle](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset).
2. Place it in the `data` folder.
3. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap`.
4. Run `Churn_Prediction.ipynb` in Jupyter Notebook to generate visualizations in `outputs` and `visualizations.html`, which opens automatically.
5. Open `visualizations.html` in a browser to view results (auto-opened by the notebook).

## Files
- `Churn_Prediction.ipynb`: Jupyter Notebook with analysis.
- `data/Churn_Modeling.csv`: Dataset (download from Kaggle).
- `outputs/*.png`: Visualization images.
- `visualizations.html`: HTML page displaying all visualizations.

## Outputs
- EDA: Churn distribution, correlations, age/balance vs. churn.
- Model Performance: Metrics and ROC curves.
- SHAP: Feature importance and dependence plots.
- HTML Page: Auto-saved and opened visualization summary.
