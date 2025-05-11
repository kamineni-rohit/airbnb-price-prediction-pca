# Airbnb Price Prediction Using PCA

This project explores predictive modeling for Airbnb listing prices using extensive data cleaning, feature engineering, and dimensionality reduction via Principal Component Analysis (PCA).

## 🧠 Objective
To predict listing prices accurately by transforming raw Airbnb data into a refined dataset and reducing complexity while preserving variance through PCA.

## 🧪 Methodology

### Data Cleaning
- Removed irrelevant or non-predictive columns such as IDs, URLs, names, and unstructured text.
- Dropped columns with high percentages of missing values.
- Imputed missing numerical fields like `bedrooms`, `beds`, and `review_scores_*` using mean-based methods.
- Removed extreme outliers to improve model robustness.

### Feature Engineering
- Created binary indicator columns (e.g., `is_superhost`, `instant_bookable_true`) for categorical features.
- Introduced derived features to improve interpretability and model input quality.

### Dimensionality Reduction
- Applied PCA to 24 cleaned continuous variables.
- Retained 18 principal components, preserving over 95% of the variance in the original dataset.

## 📊 Results
The final dataset is ready for regression or machine learning pipelines. PCA significantly improved model training efficiency by reducing feature space while retaining core information.

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- PCA for dimensionality reduction and noise reduction

## 👥 Team
- Ayushi Bisht  
- Rohit Kamineni  
- Ryan Nelson  
- Satakshi Deshmukh  
- Sumit Pal  
- Supraja Bala

## 📌 Notes
- Dataset contained over 12,000 Airbnb listings.
- Model-ready dataset preserves meaningful insights while removing noise and redundancy.
- Useful as a preprocessing pipeline template for real estate or rental price prediction problems.

