# Mercedes-Benz-Greener-Manufacturing

## Project Overview
- Optimize speed and efficiency of the Mercedes-Benz car testing system using advanced machine learning.
- Reduce test bench time while maintaining Mercedes-Benz’s high-quality standards.
- Identify the best car feature combinations for quicker testing without sacrificing reliability.
- Key process steps:
  - Data Acquisition
  - Data Wrangling
  - Exploratory Data Analysis (EDA)
  - Dimensionality Reduction
  - Model Training and Prediction

## Detailed Project Description

### 1. Data Acquisition
- Collect data related to Mercedes-Benz vehicle testing.
- Dataset includes vehicle specifications, test parameters, and performance metrics.
- Ensures the model learns meaningful patterns.

### 2. Data Wrangling
- Clean raw data by:
  - Handling missing values
  - Correcting inconsistencies
  - Transforming data into a usable format
- Ensures data accuracy and reliability for modeling.

### 3. Exploratory Data Analysis (EDA)
- Visualize feature distributions and relationships.
- Identify correlations between variables.
- Detect outliers or anomalies.
- Gain insights into feature importance.
- Helps in early data issue detection and feature selection.

### 4. Dimensionality Reduction using PCA (Principal Component Analysis)
- Reduce the number of features to a smaller set of uncorrelated components.
- Capture most data variance while lowering complexity.
- Focus on significant features to decrease car testing time.
- Improve model efficiency and speed without losing accuracy.

### 5. Model Fitting and Prediction
- Use **XGBoost Regressor** for predicting testing time/efficiency.
- Compare with Decision Tree and Random Forest regressors.
- XGBoost achieves a lower Mean Squared Error (MSE), indicating better accuracy.
- Train model on PCA-reduced data for computational efficiency.
- Predict testing time for various feature combinations.
- Help engineers select optimal configurations.

## Key Benefits and Outcomes
- Optimized testing time, leading to cost savings and increased throughput.
- Maintained Mercedes-Benz quality standards with reliable predictions.
- Efficient handling of high-dimensional data using PCA and XGBoost.
- Developed a scalable pipeline from data collection to prediction.
- Ready for future enhancements or real-time deployment.

## Technologies and Tools Used
- **Programming Language:** Python
- **Libraries/Frameworks:**
  - pandas, numpy (data manipulation)
  - matplotlib, seaborn (data visualization)
  - scikit-learn (PCA)
  - XGBoost (model training)
- **Evaluation Metric:** Mean Squared Error (MSE) for model performance comparison


