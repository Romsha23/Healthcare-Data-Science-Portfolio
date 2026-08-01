
# Healthcare Data Science Portfolio 🏥

Welcome to my healthcare data science portfolio. This repository demonstrates a complete, end-to-end data pipeline typical of real-world healthcare analytics and machine learning environments. 

The project is broken down into four chronological stages, progressing from raw, messy clinical logs to privacy-compliant, model-ready datasets, and finally to predictive modeling.

## 📂 Repository Structure

### [01. Data Quality and Cleaning](./01_Data_Quality_and_Cleaning/)
Focuses on exploring raw data, identifying anomalies (e.g., impossible vital signs, temporal inconsistencies), removing duplicates, and ensuring HIPAA compliance by masking Protected Health Information (PHI).

### [02. Data Engineering and Harmonization](./02_Data_Engineering_and_Harmonization/)
Demonstrates the integration of siloed healthcare systems. It standardizes patient identifiers, maps diagnostic terminologies (ICD codes), and merges Electronic Health Records (EHR), insurance claims, and laboratory results into a unified view. Includes programmatic generation of synthetic healthcare data.

### [03. Feature Engineering](./03_Feature_Engineering/)
Bridges the gap between raw tables and machine learning. Transforms longitudinal clinical events into model-ready features by aggregating lab results, counting encounter frequencies, and strictly preventing data leakage (predicting the future).

### [04. Machine Learning and Modeling](./04_Machine_Learning_and_Modeling/)
Showcases predictive modeling with a focus on clinical interpretation. Includes a regularized Logistic Regression model to predict 30-day hospital readmissions, analyzes feature coefficients, and addresses class imbalance using dynamically weighted loss functions.

## 🛠️ Technologies & Tools Used
* **Python** (Pandas, NumPy)
* **Machine Learning** (Scikit-Learn)
* **Data Visualization** (Matplotlib, Seaborn)
* **Healthcare Concepts** (HIPAA De-identification, EHR/Claims Harmonization, Data Leakage Prevention, Risk Stratification)
