# 🌊 Water Quality Prediction - AICTE Virtual Internship (Shell, June 2025)

This project aims to **predict multiple water quality parameters** using machine learning techniques, specifically a **`MultiOutputRegressor`** wrapped around a **`RandomForestRegressor`**. It was developed as part of a **one-month AICTE Virtual Internship sponsored by Shell** in **June 2025**.

---

## 🚀 Project Overview

Access to **clean water** is a critical global concern. Manual testing of water samples is **time-consuming** and **resource-intensive**. This project leverages **machine learning** to estimate key chemical parameters of water from existing sensor/test data, enabling **faster and automated monitoring**.

---

## 🔬 Predicted Parameters

The model is trained to predict the following water quality indicators:

- **NO3** (Nitrates)
- **NO2** (Nitrites)
- **PO4** (Phosphates)
- **CL** (Chloride)
- **O2** (Dissolved Oxygen)

---

## 🧠 Technologies Used

- **Python 3.12**
- **Pandas, NumPy** – Data preprocessing & manipulation  
- **Scikit-learn** – Model training and evaluation  
- **Matplotlib, Seaborn** – Data visualization  
- **Streamlit** – Web app for user interaction  
- **Joblib** – Model serialization  
- **Jupyter Notebook** – Experimentation and analysis  

---

## 🛠️ Methodology

1. **Data Collection** – Real-world water quality dataset  
2. **Preprocessing** – Cleaning, feature selection, train-test split  
3. **Modeling** – Multi-target regression using **`RandomForestRegressor`**  
4. **Evaluation** – **R² Score** and **Mean Squared Error (MSE)**  
5. **Deployment** – Streamlit app using a custom **`app.py`** file  

---

## 📊 Results

The model achieved **acceptable accuracy** across all predicted parameters, validated using regression metrics. A **Streamlit app** was created to allow **real-time predictions** through an **interactive interface**.

## 🔗 Download Model Files

The trained model file is too large for GitHub. You can download it from the link below:

- [📥 Download pollution_model.pkl and model_columns.pkl from Google Drive](https://drive.google.com/drive/folders/1iuItQAR1W8cpyPZjt2BA-FLsZ4PiwdFd?usp=drive_link)


