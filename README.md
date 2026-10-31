# NBA Shot Prediction

Predicting whether an NBA shot will go in using machine learning and data from the 2014–2015 season.

The project covers data collection and preparation, exploratory analysis, feature engineering, and training and evaluation of classification models. Features include shot distance, defender distance, and player and game context.

## Models

- Logistic Regression (L1 and L2 regularization)
- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- CatBoost

Models were compared using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrices. **CatBoost achieved the highest test accuracy, approximately 66.6%.** The analysis also explores feature importance and the trade-offs between different models.

## Tools

Python, pandas, NumPy, scikit-learn, XGBoost, CatBoost, Matplotlib, Seaborn, and Jupyter Notebook.

## Project files

- [`notebooks/dataworks_final.ipynb`](notebooks/dataworks_final.ipynb) — main notebook with code and analysis.
- [`notebooks/dataworks_final.html`](notebooks/dataworks_final.html) — exported notebook with outputs, available to read without rerunning the analysis.
- `utils/` — supporting Python utilities.

The HTML export is the easiest way to review the complete analysis and results.
