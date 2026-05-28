<img width="1582" height="618" alt="image" src="https://github.com/user-attachments/assets/6710740f-c7b0-423b-9211-ef0eac92006b" /># Canada-agricultural-yield-clustering
Machine learning pipeline for agricultural yield forecasting using PCA, K-Means clustering and XGBoost regression

This project applies machine learning and clustering techniques to agricultural yield forecasting data across Canada.

The study uses dimensionality reduction and clustering to uncover latent regional structures, followed by predictive modeling using XGBoost regression.

Three distinct agricultural regions emerged from PCA-based clustering:

Western Canada, 
Eastern Canada and
Manitoba

Each region demonstrates unique climatic and yield stability characteristics that directly influence predictive performance.

Techniques
- PCA dimensionality reduction
- K-Means clustering
- XGBoost regression
- Geospatial visualization
- Data preprocessing

Libraries
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Folium
- Matplotlib

Methodology
1. Data Processing
Historical agricultural yield datasets from Canadian regions
Feature selection and cleaning of environmental and yield variables
Standardization and imputation of missing values
2. Dimensionality Reduction & Clustering
Principal Component Analysis (PCA) used to reduce feature space
K-Means clustering applied to identify regional groupings
Interpretation of clusters based on agricultural and climatic characteristics
3. Predictive Modeling
XGBoost regressor was trained and evaluated for crop yield forecasting.
Performance evaluated using RMSE and MAPE metrics.

Results

The project generated regional agricultural clusters and evaluated yield prediction performance using RMSE and MAPE metrics.

Key Findings

Distinct regional agricultural behaviors were identified through clustering analysis
Manitoba exhibited the most stable and predictable yield patterns
Western Canada showed higher yield variance associated with environmental instability
