# diabetes-ml-project
🩺 Diabetes Prediction System (Machine Learning Project)
📌 Project Overview

This project is a Machine Learning-based Diabetes Prediction System that uses patient medical data to predict whether a person is diabetic or non-diabetic. The model is trained using Support Vector Machine (SVM) with a linear kernel and achieves good accuracy on unseen data.

The system is built using Python and popular ML libraries such as Pandas, NumPy, Scikit-learn, and StandardScaler for preprocessing.

⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Scikit-learn
SVM (Support Vector Machine)
Logistic Regression (exploration)
StandardScaler (feature scaling)
📊 Dataset Information

The dataset contains medical attributes such as:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
Outcome (Target Variable)

📌 Dataset size: 2460 records × 9 columns

🧠 Machine Learning Workflow
1. Data Preprocessing
Loaded dataset using Pandas
Checked data structure and statistics
Handled feature-target separation:
X = features
Y = Outcome
2. Feature Scaling

StandardScaler was applied to normalize the data:

Ensures all features contribute equally
Improves SVM performance
3. Train-Test Split
Training data: 80%
Testing data: 20%
Stratified splitting used for balanced classes
4. Model Training

A Support Vector Machine (SVM) with a linear kernel was used:

Model learns decision boundary between diabetic and non-diabetic cases
5. Model Evaluation
🎯 Accuracy Results:
Training Accuracy: ~73.6%
Testing Accuracy: ~75.4%

These results show the model generalizes well on unseen data.

🧪 Prediction Example

The model can predict diabetes based on input medical data:

input_data = (4, 110, 92, 0, 0, 37.6, 0.191, 30)
Output:
The person is diabetic
or
The person is non-diabetic
📈 Key Features of Project

✔ Clean ML pipeline
✔ Data preprocessing with StandardScaler
✔ SVM classification model
✔ Real-time prediction capability
✔ Balanced dataset handling
✔ Simple and interpretable workflow

🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
2. Install dependencies
pip install -r requirements.txt
3. Run the notebook / script
python main.py
🔮 Future Improvements
Try advanced models (Random Forest, XGBoost, Neural Networks)
Hyperparameter tuning for better accuracy
Feature selection techniques
Cross-validation for better performance evaluation
Deploy as a web API using FastAPI
Build a frontend for real-time prediction
👨‍💻 Project Purpose

This project demonstrates practical knowledge of:

Machine Learning pipeline
Data preprocessing
Classification models
Model evaluation
Real-world healthcare prediction systems
