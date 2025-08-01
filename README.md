# ❤️ Heart Disease Prediction - Streamlit App

A simple web application built using **Streamlit** that predicts the likelihood of heart disease using machine learning. This app takes user input for various medical parameters and gives a prediction based on a trained model.

## 🚀 Features

- Predicts heart disease likelihood using health data
- Clean, interactive UI powered by Streamlit
- Trained using a Logistic Regression model
- Easy-to-use interface for medical or academic demonstrations

## 🧠 Machine Learning Model

- **Algorithm Used:** Logistic Regression
- **Dataset Source:** [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Target Variable:** Heart Disease (0: No, 1: Yes)
- **Accuracy Achieved:** ~85% (on test set)

## 📊 Input Features

The model uses the following input features:

- Age
- Sex
- Chest pain type (4 values)
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Slope of peak exercise ST segment
- Number of major vessels (0–3)
- Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)

## 🖥️ How to Run the App Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Lakshaymudgil/Heart-Disase-Prediction-Streamlit-App.git
   cd Heart-Disase-Prediction-Streamlit-App
Install dependencies:
Make sure you have Python installed (preferably >= 3.7).
pip install -r requirements.txt

Run the Streamlit app:
streamlit run app.py

Open your browser and go to http://localhost:8501

📂 Project Structure
Heart-Disase-Prediction-Streamlit-App/
├── app.py                  # Main Streamlit app
├── model.pkl               # Trained ML model
├── heart.csv               # Dataset
├── requirements.txt        # Required Python packages
└── README.md               # Project documentation

📦 Dependencies
pandas

numpy

scikit-learn

streamlit

pickle

Install all using:
pip install -r requirements.txt


🧑‍💻 Author
Lakshay Mudgil
