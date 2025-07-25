# 🩺 Diabetes Predictor

A Django-powered web application that utilizes machine learning to predict the likelihood of diabetes based on user health data. Built for ease of use, fast predictions, and clinical insight.

---

## 🔍 Overview

This project combines data science and web development to build an end-to-end diabetes prediction system. Users input medical details through a web form, and the app returns prediction results based on a trained model using the PIMA Indian Diabetes dataset.

---

## 🚀 Features

- 🎯 Accurate predictions using Scikit-learn
- 🔗 Integrated Django backend with ML model
- 📊 Interactive Jupyter Notebook for model training
- 🖥️ Responsive UI with Bootstrap styling
- 🧪 Input fields: Glucose, BMI, Age, Insulin, etc.

---

## 🛠 Tech Stack

- **Backend:** Django
- **Machine Learning:** Scikit-learn, Pandas, NumPy
- **Frontend:** HTML5, CSS3, Bootstrap
- **Data Source:** PIMA Indian Diabetes Dataset

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/kmrabhayak/Diabetes-Predictor.git
cd Diabetes-Predictor

# Create and activate virtual environment
python3 -m venv env
source env/bin/activate

# Install dependencies
pip install -r requirements.txt
```
---

### 🧪 Run the Project
```bash
python manage.py runserver
```

Open your browser and go to 
http://127.0.0.1:8000/ to start predicting!

---

### 📁 Project Structure
Diabetes-Predictor/

├── DiabetesPrediction/     # Django app

├── templates/              # HTML templates

├── static/                 # CSS, images

├── diabetes.ipynb          # Model training notebook

├── db.sqlite3              # Local DB

├── manage.py               # Django manager

└── requirements.txt        # Project dependencies


