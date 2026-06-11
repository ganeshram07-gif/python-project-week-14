# Credit Card Fraud Detection System

## Project Overview

The Credit Card Fraud Detection System is a machine learning and data analytics project developed to identify fraudulent credit card transactions using historical transaction data. The project combines data preprocessing, exploratory data analysis (EDA), predictive modeling, and interactive visualizations to understand transaction patterns and detect potential fraud.

This project uses the Kaggle Credit Card Fraud Detection dataset and demonstrates how data-driven techniques can support financial security and fraud prevention.

---

## Objectives

- Analyze credit card transaction data.
- Perform data cleaning and preprocessing.
- Explore transaction patterns using EDA.
- Identify characteristics of fraudulent transactions.
- Build a Linear Regression model for analytical purposes.
- Visualize transaction behavior through charts and dashboards.
- Generate insights that support fraud detection strategies.

---

## Dataset

**Source:** Kaggle – Credit Card Fraud Detection Dataset

### Main Features

| Feature | Description |
|----------|-------------|
| Time | Seconds elapsed between transactions |
| Amount | Transaction amount |
| V1-V28 | PCA-transformed anonymized features |
| Class | Target variable (0 = Normal, 1 = Fraud) |

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn

---

## Project Workflow

### 1. Data Collection
- Load dataset from Google Drive.
- Inspect dataset structure and features.

### 2. Data Cleaning & Preprocessing
- Check missing values.
- Verify data types.
- Prepare features for analysis.

### 3. Exploratory Data Analysis (EDA)
- Fraud vs Non-Fraud distribution.
- Transaction amount analysis.
- Correlation analysis.
- Outlier identification.

### 4. Relationship Analysis
- Amount vs Fraud Status.
- Feature correlations.
- Transaction behavior patterns.

### 5. Predictive Modeling
- Train/Test Split.
- Linear Regression model creation.
- Prediction generation.

### 6. Model Evaluation
- R² Score.
- Mean Absolute Error (MAE).
- Root Mean Squared Error (RMSE).

### 7. Interactive Dashboard
- Fraud distribution charts.
- Transaction amount visualizations.
- Correlation insights.
- Interactive Plotly graphs.

---

## How to Run

1. Open the notebook in Google Colab.
2. Mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Update the dataset path if necessary.
4. Run all notebook cells sequentially.

---

## Expected Outcomes

- Better understanding of fraudulent transaction patterns.
- Identification of factors associated with fraud.
- Visual insights through dashboards and charts.
- Foundation for building advanced fraud detection models.

---

## Future Enhancements

- Random Forest Classifier.
- XGBoost Classifier.
- Real-time fraud detection system.
- Streamlit dashboard deployment.
- Advanced anomaly detection techniques.

## Visualization
<img width="1728" height="520" alt="image" src="https://github.com/user-attachments/assets/05ed27f8-173d-431b-8b7f-5412d14b4fa4" />
<img width="1725" height="527" alt="image" src="https://github.com/user-attachments/assets/d8961d22-663d-4e55-9042-5c7552e73957" />
<img width="1725" height="530" alt="image" src="https://github.com/user-attachments/assets/e696bbd6-0d1c-4363-8151-23a84915d50b" />
<img width="1733" height="523" alt="image" src="https://github.com/user-attachments/assets/e61b61ae-0421-4b79-9732-7ce2f07146a1" />
<img width="1745" height="533" alt="image" src="https://github.com/user-attachments/assets/3e2e3fc0-8ccf-49f3-9a64-16fce95766a8" />
<img width="803" height="706" alt="image" src="https://github.com/user-attachments/assets/0aa1296a-5ad1-4520-9cd6-519c676a97af" />
<img width="1732" height="527" alt="image" src="https://github.com/user-attachments/assets/ffa7460c-9398-496a-8a91-d1e4f09d7908" />

---

## Conclusion

This project demonstrates how machine learning, data visualization, and statistical analysis can be applied to detect fraudulent credit card transactions. The system provides valuable insights that can help financial institutions improve security and reduce fraud-related losses.
