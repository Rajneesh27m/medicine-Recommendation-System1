Personalized Medicine Recommendation System with Machine Learning

This is an AI-powered healthcare project that predicts potential diseases based on user symptoms and provides personalized health recommendations including medications, precautions, diets, and workouts.

## 🚀 Overview
The system uses a Support Vector Classifier (SVC) model trained on a medical dataset to provide accurate disease predictions. The backend is built using Flask, making it a lightweight and efficient web application.

### Key Features:
* Disease Prediction: Predicts 40+ diseases based on symptoms input.
* Medication Advice: Suggests relevant medicines for the predicted disease.
* Health Plans: Provides customized Diet and Workout recommendations.
* Safety First: Shows necessary precautions to take for each condition.

---

## 🛠️ Tech Stack
* Language: Python
* Machine Learning: Scikit-learn (SVC), Pandas, NumPy
* Web Framework: Flask
* Frontend: HTML, CSS, Bootstrap

---

## 📁 Project Structure
`text
├── datasets/           # Contains all CSV data files
├── models/             # Contains the trained svc.pkl model
├── templates/          # HTML files for the web interface
├── main.py             # Main Flask application file
└── Training.csv        # Dataset used for model training
