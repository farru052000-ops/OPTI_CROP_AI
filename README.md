# 🌱 OptiCrop – AI-Based Crop Recommendation System

OptiCrop is a Machine Learning-based web application that recommends the most suitable crop based on soil nutrients and environmental conditions. It helps farmers make informed decisions by analyzing soil parameters and predicting the best crop for cultivation.

---

## 📖 Project Overview

Selecting the right crop is one of the biggest challenges faced by farmers. Soil nutrients and climatic conditions greatly influence crop productivity. OptiCrop uses Machine Learning to analyze these factors and instantly recommend the most suitable crop.

The application is built using **Python, Flask, HTML, CSS, and Scikit-learn** and provides a simple web interface where users can enter soil and environmental parameters to receive an accurate crop recommendation.

---

## 🎯 Problem Statement

Farmers often struggle to decide which crop is best suited for their land due to changing soil conditions and environmental factors. Incorrect crop selection can reduce yield and increase financial losses.

OptiCrop solves this problem by recommending the most suitable crop using Machine Learning based on:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

---

## ✨ Features

- 🌾 AI-Based Crop Recommendation
- 📊 Machine Learning Prediction
- ⚡ Real-Time Prediction
- 📱 Responsive User Interface
- 🌍 Web-Based Application
- 🔍 Data Preprocessing
- 📈 Model Training & Evaluation
- ☁️ Render Deployment
- 📂 GitHub Version Control

---

## 🛠 Technology Stack

### Frontend
- HTML5
- CSS3

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- NumPy
- Joblib

### Development Tools
- VS Code
- Git
- GitHub

### Deployment
- Render

---

## 📁 Project Structure

```
Agriculture/
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
│
├── dataset/
│   └── Crop_recommendation.csv
│
├── model/
│   ├── model.pkl
│   └── scaler.pkl
│
├── templates/
│   ├── home.html
│   ├── about.html
│   └── findyourcrop.html
│
├── static/
│   ├── css/
│   └── images/
│
└── notebook/
    └── Crop_Recommendation.ipynb
```

---

## 📊 Dataset Information

- Dataset Size: **2200 Records**
- Number of Features: **7**
- Target Classes: **22 Crops**

### Input Features

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

### Output

Recommended Crop

---

## 🌾 Supported Crops

- Rice
- Maize
- Chickpea
- Kidney Beans
- Pigeon Peas
- Moth Beans
- Mung Bean
- Black Gram
- Lentil
- Pomegranate
- Banana
- Mango
- Grapes
- Watermelon
- Muskmelon
- Apple
- Orange
- Papaya
- Coconut
- Cotton
- Jute
- Coffee

---

## 🤖 Machine Learning Models Used

The following Machine Learning algorithms were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gaussian Naive Bayes

### Model Performance

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 96.36% |
| KNN | 95.68% |
| Decision Tree | 98.64% |
| Random Forest | 99.32% |
| Naive Bayes | **99.55%** |

The best-performing model is saved as **model.pkl**.

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/farru052000-ops/Agriculture.git
```

### Navigate to Project Folder

```bash
cd Agriculture
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

The application will run at:

```
http://127.0.0.1:5000/
```

---

## 🌐 Live Demo

**Render Deployment**

https://opti-crop-ai-1.onrender.com

---

## 📸 How to Use

1. Open the OptiCrop website.
2. Click on **Find Your Crop**.
3. Enter:
   - Nitrogen (N)
   - Phosphorus (P)
   - Potassium (K)
   - Temperature
   - Humidity
   - pH
   - Rainfall
4. Click **Predict**.
5. View the recommended crop.

---

## 📈 Future Enhancements

- Fertilizer Recommendation System
- Weather Forecast Integration
- Crop Disease Detection
- Crop Yield Prediction
- User Authentication
- Farmer Dashboard
- Database Integration
- Mobile Application
- Multi-language Support

---

## 📷 Screenshots

Add screenshots of:

- Home Page
- About Page
- Crop Recommendation Form
- Prediction Result

---

## 📚 Requirements

```
Flask
numpy
pandas
scikit-learn
joblib
gunicorn
```

---

## 👩‍💻 Developer

**Farru Farnaz**

B.Tech – Computer Science & Engineering

---

## 📄 License

This project is developed for educational and academic purposes only.

---

## ⭐ Support

If you found this project useful, please ⭐ star this repository on GitHub.

Thank you!