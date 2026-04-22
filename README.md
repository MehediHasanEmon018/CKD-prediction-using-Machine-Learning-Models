# CKD-prediction-using-Machine-Learning-Models
Machine learning project for predicting Chronic Kidney Disease (CKD) using clinical data. Includes data preprocessing, EDA, and models like Logistic Regression, KNN, Decision Tree, and Random Forest. Evaluated using accuracy, precision, recall, F1-score, and confusion matrix.

🩺 Chronic Kidney Disease (CKD) Prediction

📌 Project Overview:
This project focuses on predicting Chronic Kidney Disease (CKD) using machine learning techniques. The goal is to analyze patient health data and build models that can accurately classify whether a patient has CKD or not.

🎯 Objectives
Perform Exploratory Data Analysis (EDA) to understand the dataset
Clean and preprocess the data (handling missing values, encoding, scaling)
Train multiple machine learning models
Evaluate model performance using metrics like accuracy, precision, recall, and F1-score
Identify the best-performing model for CKD prediction

📂 Dataset
The dataset contains medical attributes such as:
Age
Blood Pressure
Specific Gravity
Albumin
Sugar
Hemoglobin
Serum Creatinine
And other clinical features

Target variable:
CKD (1 = Disease, 0 = No Disease)
⚙️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn

🔄 Workflow:

1. Data Preprocessing
Converted categorical values (Yes/No) into binary (1/0)
Handled missing values
Feature scaling using StandardScaler
2. Exploratory Data Analysis (EDA)
Distribution plots
Correlation heatmap
Feature relationships analysis
3. Train-Test Split
Dataset split into training and testing sets
Used stratification to maintain class balance
4. Model Training

Models used:
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest

5. Model Evaluation:
Accuracy
Confusion Matrix
Precision
Recall
F1-score

📊 Results:
Compared multiple models to find the best performer
Random Forest / KNN (modify based on your result) achieved the highest accuracy
Model performance evaluated using confusion matrix and classification report

🚀 How to Run the Project:
Clone this repository:
git clone https://github.com/your-username/ckd-prediction.git
Navigate to the project folder:
cd ckd-prediction
Install dependencies:
pip install -r requirements.txt
Open the notebook:
jupyter notebook CKD_prediction.ipynb

📈 Future Improvements:
Hyperparameter tuning
Use of advanced models (XGBoost, Neural Networks)
Deployment as a web app
Real-time prediction system

🤝 Contribution:
Feel free to fork this repository and submit pull requests.

📜 License

This project is open-source and available under the MIT License.
