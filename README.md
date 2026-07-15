🌱 OptiCrop – AI-Based Crop Recommendation System

An intelligent Machine Learning-based web application that recommends the most suitable crop based on soil nutrients and environmental conditions. The application helps farmers make informed decisions, improve crop productivity, and promote sustainable agriculture.

📌 Project Overview

OptiCrop uses a trained Machine Learning model to analyze soil and environmental parameters and recommend the best crop for cultivation.

Users simply enter:

Nitrogen (N)
Phosphorus (P)
Potassium (K)
Temperature
Humidity
pH Value
Rainfall

The system instantly predicts the most suitable crop using a trained Machine Learning model.

🎯 Problem Statement

Farmers often face difficulty in selecting the most suitable crop because of changing soil conditions and environmental factors. Choosing an unsuitable crop can reduce productivity and increase financial losses.

OptiCrop solves this problem by providing accurate crop recommendations based on soil nutrients and climatic conditions using Machine Learning.

✨ Features
🌾 Crop Recommendation using Machine Learning
📊 Data Preprocessing with StandardScaler
🧠 Multiple ML Algorithms Comparison
🌐 User-Friendly Flask Web Application
📱 Responsive HTML & CSS Interface
⚡ Real-Time Prediction
☁️ Render Deployment
📂 GitHub Version Control
🛠 Technology Stack
Frontend
HTML5
CSS3
Backend
Python
Flask
Machine Learning
Scikit-learn
Pandas
NumPy
Joblib
Deployment
Render
Version Control
Git & GitHub
📁 Project Structure
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
📊 Dataset

The project uses the Crop Recommendation Dataset containing 2200 records and 22 crop classes.

Input Features
Nitrogen (N)
Phosphorus (P)
Potassium (K)
Temperature
Humidity
pH
Rainfall
Output

Recommended Crop

Examples include:

Rice
Maize
Chickpea
Kidney Beans
Pigeon Peas
Banana
Mango
Cotton
Coffee
Apple
Coconut
Orange
Papaya
Grapes
Watermelon
Muskmelon
Jute
Lentil
Blackgram
Mungbean
Mothbeans
Pomegranate
🤖 Machine Learning Models Used

The following algorithms were trained and evaluated:

Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Gaussian Naive Bayes
Model Accuracy
Model	Accuracy
Logistic Regression	96.36%
KNN	95.68%
Decision Tree	98.64%
Random Forest	99.32%
Naive Bayes	99.55%

The best-performing model is saved as model.pkl.

🚀 Installation

Clone the repository

git clone https://github.com/farru052000-ops/Agriculture.git

Move into the project folder

cd Agriculture

Create a virtual environment

python -m venv venv

Activate the virtual environment

Windows

venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

Run the application

python app.py
🌐 Live Demo

Render Deployment

https://opti-crop-ai-1.onrender.com

📸 Application Workflow
Open the OptiCrop website.
Navigate to the Crop Recommendation page.
Enter:
Nitrogen
Phosphorus
Potassium
Temperature
Humidity
pH
Rainfall
Click Predict.
View the recommended crop.
📈 Future Enhancements
Fertilizer Recommendation
Weather Forecast Integration
Crop Disease Detection
Yield Prediction
Multi-language Support
Farmer Login System
Database Integration
Mobile Application
👩‍💻 Developed By

Farru Farnaz

B.Tech – Computer Science & Engineering

📄 License

This project is developed for educational and academic purposes.

⭐ If you found this project useful, consider giving it a Star on GitHub!