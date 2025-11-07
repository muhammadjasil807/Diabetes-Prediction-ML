**Diabetes Prediction using Machine Learning**

An AI-powered Diabetes Prediction System that uses machine learning to estimate the likelihood of a person having diabetes based on various medical attributes such as glucose level, BMI, blood pressure, and age. The model is trained using Logistic Regression and Random Forest and deployed with Streamlit for an interactive and user-friendly web interface.

---

**Overview**

This project demonstrates an end-to-end Machine Learning pipeline — from data preprocessing and model training to evaluation and deployment.

Users can input medical details such as:

* Glucose Level
* Blood Pressure
* BMI (Body Mass Index)
* Insulin and Skin Thickness
* Age
* Pregnancies
* Diabetes Pedigree Function

The trained model then predicts whether the person is at high risk or low risk of diabetes.

---

**Features**

* Interactive web interface built using Streamlit
* Real-time risk prediction based on user input
* Clean and optimized ML pipeline using Scikit-learn
* Supports multiple classification models
* Deployed locally or online (via Ngrok / Streamlit Cloud)
* Visualized metrics and model comparison charts

---

**Tech Stack**

Programming Language: Python 3
Machine Learning: Scikit-learn
Data Processing: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Frontend/UI: Streamlit
Deployment: Streamlit + Pyngrok
Model Saving: Joblib
-

**Installation and Running**

Step 1 — Clone the Repository

Step 2 — Install Dependencies
pip install -r requirements.txt

Step 3 — Run the Streamlit App
streamlit run app.py

Step 4 — (Optional) Get a Public Link using Ngrok
from pyngrok import ngrok
ngrok.connect(8501)

---

**Model Details**

Model Used: Logistic Regression, Random Forest
Target Variable: Diabetes outcome (1 = Diabetic, 0 = Non-Diabetic)
Input Features: Glucose, BMI, Age, Pregnancies, Insulin, Blood Pressure, etc.
Preprocessing: Handling missing values, feature scaling
Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report

---

**Example Output**

User Input:
Glucose: 150
BMI: 32.5
Blood Pressure: 80
Age: 45

Output:
High risk of diabetes detected.
Probability: 0.87

---

User Input:
Glucose: 95
BMI: 23.1
Blood Pressure: 72
Age: 25

Output:
Low risk of diabetes detected.
Probability: 0.12

---

**Future Improvements**

* Integrate a real-world healthcare dataset
* Add feature importance visualization
* Deploy on Streamlit Cloud / Hugging Face Spaces
* Include lifestyle recommendations based on results
* Add model comparison dashboard
