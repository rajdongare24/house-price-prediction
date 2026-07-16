# 🏠 House Price Prediction using Machine Learning

An end-to-end Machine Learning web application that predicts residential property prices in Bangalore based on user inputs such as location, BHK, bathrooms, and total square feet.

The application is built using **Python, Scikit-learn, Flask, Pandas, NumPy, HTML, Bootstrap, and JavaScript**.

---

## 📌 Features

- Predicts house prices in real time
- User-friendly web interface built with Flask
- Supports multiple Bangalore locations
- Input validation for realistic property values
- Reset button to clear all inputs
- Responsive UI using Bootstrap

---

## 🛠️ Tech Stack

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML
- Bootstrap
- JavaScript
- Jupyter Notebook

---

## 📊 Dataset

- Bangalore Housing Price Dataset
- Over **13,000 property records**
- Features include:
  - Location
  - Total Square Feet
  - Number of Bathrooms
  - BHK

---

## 🔍 Machine Learning Workflow

- Data Cleaning
- Missing Value Treatment
- Feature Engineering
- Outlier Removal
- One-Hot Encoding
- Model Training
- Hyperparameter Tuning using GridSearchCV
- 5-Fold Cross Validation
- Model Serialization using Pickle
- Flask Deployment

---

## 🤖 Models Evaluated

- Linear Regression
- Lasso Regression
- Ridge Regression

The final model was selected using **GridSearchCV with 5-fold Cross Validation**.

---

## 📈 Model Performance

- **R² Score:** ~0.82

---

## 📂 Project Structure

```
House-Price-Prediction/
│
├── data/
│   └── Cleaned_data.csv
│
├── model/
│   └── RidgeModel.pkl
│
├── templates/
│   └── index.html
│
├── app.py
├── model_training.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/rajdongare24/house-price-prediction.git
```

Move into the project directory

```bash
cd house-price-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5001
```

---

## 👨‍💻 Author

**Raj Dongare**

- GitHub: https://github.com/rajdongare24
