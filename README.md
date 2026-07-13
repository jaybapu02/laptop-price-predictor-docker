# 💻 Laptop Price Predictor

## 📌 Overview

Laptop Price Predictor is a Machine Learning web application that predicts the price of a laptop based on its specifications such as brand, processor, RAM, storage, display features, operating system, and other hardware configurations.

The project uses data preprocessing, feature engineering, and an Extra Trees Regression model to provide accurate price predictions through an interactive Streamlit-based user interface.

---

## 🚀 Features

* Predict laptop prices in real time
* User-friendly Streamlit interface
* Supports multiple laptop brands and configurations
* Feature engineering for improved prediction accuracy
* Machine Learning model trained on real-world laptop data

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries & Frameworks

* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

### Machine Learning

* Extra Trees Regressor
* One-Hot Encoding
* Data Preprocessing & Feature Engineering

---

## 📂 Project Structure

```text
Laptop-Price-Predictor/
│
├── app.py
├── pipe.pkl
├── df.pkl
├── laptop_data.csv
├── requirements.txt
├── runtime.txt
├── Procfile
├── Dockerfile
├── setup.sh
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/laptop-price-predictor.git
cd laptop-price-predictor
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser at:

```text
http://localhost:8501
```

---

## 📊 Input Features

The model uses the following laptop specifications:

* Company
* Type Name
* RAM
* Weight
* Touchscreen
* IPS Display
* Screen Size
* Screen Resolution
* CPU Brand
* HDD Storage
* SSD Storage
* GPU Brand
* Operating System

---

## 🧠 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Model Training
6. Model Evaluation
7. Deployment using Streamlit

---

## 📈 Model Performance

The model was trained using the Extra Trees Regression algorithm and evaluated using:

* R² Score
* Mean Absolute Error (MAE)

---

## 🌐 Deployment

The project can be deployed using:

* Streamlit Community Cloud
* Render
* Docker
* AWS
* Azure

---

## 📜 License

This project is created for educational and learning purposes.

---

## 👨‍💻 Author

Jaychandra Das

Engineering Student | Machine Learning Enthusiast | Python Developer | Tech Explorer
