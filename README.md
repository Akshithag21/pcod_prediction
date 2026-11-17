# 🌸 FemCare – pcod_prediction

A machine learning-powered web application that helps women estimate their **Polycystic Ovarian Disease (PCOD) risk** using common health indicators, lifestyle habits, and symptoms.

The system also evaluates **mental health conditions** using standardized screening tools and provides personalized health recommendations.

This project demonstrates how **machine learning models can be integrated into a real-world healthcare awareness application using Flask**.

---

# 🚀 Features

### PCOD Risk Prediction

Predicts the probability of PCOD using a trained machine learning model based on health symptoms and lifestyle factors.

### Risk Categorization

The system categorizes results into:

- No Significant Risk
- Low Risk
- Moderate Risk
- High Risk
- Very High Risk

### Mental Health Screening

Includes standardized psychological screening tools:

- **GAD-7** – Anxiety Assessment
- **PHQ-9** – Depression Assessment

### AI-Based Personalized Advice

Based on prediction results and mental health scores, the system generates suggestions related to:

- Diet
- Lifestyle
- Exercise
- Mental health well-being

### Responsive Web Application

The application is built with **Flask** and provides a simple, user-friendly interface.

---

# 📊 Machine Learning Workflow

The project follows a complete machine learning pipeline:

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Feature Selection
6. Model Training
7. Model Evaluation
8. Model Deployment

---

# 📁 Dataset

The dataset used for training the model contains patient health records related to **PCOD symptoms and lifestyle factors**.

Example features used in the model:

- Age (yrs)
- Weight (Kg)
- Height (Cm)
- Cycle Regularity
- Cycle Length (days)
- Marriage Status (years)
- Pregnancy Status
- Number of Abortions
- Weight Gain
- Hair Growth
- Skin Darkening
- Hair Loss
- Pimples
- Fast Food Consumption
- Regular Exercise

**Target variable:**

```text
Target = 1 → PCOD present
Target = 0 → No PCOD
```

---

# 🧠 Machine Learning Models Tested

Several classification algorithms were evaluated:

- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine
- Decision Tree
- Random Forest
- XGBoost Random Forest
- CatBoost Classifier

The **CatBoost model** provided the most stable and accurate results and was selected as the final prediction model.

The trained model is saved as:

```text
model_joblib.pkl
```

---

# 🧪 Mental Health Assessment

The system also evaluates mental health using two standardized screening questionnaires.

### GAD-7 – Anxiety Screening

Measures the severity of generalized anxiety.

Levels:

- Minimal Anxiety
- Mild Anxiety
- Moderate Anxiety
- Severe Anxiety

### PHQ-9 – Depression Screening

Measures depression severity.

Levels:

- Minimal Depression
- Mild Depression
- Moderate Depression
- Moderately Severe Depression
- Severe Depression

---

# 🖥 Application Workflow

```text
User
  ↓
index.html (User Input Form)
  ↓
Flask Backend (app.py)
  ↓
Data Preprocessing
  ↓
Machine Learning Model (CatBoost)
  ↓
PCOD Risk Prediction
  ↓
Mental Health Evaluation
  ↓
Personalized AI Suggestions
  ↓
result.html (Result Page)
```

---

## 🛠 Tech Stack

| Component | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Python Flask |
| Machine Learning | Scikit-learn, CatBoost |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |

---

# ⚙ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Akshithag21/pcod_prediction.git
cd pcod_prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

### 4. Open the application in your browser

```text
http://127.0.0.1:5000
```

---

# 📂 Project Structure

```text
PCOD-Risk-Predictor
│
├── PCOD.ipynb
├── PCOD_data.csv
├── model_joblib.pkl
├── app.py
├── templates
│   ├── index.html
│   └── result.html
│
├── requirements.txt
└── README.md
```

---

# 📈 Future Improvements

- Improve dataset size and diversity.
- Add Explainable AI (SHAP feature importance).
- Build a mobile application version.
- Add user health history tracking.
- Integrate real medical APIs for guidance.

---

# ⚠ Disclaimer

This tool is designed **for educational and awareness purposes only**.

It does not replace professional medical diagnosis or treatment.

If you experience symptoms related to PCOD, consult a qualified healthcare professional.

---

### GitHub Profile

**Naga Akshitha Gunuguntla**

[GitHub – Akshithag21](https://github.com/Akshithag21)
