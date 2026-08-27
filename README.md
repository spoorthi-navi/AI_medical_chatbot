# 🩺 AI Medical Chatbot

An AI-powered medical chatbot that analyzes user symptoms and predicts possible diseases using machine learning. The application is built with Python, Flask, HTML, CSS, and JavaScript.

> **Disclaimer:** This project is intended for educational and informational purposes only. It does not replace professional medical advice, diagnosis, or treatment.

## ✨ Features

* 🤖 AI-based symptom analysis
* 🩺 Disease prediction using machine learning
* 💬 Interactive chatbot interface
* 📊 Uses symptom and disease datasets
* 🌐 Flask-based web application
* 📱 Simple and user-friendly interface
* 📚 Provides information related to predicted conditions

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **Scikit-learn**
* **Pandas**
* **NumPy**
* **HTML**
* **CSS**
* **JavaScript**

## 🤖 Machine Learning

The application uses a **Random Forest Classifier** to predict a possible disease based on the symptoms provided by the user.

The project contains training and testing datasets in the `Data` directory and supporting medical information in the `MasterData` directory.

## 📁 Project Structure

```text
AI_medical_chatbot/
│
├── Data/
│   ├── Training.csv
│   ├── Testing.csv
│   └── dataset.csv
│
├── MasterData/
│   ├── symptom_severity.csv
│   ├── symptom_Description.csv
│   └── symptom_precaution.csv
│
├── api/
│   └── index.py
│
├── static/
│   ├── images/
│   ├── script.js
│   └── style.css
│
├── templates/
│   └── index.html
│
├── app.py
├── commands.txt
├── requirements.txt
└── .gitignore
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/spoorthi-navi/AI_medical_chatbot.git
cd AI_medical_chatbot
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

Start the Flask application:

```bash
python app.py
```

Then open the local address shown by Flask in your browser.

## 📌 Future Enhancements

* Improve prediction accuracy with additional datasets
* Add user authentication
* Add medical history tracking
* Improve chatbot responses
* Add voice-based interaction
* Deploy the application to the cloud
* Add more comprehensive medical information

## 👥 Contributors

**Spoorthi Navi**

Additional team members can be added here.

## 📄 License

This project is currently intended for educational purposes.
