# Creditworthiness Prediction

## Machine Learning Based Credit Scoring Prediction System

**Internship Project**
**Author:** Aadesh Khollam

---

## 📌 Project Overview

Creditworthiness Prediction is a Machine Learning project that predicts whether a customer is creditworthy based on their financial and personal information.

The system analyzes customer-related features and uses a trained machine learning model to classify applicants into different credit risk categories.

This project demonstrates the complete Machine Learning workflow:

* Data preprocessing
* Exploratory Data Analysis
* Model training
* Model evaluation
* Prediction using trained model

---

## 🎯 Objective

The main objective of this project is to build a machine learning model that can help financial institutions evaluate the credit risk of customers and support faster decision-making.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook
* Machine Learning Algorithms
* Git & GitHub

---

## 📂 Project Structure

```
Creditworthiness---Prediction
│
├── dataset
│   └── credit_data.csv
│
├── models
│   └── credit_model.pkl
│
├── notebooks
│   └── credit_prediction.ipynb
│
├── src
│   ├── train.py
│   ├── predict.py
│   └── preprocessing.py
│
├── requirements.txt
│
└── README.md
```

---

## 📊 Dataset

The dataset contains customer financial information used for predicting creditworthiness.

Features include:

* Income information
* Loan details
* Credit history
* Financial attributes
* Customer profile information

The dataset is processed before being used for model training.

---

## ⚙️ Machine Learning Workflow

### 1. Data Collection

The credit dataset is loaded and analyzed.

### 2. Data Preprocessing

Steps performed:

* Handling missing values
* Data cleaning
* Feature transformation
* Preparing data for model training

### 3. Model Training

The processed dataset is used to train a machine learning classification model.

The trained model is saved as:

```
models/credit_model.pkl
```

### 4. Prediction

The trained model predicts the creditworthiness of new customers.

---

## 🚀 Installation and Setup

Clone the repository:

```
git clone https://github.com/aadeshkhollam-hub/Creditworthiness---Prediction.git
```

Navigate into the project folder:

```
cd Creditworthiness---Prediction
```

Install required libraries:

```
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Train the Model

```
python src/train.py
```

### Make Predictions

```
python src/predict.py
```

---

## 📈 Model Output

The model predicts whether a customer is suitable for credit approval based on the provided financial information.

---

## 🔮 Future Improvements

Possible improvements:

* Add a web-based user interface
* Deploy the model using Flask/Streamlit
* Improve model accuracy with advanced algorithms
* Add real-time credit scoring API

---

## 👨‍💻 Author

**Aadesh Khollam**

Machine Learning Internship Project
