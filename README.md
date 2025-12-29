# 💓 Heart Disease Prediction using Random Forest

A machine learning project that predicts the presence or absence of heart disease in patients using clinical and diagnostic features with a Random Forest classifier.

## 📊 Dataset Overview

The project uses a heart disease prediction dataset containing **14 features**:

| Feature                  | Description                                     |
|--------------------------|-------------------------------------------------|
| Age                      | Patient's age                                   |
| Sex                      | Gender (0=Female, 1=Male)                       |
| Chest pain type          | Type of chest pain experienced                  |
| BP                       | Blood pressure reading                          |
| Cholesterol              | Serum cholesterol level                         |
| FBS over 120             | Fasting blood sugar > 120 mg/dl (1=True, 0=False)|
| EKG results              | Electrocardiographic results                    |
| Max HR                   | Maximum heart rate achieved                     |
| Exercise angina          | Exercise-induced angina (1=Yes, 0=No)           |
| ST depression            | ST depression induced by exercise               |
| Slope of ST              | Slope of the peak exercise ST segment           |
| Number of vessels fluro  | Number of major vessels colored by fluoroscopy  |
| Thallium                 | Thallium stress test results                    |
| Heart Disease            | **Target variable**: Presence or Absence        |

## 🚀 Features

- **Data Loading & Preprocessing:** Automated CSV data loading and label encoding
- **Random Forest Classification:** Robust ensemble learning algorithm
- **Model Evaluation:** Confusion matrix and visualization tools
- **Model Persistence:** Save and load trained models using joblib
- **Visualization:** Matplotlib integration for result plotting


## 🚀 Highlights

- Accurate Random Forest classifier in Python
- User-friendly data preprocessing and analysis
- Visual Confusion Matrix for model clarity
- Save your trained model with joblib

---

## ⚙️ Quick Start

1. **Download/clone the repository**
2. **Install Python dependencies (once):**
3. **Open and run the notebook in Jupyter:**
4. **Dataset:** Make sure `Heart_Disease_Prediction.csv` is in the same folder.

---

## 🧠 How It Works

- Loads, explores, and encodes the data
- Splits dataset for training/validation
- Trains Random Forest model on features
- Evaluates with confusion matrix and accuracy
- Saves model using joblib for later use

---

## 📈 Example Output

- Data sample preview
- Complete model configuration
- Confusion Matrix plot
- Model accuracy
<img width="498" height="455" alt="413f3bc4-7204-4ac1-a87a-68625817515f" src="https://github.com/user-attachments/assets/47a5dd75-9f37-4574-abbb-bfbb8742a204" />

---

## 📦 Files

- `heart_attack_classifier.ipynb` – Main notebook
- `Heart_Disease_Prediction.csv` – Data
- `trained_model.joblib` – Trained model

---

## 🤝 Contributions

Open to pull requests, feature ideas, and issue reports!

---

## 📝 License

MIT License

---

_Made with ❤️ by [Karanpr-18](https://github.com/Karanpr-18)_

