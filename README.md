# Heart-Disease-Prediction
# 💓 Heart Disease Prediction App
A **Machine Learning–based Streamlit Web App** that predicts the likelihood of heart disease based on various medical input parameters.  
Built using a **Logistic Regression model** trained on the classic Heart Disease dataset.
---
## 🚀 Features
- 🩺 Predicts heart disease risk instantly.  
- 💡 Clean and modern UI built with **Streamlit**.  
- ❤️ Animated flying heart (❤️ / 💔) when prediction is made.  
- ⚙️ Model integrated using **Pickle (.sav)** file.  
- 📊 User-friendly input sliders, dropdowns, and number fields.  
---
## 🧠 Tech Stack
| Component | Technology |
|------------|-------------|
| Frontend | Streamlit |
| Backend | Python |
| ML Model | Logistic Regression |
| Data Handling | NumPy, Pandas |
| Model Storage | Pickle (.sav) |

---
## 📦 Project Structure
```
📁 Heart_Disease_Prediction/
│
├── app.py                        # Streamlit main app file
├── heart_disease_model.sav       # Trained ML model (pickle file)
├── requirements.txt               # Dependencies list
├── README.md                      # Project documentation (this file)
└── dataset.csv                    # (Optional) Dataset used for training

````

---

## ⚙️ Installation and Setup
### 1️⃣ Clone this repository
```bash
git clone https://github.com/yourusername/heart-disease-predictor.git
cd heart-disease-predictor
````
### 2️⃣ Create and activate a virtual environment (optional)

```bash
python -m venv venv
venv\Scripts\activate   # (Windows)
source venv/bin/activate  # (Mac/Linux)
```
### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

### 5️⃣ Open in your browser

The app will open automatically at:
👉 [http://localhost:8501](http://localhost:8501)

---
## 🧩 Input Features

| Feature                 | Description                    |
| ----------------------- | ------------------------------ |
| Age                     | Age of the person              |
| Sex                     | Male/Female                    |
| Chest Pain Type         | 0–3                            |
| Resting BP              | Resting Blood Pressure (mm Hg) |
| Cholesterol             | Serum Cholesterol (mg/dl)      |
| Fasting Blood Sugar     | >120 mg/dl (Yes/No)            |
| Resting ECG             | 0–2                            |
| Max Heart Rate          | Maximum heart rate achieved    |
| Exercise Induced Angina | Yes/No                         |
| ST Depression           | Oldpeak value                  |
| Slope                   | Slope of ST segment (0–2)      |
| Major Vessels           | Number of major vessels (0–4)  |
| Thalassemia             | 1–3                            |

---

## 💥 Output

* ✅ **No Heart Disease** → Flying ❤️ animation
* ⚠️ **Heart Disease Detected** → Flying 💔 animation

---

## 🧪 Example Screenshot

<img width="567" height="699" alt="image" src="https://github.com/user-attachments/assets/463fc9a7-c96f-4c7c-b6a6-56b5a48e6d32" />


```
📸 Example: Heart Disease Prediction App UI
```

---

## 📚 Requirements

Add this in your `requirements.txt`:

```text
streamlit
numpy
scikit-learn
pickle-mixin
```

---

## 👨‍💻 Developed By

**Kathi Varshith**
💻 AI & ML Enthusiast | Data Science Learner
📧 kathivarshithgoud59@gmail.com
🌐 https://www.linkedin.com/in/kathi-varshith1114/

---

> “Developed with ❤️ using Streamlit and Machine Learning.”


