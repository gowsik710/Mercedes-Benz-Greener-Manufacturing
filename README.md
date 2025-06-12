# Mercedes-Benz-Greener-Manufacturing

Project Overview
Optimize the speed and efficiency of the Mercedes-Benz car testing system using advanced machine learning techniques.

Reduce the time a car spends on the test bench while maintaining Mercedes-Benz's high-quality standards.

Identify optimal combinations of car features that allow faster testing without compromising reliability or performance evaluation.

Approach involves:

Data Acquisition

Data Wrangling

Exploratory Data Analysis (EDA)

Dimensionality Reduction

Model Training and Prediction

Detailed Project Description
1. Data Acquisition
Collect relevant data related to Mercedes-Benz vehicle testing.

Dataset includes vehicle specifications, test parameters, and performance metrics.

Ensures meaningful patterns and relationships can be learned by the model.

2. Data Wrangling
Handle missing values and correct inconsistencies.

Clean and transform raw data into a format suitable for analysis.

Prepare accurate and reliable data for modeling.

3. Exploratory Data Analysis (EDA)
Visualize feature distributions and relationships.

Identify correlations between variables.

Detect outliers or anomalies.

Gain insights into feature importance.

Guide feature selection and detect early data issues.

4. Dimensionality Reduction using PCA (Principal Component Analysis)
Reduce large number of features to a smaller set of uncorrelated components.

Capture majority of data variance while reducing complexity.

Decrease car testing time by focusing on significant features.

Improve model efficiency and speed without sacrificing accuracy.

5. Model Fitting and Prediction
Use XGBoost Regressor for predicting testing time or efficiency.

Compare with Decision Tree and Random Forest regressors.

Achieve lower Mean Squared Error (MSE), indicating higher accuracy.

Train model on reduced-dimensional data (post-PCA) for better computational efficiency.

Predict expected testing time for various feature combinations.

Assist engineers in selecting optimal configurations.

Key Benefits and Outcomes
Optimized testing time on the bench, leading to cost savings and increased throughput.

Maintained Mercedes-Benz quality standards without sacrificing accuracy or reliability.

Efficient handling of high-dimensional data using PCA and XGBoost.

Developed a robust and scalable pipeline from data collection to prediction.

Prepared for future enhancements or real-time deployment.

Technologies and Tools Used
Programming Language: Python

Libraries and Frameworks:

pandas, numpy (data manipulation)

matplotlib, seaborn (EDA visualization)

scikit-learn (PCA implementation)

XGBoost (modeling)

Evaluation Metric: Mean Squared Error (MSE) for model performance comparison



