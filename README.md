# Health Insurance Claim Predictor 🏥

A machine learning web application that predicts whether an individual will file a health insurance claim based on their profile.

---

## 📊 Overview

This project helps insurance companies assess potential claim risk by analyzing key health and lifestyle attributes of policyholders using a predictive ML model.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Insurance Claim Analysis.ipynb` | Data exploration, visualization, and model training notebook |
| `insurance_data.csv` | Dataset used for training the model |
| `insurance.pkl` | Trained ML model saved using `joblib` or `pickle` |
| `app.py` | Streamlit web app to take user input and show predictions |
| `retrain_model.py` | Script to retrain the model with new data |
| `requirements.txt` | List of Python dependencies |
| `output.html` | Exported report (optional) |
| `.gitignore` | Prevents tracking unnecessary files |

---

## 🧠 Features

- Predicts insurance claim possibility
- Simple and interactive UI using Streamlit
- Model retraining enabled via script
- Cleaned and preprocessed dataset with categorical encoding
- Exploratory Data Analysis included in Jupyter notebook

---

## ⚙️ How to Run

### 1. Clone the Repo
```bash
git clone https://github.com/<your-username>/Health-Insurance-Claim-Predictor.git
cd Health-Insurance-Claim-Predictor
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Streamlit App
```bash
streamlit run app.py
```

---

## 📈 Model Training

- **Target variable**: `insuranceclaim`
- **Features used**: `age`, `bmi`, `children`, `smoker`, `region`, etc.
- **Algorithms tested**: Logistic Regression, Random Forest
- **Evaluation metrics**: Accuracy, Precision, Confusion Matrix

---

## 📦 Tools Used

- Python
- pandas, NumPy
- scikit-learn
- Streamlit
- Matplotlib & Seaborn

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Author

Created as part of a practical machine learning module to understand real-world insurance applications.
