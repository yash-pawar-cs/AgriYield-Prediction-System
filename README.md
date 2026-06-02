# 🌾 AgriYield Predictor

### AI-Powered Crop Yield Prediction System

---

## 🚀 Overview

AgriYield Predictor is a machine learning-based web application that predicts crop yield and total production based on real-world agricultural inputs such as rainfall, temperature, humidity, soil type, and nutrient values.

This system is designed to assist farmers, researchers, and agricultural planners in making data-driven decisions.

---

## 🎯 Features

* 🌱 Crop Yield Prediction (tons/hectare)
* 📊 Total Production Estimation
* 🤖 AI-Based Insights & Explanation
* 🔄 Auto NPK Estimation (if unknown)
* 📄 Downloadable PDF Report
* 🎨 Modern Glassmorphism UI Design
* ⚡ Real-time Prediction using Flask

---

## 🧠 Machine Learning

### Input Features

* State
* Crop
* Rainfall
* Temperature
* Humidity
* Soil Type
* N, P, K values
* pH level

### Output

* Predicted Yield (tons/hectare)
* Estimated Production (tons)

---

## 🛠️ Tech Stack

| Component        | Technology            |
| ---------------- | --------------------- |
| Backend          | Flask (Python)        |
| Frontend         | HTML, CSS, JavaScript |
| Machine Learning | Scikit-learn          |
| Data Processing  | Pandas                |
| Model Storage    | Joblib                |
| PDF Reports      | ReportLab             |

---

## 📂 Project Structure

```text
AgriYield-Predictor/
│
├── app.py
├── requirements.txt
├── README.md
│
├── data/
│   ├── crop_npk_avg.csv
│   └── state_crop_npk_avg.csv
│
├── models/
│   └── best_crop_yield_model.pkl
│
├── notebooks/
│   └── crop_yield_training.ipynb
│
├── static/
│
├── templates/
│
└── screenshots/
```

---

## 📸 Screenshots

### Home Page

![Home Page](Screenshots/Home%20Page.png)

### Prediction Form

![Prediction Form](Screenshots/PredictionForm.pn)

### Results Page

![Results Page](Screenshots/ResultsPage.png)

### Insights Section

![Insights Section](Screenshots/Insights%20Section.png)

### PDF Report

![PDF Report](Screenshots/PDFReport.png)

---

---

## 🧪 Testing

The system has been tested using multiple agricultural scenarios including:

* Rice cultivation in high rainfall regions
* Wheat cultivation in moderate climatic conditions
* Maize cultivation under balanced environmental conditions
* Missing NPK value scenarios using auto-estimation
* Different soil types and weather conditions

---

## 📄 PDF Report

Users can download a detailed PDF report containing:

* Farmer input details
* Predicted crop yield
* Estimated production
* AI-generated insights
* Summary of prediction results

---

## 🚀 Future Scope

* SHAP-based Explainable AI (XAI)
* Real-time Weather API Integration
* Crop Recommendation System
* Mobile Application Development
* Cloud Deployment (Render / AWS)

---


