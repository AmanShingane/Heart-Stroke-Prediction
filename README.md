❤️ Heart Disease Prediction App

A Machine Learning web application that predicts the risk of heart disease based on patient health data.
The model is trained using the K-Nearest Neighbors (KNN) algorithm and deployed using Streamlit.

📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help doctors and patients take preventive measures.

This project uses a trained Machine Learning model to analyze patient health metrics and predict whether a person is at high risk or low risk of heart disease.

The application provides a simple interface where users can input medical information and instantly receive a prediction.

🚀 Features

Interactive web interface built with Streamlit

Real-time heart disease prediction

Uses a trained KNN Machine Learning model

Input validation with sliders and dropdown menus

Displays prediction probability

Clean and user-friendly UI

🧠 Machine Learning Workflow

Data Preprocessing

Feature Engineering

Feature Scaling

Model Training (KNN Classifier)

Model Evaluation

Model Serialization using Joblib

Web App Deployment using Streamlit

📂 Project Structure
heart-disease-prediction/
│
├── app.py                 # Streamlit application
├── KNN_heart.pkl          # Trained KNN model
├── scaler.pkl             # Feature scaler
├── columns.pkl            # Feature column structure
├── Classification Preprocessing.ipynb  # Model training notebook
├── dataset.csv            # Dataset used for training
└── README.md              # Project documentation
⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction

Install required libraries:

pip install streamlit pandas scikit-learn joblib
▶️ Run the Application

Start the Streamlit app using:

streamlit run app.py

The application will open in your browser at:

http://localhost:8501
📊 Input Features

The model uses the following medical parameters:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol

Fasting Blood Sugar

Resting ECG

Maximum Heart Rate

Exercise Induced Angina

Oldpeak (ST Depression)

ST Slope

📈 Output

The model predicts:

⚠️ High Risk of Heart Disease

✅ Low Risk of Heart Disease

It also shows the prediction probability.

🛠️ Technologies Used

Python

Pandas

Scikit-Learn

Streamlit

Joblib

📚 Dataset

The dataset contains medical records used to train the machine learning model for heart disease prediction.

👨‍💻 Author

Aman Shingane

Data Science / Machine Learning Enthusiast

⭐ Future Improvements

Deploy the application online

Add more ML models for comparison

Improve UI/UX

Add model performance visualization

📜 License

This project is for educational and research purposes.
