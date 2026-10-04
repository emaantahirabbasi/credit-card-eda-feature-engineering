
   # Credit Card EDA & Feature Engineering

   Data preprocessing and feature engineering on a credit card transaction dataset (93,949 rows × 31 columns).

   - **Missing values:** 15% missing values simulated in 3 columns; median and KNN imputation compared
   - **Outliers:** detected with the IQR method and treated with Winsorization (capping), retaining 100% of rows
   - **Feature engineering:** 4 new features (LOG_AMOUNT, HOUR_OF_DAY, V_MEAN, V_SUM), expanding the dataset from 31 to 35 columns
   - **Tech:** Python, pandas, scikit-learn, matplotlib, seaborn
