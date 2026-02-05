# 🌱 Optimal Planting Season Prediction

## 📌 Project Title
**A Data-Driven Approach to Forecasting Crop Transplantation Periods in Bangladesh Using Machine Learning Model**

## 📖 Abstract
Agricultural production in Bangladesh is extremely sensitive to climate variability. Climate change poses one of the greatest challenges to determining optimal planting seasons in the country. With increasing climatic uncertainties, evidence-based planting decisions are essential to sustain crop yields and ensure food security. Traditional crop calendars are becoming less reliable as shifting environmental conditions alter seasonal patterns.

This study aims to predict the optimal transplanting months for **103 major crops in Bangladesh** using machine learning models and long-term historical weather data. We utilize day-to-day meteorological information—**temperature, rainfall, humidity, and sunshine**—from **35 meteorological stations** covering the period **1961–2023**, combined with crop-wise agronomic information across **nine crop groups**: cereals, pulses, oil seeds, vegetables, fiber, staples, fruits, tubers, and nicotine.

Four datasets were constructed based on different temporal windows, variable combinations, and geographic coverage. After preprocessing (categorical encoding and feature scaling), several machine learning models—**Decision Tree, K-Nearest Neighbors (KNN), and Random Forest**—were trained and evaluated using **10-fold cross-validation (10K-CV)**.

The **Random Forest** model achieved the best performance with **98.95% accuracy** using a 30-year meteorological window (1993–2023) along with crop and geographic features, while **KNN** achieved **97.68% accuracy**. The results demonstrate the effectiveness of machine learning in identifying climate-resilient and data-driven planting seasons for Bangladeshi agriculture.

---

## 🎯 Objectives
- Predict optimal transplanting months for major crops in Bangladesh  
- Analyze long-term climate variability and its impact on planting seasons  
- Compare the performance of multiple machine learning classifiers  
- Support intelligent agro-advisory and climate-resilient farming systems  

---

## 🗂️ Dataset Description
- **Meteorological Data**
  - Temperature
  - Rainfall
  - Humidity
  - Sunshine
  - Source: 35 meteorological stations (1961–2023)

- **Crop Information**
  - 103 crops
  - 9 crop groups:
    - Cereals
    - Pulses
    - Oil seeds
    - Vegetables
    - Fiber
    - Staples
    - Fruits
    - Tubers
    - Nicotine

- **Prepared Datasets**
  - Four datasets based on:
    - Temporal span
    - Feature combinations
    - Geographic coverage

---

## ⚙️ Methodology
The overall workflow of the proposed system is shown below:

![Methodology](https://github.com/user-attachments/assets/cb729128-d0d1-4973-9b02-88789229c388)

### 🔧 Preprocessing Steps
- Encoding categorical variables (crop name, crop type)
- Feature scaling for continuous variables
- Dataset partitioning using 10-fold cross-validation

### 🤖 Machine Learning Models
- Decision Tree
- K-Nearest Neighbors (KNN)
- Random Forest

---

## 📊 Exploratory Data Analysis

### Humidity Distribution
![Humidity Box Plot](https://github.com/user-attachments/assets/0e568bbc-f43f-457d-8c32-8236014e26a3)

### Temperature Distribution
![Temperature Box Plot](https://github.com/user-attachments/assets/71179bec-f44b-4508-9574-62346f9d9af4)

![Additional Plot](https://github.com/user-attachments/assets/7c5d3023-ed31-41b7-9a24-46e23a161c20)
![Additional Plot](https://github.com/user-attachments/assets/9142202e-976a-49d4-a770-63d98e94017f)

---

## 📈 Model Performance

### Confusion Matrix
![Confusion Matrix](https://github.com/user-attachments/assets/c37d33eb-86ff-481f-8bbf-c113e71cfd1f)
![Confusion Matrix](https://github.com/user-attachments/assets/cec95efd-343d-480c-8bca-55105c7eaab5)

### 🔍 Key Results
| Model | Accuracy |
|------|----------|
| Random Forest | **98.95%** |
| KNN | **97.68%** |
| Decision Tree | Competitive |

---

## 🌾 Key Findings
- Random Forest consistently outperformed other models
- Long-term meteorological data significantly improves prediction accuracy
- Crop-specific and geographic features enhance model robustness
- ML-based planting calendars outperform traditional rule-based calendars

---

## 🚀 Applications
- Intelligent agro-advisory systems
- Climate-resilient crop planning
- Policy-making for agricultural adaptation
- Farmer decision-support tools

---

## 🔮 Future Work
- Integrate crop yield prediction alongside transplanting time
- Near-real-time forecasting using early-season weather data
- Expand models for regional and district-level recommendations
- Incorporate Explainable AI (XAI) for interpretability

---

## 📚 Keywords
Machine Learning, Climate Change, Planting Season Prediction, Agriculture, Bangladesh, Agro-Advisory Systems

---

## 👤 Author
**Abu Omayed**  
Department of Statistics

---

## 📜 License
This project is for academic and research purposes. License information can be added here.
