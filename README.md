![GitHub repo size](https://img.shields.io/github/repo-size/anjaliy11/ANN_churn_classification) 
![Python](https://img.shields.io/badge/Python-3.8+-blue) 
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange) 
![Keras](https://img.shields.io/badge/Keras-2.x-red) 
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-green) 

### Customer Churn Prediction with Artificial Neural Networks

This project demonstrates the application of Artificial Neural Networks (ANNs) to predict customer churn for a telecommunications company. By analyzing customer data, the model identifies patterns that indicate whether a customer is likely to leave the service, enabling proactive retention strategies.


---

---
 ### 📊 Project Overview

Customer churn prediction is crucial for businesses aiming to retain valuable clients. This repository implements an ANN to classify customers based on various features, such as demographics, account information, and usage patterns.


---
---

### 🧪 Features

Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.

Model Building: Constructing a Sequential ANN using Keras.

Model Evaluation: Assessing performance with accuracy and loss metrics.

Deployment: Creating an interactive web application using Streamlit for real-time predictions.

---

---

### 🛠️ Technologies Used

Data Processing: Pandas, NumPy, Scikit-learn

Machine Learning: TensorFlow, Keras

Web Application: Streamlit

Serialization: Pickle

Version Control: Git

---

---
### 📁 Project Structure
.
├── app.py                     # Streamlit application for real-time predictions
├── Churn_Modelling.csv        # Dataset containing customer information
├── experiments.ipynb          # Jupyter notebook for exploratory data analysis
├── hyperparametertuningann.ipynb # Jupyter notebook for hyperparameter tuning
├── prediction.ipynb           # Jupyter notebook for making predictions
├── salaryregression.ipynb     # Jupyter notebook for salary regression analysis
├── requirements.txt           # Python dependencies
├── scaler.pkl                 # StandardScaler object for feature scaling
├── label_encoder_gender.pkl   # LabelEncoder for encoding gender
├── onehot_encoder_geo.pkl     # OneHotEncoder for encoding geography
└── my_model.keras             # Trained ANN model

---
---
### 🚀 Getting Started
pip install -r requirements.txt

---
---

### Running the Streamlit App

Start the Streamlit application:
streamlit run app.py
Access the application in your browser at http://localhost:8501.

---
---

### 📈 Model Performance

Test Accuracy: 85.95%
Test Loss: 0.3370

These metrics indicate a well-performing model capable of accurately predicting customer churn.

---
---

### 🔧 How It Works

Data Loading: The dataset is loaded and preprocessed, including encoding categorical variables and scaling features.

Model Training: An ANN is trained on the processed data to learn patterns associated with customer churn.

Prediction: The trained model predicts churn probabilities for new customer data.

Deployment: The Streamlit app serves as an interface for users to input customer information and receive churn predictions.

---
