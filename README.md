🍽️ AI-Powered Smart Diet & Nutrition Planner

## 📌 Problem Statement

An AI-powered app that suggests personalized diet plans based on health conditions, fitness goals, and dietary preferences. It helps users track calories, plan meals, detect health issues, and integrate with fitness apps for a healthier lifestyle.

## 📖 Description

The AI-Powered Smart Diet & Nutrition Planner is designed to provide personalized meal recommendations that align with dietary needs and budget constraints. This tool integrates Machine Learning, AI, and an interactive Streamlit-based UI to offer optimized meal choices.

By leveraging Random Forest Regressor, Gemini AI, and a Health Issue Detection Model, the system ensures balanced nutrition while helping users maintain a healthy lifestyle within their budget.

This project is ideal for students, professionals, dieticians, and individuals looking for AI-assisted meal planning solutions.

---

## 🚀 Solution Overview

This project leverages Machine Learning and AI models to provide optimized meal plans. The core components include:

- **📊 Data Collection & Preprocessing**
- **🤖 Machine Learning Module**
- **🌐 Streamlit Web App**
- **🧠 Gemini AI Integration**
- **⚕️ Health Issue Detection Model**
- **📲 AR-based QR Scanning for Nutrition Info**
- **🚨 SOS Emergency Alert System**



---

## 📂 1️⃣ Data Collection & Preprocessing

### Steps Followed:

- Collected a dataset containing food items, calories, protein, carbs, fat, cost, and health benefits.
- Cleaned missing data and converted categorical features.
- Standardized numeric features using StandardScaler.
- Saved the preprocessed dataset for model training.

---

## 🤖 2️⃣ Machine Learning Module

### Models Used:

- **Random Forest Regressor** for high-accuracy nutritional value predictions.
- **Health Issue Detection Model** for identifying potential health risks.

### Process:

- Splitting dataset into train & test sets.
- Training the models and saving them as `.pkl` files.
- Models predict optimal meal plans and detect health issues based on user input.
- Reports generated to evaluate model accuracy.

---

## 🌐 3️⃣ Streamlit Web Application

The interactive Streamlit-based UI allows users to:

- Select dietary preferences, health conditions & budget.
- View AI-suggested meal plans.
- Get detailed nutrition analysis.
- Scan QR codes for real-time nutrition details.
- Access emergency SOS features.

### To run the Streamlit app:

```bash
streamlit run app.py
```

---

## 🧠 4️⃣ Gemini AI for Enhanced Recommendations

- Used Gemini AI to improve food recommendations.
- AI refines the meal plan based on health goals & constraints.
- Provides real-time feedback on meal choices.

---

## ⚕️ 5️⃣ Health Issue Detection Model

- Uses Machine Learning to analyze user health conditions.
- Suggests personalized diet plans based on health risks.
- Integrated with real-time monitoring for proactive alerts.

---

## 📜 Results & Reports

- **Model Accuracy Metrics**: Displayed in the Streamlit app.
- **ML Model Performance Reports**: Stored in `/reports/`.
- **AI Meal Plan Recommendations**: Based on user inputs.
- **Health Issue Detection Reports**: Available in the dashboard.

---

## 📌 Future Scope

- Expand dataset & add more AI-driven insights!
- Implement voice-based meal suggestions.
- Enhance integration with wearable fitness devices.
- AI-powered meal preparation assistance.

---

## 🔗 Contributors

[TEAM STACKERS] 🚀

