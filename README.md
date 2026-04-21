🚜 Automated Cost Estimator: Heavy Equipment Price Prediction
🎯 Project OverviewA machine learning regression model designed to forecast the auction sale price of heavy machinery (bulldozers) based on historical usage metrics, equipment configuration, and time-series sales data. This project demonstrates the ability to engineer complex temporal features, handle massive datasets with missing values, and build robust predictive pricing engines.
⚙️ Technical Stack
🔸 Language: Python
🔸 Data Engineering (ETL): Pandas, NumPy
🔸 Machine Learning Framework: Scikit-Learn
🔸 Algorithm Deployed: Random Forest Regressor (Optimized via RandomizedSearchCV)
📊 Key Results & Insights
✅ Model Performance: Achieved a Validation RMSLE of 0.32 and an $R^2$ score of 0.78. Additionally, maintained a Mean Absolute Error (MAE) of ~$8,108, demonstrating a reliable baseline for forecasting the price of high-value heavy machinery.
✅ Time-Series Engineering: Successfully extracted and engineered temporal features (Year, Month, Day, DayOfWeek, DayOfYear) from raw sales dates to identify seasonal purchasing trends.
✅ Data Preprocessing: Built an automated pipeline to convert unstructured string data into pandas categories, impute missing numeric values with medians, and handle massive datasets efficiently.
📁 Project Structurenotebook.ipynb: The core Jupyter Notebook containing the full end-to-end pipeline (Data loading, time-series EDA, feature engineering, model training, and evaluation).data/: Contains the TrainAndValid.csv dataset (Note: Ensure data size is within GitHub limits or provide a link to the Kaggle source).environment.yml / requirements.txt: The isolated local environment dependencies required to replicate this project.
🚀 How to Run LocallyClone the repository: 
git clone []
Install the required dependencies: pip install -r requirements.txtLaunch Jupyter and open the notebook: jupyter notebook notebook.ipynb
