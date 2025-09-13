# 📊 ANN Churn Classification  

<p align="center">
  <img src="https://img.shields.io/github/stars/anjaliy11/ANN_churn_classification" alt="Stars">
  <img src="https://img.shields.io/github/forks/anjaliy11/ANN_churn_classification" alt="Forks">
  <img src="https://img.shields.io/github/issues/anjaliy11/ANN_churn_classification" alt="Issues">
</p>

<p align="center">
  <!-- Tech Stack Badges -->
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras&logoColor=white" alt="Keras">
  <img src="https://img.shields.io/badge/Scikit--Learn-ML%20Toolkit-yellow?logo=scikit-learn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white" alt="Jupyter">
</p>

---

## 📑 Table of Contents
- [ Overview](#-overview)  
- [ Quickstart](#-quickstart)    
- [ Features](#-features)  
- [🛠 Technologies Used](#️-technologies-used)  
- [ Project Structure](#-project-structure)  
- [ Getting Started](#-getting-started)  
- [ Model Performance](#-model-performance)  
- [ How It Works](#-how-it-works)  
- [🗂 Project Index](#️-project-index)   
- [ Contribution](#-contribution)   
- [ Acknowledgements](#-acknowledgements)  

---

## 📖 Overview
This repository implements an **Artificial Neural Network (ANN)** for predicting **customer churn** in a classification setting.  
The project demonstrates how deep learning can be applied to business problems, specifically in understanding whether a customer will stay or leave.

---

## ⚡ Quickstart
1. Clone the repo:
   ```bash
   git clone https://github.com/anjaliy11/ANN_churn_classification.git
   cd ANN_churn_classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

---

## ✨ Features
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.  
- **Model Building**: Constructing a Sequential ANN using Keras.  
- **Model Evaluation**: Assessing performance with accuracy and loss metrics.  
- **Deployment**: Creating an interactive web application using Streamlit for real-time predictions.  
- **Extensibility**: Easy to extend for other binary classification tasks.  

---

## 🛠️ Technologies Used
- **Data Processing**: Pandas, NumPy, Scikit-learn  
- **Machine Learning**: TensorFlow, Keras  
- **Web Application**: Streamlit  
- **Serialization**: Pickle  
- **Version Control**: Git  

---

## 📂 Project Structure
```
.
├── app.py                     # Streamlit application for real-time predictions
├── Churn_Modelling.csv        # Dataset containing customer information
├── experiments.ipynb          # Exploratory data analysis
├── hyperparametertuningann.ipynb  # Hyperparameter tuning
├── prediction.ipynb           # Predictions notebook
├── salaryregression.ipynb     # Salary regression analysis
├── requirements.txt           # Python dependencies
├── scaler.pkl                 # StandardScaler for feature scaling
├── label_encoder_gender.pkl   # LabelEncoder for encoding gender
├── onehot_encoder_geo.pkl     # OneHotEncoder for encoding geography
└── my_model.keras             # Trained ANN model
```

---

## 🚀 Getting Started
Install dependencies:
```bash
pip install -r requirements.txt
```

Run the Streamlit application:
```bash
streamlit run app.py
```

Open your browser at `http://localhost:8501`.

---

## 📈 Model Performance
- **Test Accuracy**: 85.95%  
- **Test Loss**: 0.3370  

These metrics indicate a well-performing model capable of accurately predicting customer churn.

---

##  How It Works
1. **Data Loading**: Dataset is loaded and preprocessed (encoding categorical variables + scaling).  
2. **Model Training**: ANN is trained to learn patterns linked to churn.  
3. **Prediction**: Trained model predicts churn probabilities for new data.  
4. **Deployment**: Streamlit app serves as a user-friendly prediction interface.  

---

## 🗂️ Project Index
- **Model Training**: `experiments.ipynb`  
- **Model Prediction**: `prediction.ipynb`   

---

## 🤝 Contribution
Contributions are welcome!  

1. Fork the repo  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m 'Add feature'`)  
4. Push to branch (`git push origin feature-name`)  
5. Create a Pull Request  

---

##  Acknowledgements
- TensorFlow & Keras for model building  
- Scikit-learn & Pandas for preprocessing  
- Open source community for tools and inspiration  
