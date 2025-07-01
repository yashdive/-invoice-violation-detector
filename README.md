
# 🧾 Invoice Violation Detection Using Machine Learning

Detect suspicious or non-compliant invoice line items using a trained AI model based on real-world patterns in financial data.


---

## 📌 Overview

In this project, we built a machine learning model to predict whether an invoice line item is likely to violate billing guidelines. The goal is to help financial or healthcare auditors automatically detect anomalie, such as:

- Missing prior authorization  
- Duplicate billing  
- Unnecessary procedures  
- Emergency misflags

This solution mimics a real-world enterprise use case and includes:
- Full preprocessing pipeline  
- SHAP-based explainability  
- Saved model artifacts  
- GitHub-ready structure

---

## 🚀 Features

- ✅ Preprocessing of categorical, numeric, and text data (`OneHotEncoder`, `TF-IDF`)
- ✅ Trained using `RandomForestClassifier`
- ✅ Global + local model interpretability with **SHAP**
- ✅ Model + vectorizers saved with `joblib`
- ✅ Ready for integration into APIs or Streamlit apps

---

## 📁 Project Structure

```
invoice-violation-detector/
├── data/
│   └── sample_invoice.csv
├── models/
│   ├── rf_model.pkl
│   ├── tfidf_vectorizer.pkl
│   ├── ohe_encoder.pkl
│   └── feature_columns.pkl
├── notebooks/
│   └── 01_model_dev.ipynb
├── src/
│   └── (optional scripts for inference or pipelines)
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🔍 SHAP Summary Plot

> Model interpretability is key to building trust.

![image](https://github.com/user-attachments/assets/16a20870-033b-4f7b-8f72-185799e18790)



- `requires_auth`, `is_duplicate`, and key terms like `"without"` have the strongest influence on the model’s decision.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Scikit-Learn | Model training |
| SHAP | Model explainability |
| Pandas, NumPy | Data manipulation |
| Matplotlib, Seaborn | Visualization |
| Joblib | Model serialization |

---

## 💡 Future Work

- 🔧 Build a real-time **Streamlit app** to upload and check invoices
- ☁️ Deploy as a REST API using **FastAPI or Flask**
- 📦 Add unit tests and CI/CD for production deployment
- 🧠 Try XGBoost or LLMs for enhanced NLP understanding



## 🙋‍♂️ About Me

👋 I'm [Yash Dive](https://github.com/YashDive), a full-stack developer transitioning into AI/ML.  
This project is part of my journey toward mastering enterprise-grade AI solutions.

Connect with me:
- 📧 yashdive190@gmail.com 
- 💼 [LinkedIn](https://linkedin.com/in/yash2131) 

