# 🦠 Monkeypox Disease Detection using Machine Learning

A web-based application that predicts **Monkeypox disease** using Machine Learning, built with **Python** and **Django**. The project compares multiple ML algorithms and achieves a best prediction accuracy of **99%** using **AdaBoost**.

---

## 📌 About the Project

Monkeypox and COVID-19 share similar symptoms like fever, fatigue, cough, sore throat, and body pains. This project trains and compares multiple ML algorithms — **LDA, MLP, and AdaBoost** — to predict Monkeypox disease and integrates the best-performing model into a Django web application for real-time prediction.

---

## 🧠 ML Algorithm Accuracy Comparison

| Algorithm | Accuracy |
|---|---|
| 🥇 AdaBoost | 99% |
| MLP (Multi-Layer Perceptron) | ~98% |
| LDA (Linear Discriminant Analysis) | ~97% |

---

## ✨ Features

- 🔐 User Registration & Login
- 🧠 Monkeypox Disease Prediction using AdaBoost
- 📊 Dataset Analysis & Visualization
- 📱 Responsive UI with Bootstrap

---

## 🛠️ Tools & Technologies

| Category | Technology |
|---|---|
| Language | Python |
| Web Framework | Django |
| Machine Learning | Scikit-learn (LDA, MLP, AdaBoost) |
| Notebook | Jupyter Notebook (.ipynb) |
| Data Analysis | Pandas, NumPy |
| Frontend | HTML, CSS, Bootstrap |
| Database | SQLite (`db.sqlite3`) |
| IDE | VS Code |

---

## 📁 Project Structure

```
CODE/
│
├── BACKEND/
│   ├── monkeypox_covid_dataset.csv      # Dataset used for training
│   └── monkeypox.ipynb                  # Jupyter notebook (model training & analysis)
│
├── FRONTEND/
│   └── detection/                       # Django project
│       ├── app/                         # Main Django app
│       │   ├── __pycache__/
│       │   ├── migrations/
│       │   ├── static/                  # CSS, JS, images
│       │   ├── templates/               # HTML templates
│       │   ├── __init__.py
│       │   ├── admin.py
│       │   ├── apps.py
│       │   ├── models.py
│       │   ├── monkeypox_covid_dataset.csv
│       │   ├── tests.py
│       │   ├── urls.py
│       │   └── views.py                 # ML model integration & logic
│       │
│       ├── catboost_info/
│       ├── detection/                   # Django settings module
│       ├── static/
│       ├── templates/
│       ├── venv/                        # Virtual environment
│       ├── .gitignore
│       ├── db.sqlite3                   # SQLite database
│       ├── fraud                        
│       ├── manage.py                    # Django entry point
│       ├── readme.txt
│       └── req.txt                      # Python dependencies
│
└── README.md
```

---

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Ajay-Bandike/monkeypox-detection.git
cd monkeypox-detection
```

### 2. Create & Activate Virtual Environment
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate
```

### 3. Install Requirements
```bash
pip install -r req.txt
```

### 4. Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the Server
```bash
python manage.py runserver
```

### 6. Open in Browser
```
http://127.0.0.1:8000/
```

---

## 📬 Contact

**Ajay Bandike**

| Platform | Details |
|---|---|
| 📧 Email | bandikeajay1234@gmail.com |
| 💼 LinkedIn | [linkedin.com/in/bandike-ajay-b8170824a](http://www.linkedin.com/in/bandike-ajay-b8170824a) |
| 🐙 GitHub | [github.com/Ajay-Bandike](https://github.com/Ajay-Bandike) |

---

© 2025 Ajay Bandike. All rights reserved.
