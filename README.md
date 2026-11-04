
# Hate Speech Detection Web Application

A full-stack Machine Learning web application that detects and classifies text into **Hate Speech, Offensive Language, or No Hate** using Natural Language Processing (NLP) techniques.

The application integrates a trained Machine Learning model with a Flask backend and an interactive frontend, providing instant text classification through a web interface.

## 🚀 Live Demo

**Live Application:** [Open Web Application](https://hate-speech-flask-app.onrender.com/)

## 📌 Project Overview

The Hate Speech Detection Web Application allows users to enter text and receive an instant classification result.

It uses TF-IDF vectorization for text feature extraction and a trained Scikit-learn classifier to identify harmful or offensive language.

The application includes:
- Flask-based backend API.
- Machine Learning model for text classification.
- Interactive frontend built with HTML, CSS, and JavaScript.
- Cloud deployment using Render.

## 📂 Project Structure

```text
hate-speech-flask-app/
│
└── Backend/
    ├── app.py
    ├── hate_model.pkl
    ├── tfidf_vectorizer.pkl
    ├── requirements.txt
    ├── Procfile
    ├── runtime.txt
    ├── .python-version
    │
    └── frontend/
        ├── index.html
        ├── style.css
        └── script.js
```

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python 3.10 |
| Backend | Flask, Flask-CORS |
| Machine Learning | Scikit-learn |
| NLP | NLTK, TF-IDF |
| Model Serialization | Joblib |
| Frontend | HTML, CSS, JavaScript |
| Deployment | Render |
| Version Control | GitHub |

## 🧠 Machine Learning Implementation

The application uses Natural Language Processing and supervised Machine Learning techniques.

- **TF-IDF Vectorization:** Converts text data into numerical features for model prediction.
- **Text Classification:** A trained Scikit-learn classifier predicts the category of the input text.
- **Joblib:** Saves and loads the trained model and TF-IDF vectorizer.

## ✨ Key Features

- Real-time text classification.
- Detection of hate speech and offensive language.
- Three-category prediction system.
- Simple and interactive user interface.
- Flask REST API integration.
- Cloud-hosted web application.

## 🔄 Application Workflow

1. User enters text through the frontend.
2. Frontend sends the input to the Flask backend.
3. Text is processed using the TF-IDF vectorizer.
4. The trained ML model predicts the text category.
5. The prediction is returned and displayed on the frontend.

**Workflow:**

`User Input → Frontend → Flask API → TF-IDF → ML Model → Prediction Result`

## ☁️ Build and Deployment

The application is deployed on the Render cloud platform.

Deployment configuration includes:
- Gunicorn production server.
- Python runtime configuration.
- Requirements-based dependency installation.
- GitHub-based source code management.
- Automated cloud builds.

## 📊 Project Outcome

Developed and deployed a full-stack Machine Learning application capable of classifying user-provided text into three categories:

- **No Hate**
- **Offensive Language**
- **Hate Speech**

The application provides an accessible web interface for automated text classification.

## 🔮 Future Enhancements

- Improve classification performance.
- Support multilingual hate speech detection.
- Experiment with advanced NLP and deep learning models.
- Enhance model evaluation and prediction confidence.

## 📄 License

This project is developed for educational and demonstration purposes.
