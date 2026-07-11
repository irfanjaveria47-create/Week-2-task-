
# Steel Industry Energy Consumption – Advanced EDA & Machine Learning

## 📌 Project Overview
This project analyzes the Steel Industry Energy Consumption dataset and develops a machine learning pipeline to classify electrical load types (Light Load, Medium Load, and Maximum Load). The project includes comprehensive Exploratory Data Analysis (EDA), data preprocessing, model training, evaluation, and explainability.

---

## 👩‍💻 Author
**Name:** Javeria Irfan  
**Roll No:** AIMLB01-94888

---

## 🎯 Objectives
- Analyze industrial energy consumption patterns.
- Perform detailed Exploratory Data Analysis (EDA).
- Handle class imbalance using SMOTE.
- Train and compare multiple machine learning models.
- Evaluate model performance using appropriate metrics.
- Interpret predictions using SHAP explainability.

---

## 📊 Dataset
- **Dataset:** Week 2 (DataSet).xlsx
- **Data Frequency:** Every 15 minutes for one year
- **Target Variable:** Load_Type
- **Classes:**
  - Light_Load
  - Medium_Load
  - Maximum_Load

### Features
- Usage_kWh
- Reactive Power
- CO2 Emissions
- Power Factor
- NSM
- WeekStatus
- Day_of_week

---

## 🔍 Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Missing value and duplicate analysis
- Feature engineering
- Target distribution analysis
- Class imbalance analysis
- Outlier detection using IQR
- Correlation heatmap
- Mutual Information analysis
- Time-series trend visualization

---

## 🤖 Machine Learning Models
The following models were trained and compared:
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM

---

## ⚙️ Techniques Used
- One-Hot Encoding
- Label Encoding
- StandardScaler
- SMOTE
- Stratified 5-Fold Cross Validation
- RandomizedSearchCV
- SHAP Explainability

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

## 🏆 Results
- XGBoost achieved the best overall performance.
- SMOTE improved prediction of minority classes.
- SHAP identified Reactive Power and Power Factor as the most influential features.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- LightGBM
- SHAP
- Imbalanced-learn

---

## 🚀 Future Improvements
- Bayesian Hyperparameter Optimization (Optuna)
- LSTM-based Time-Series Forecasting
- FastAPI Model Deployment

---

## 📄 License
This project is developed for educational and learning purposes.
