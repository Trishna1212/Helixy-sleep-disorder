# Helixy - AI-Powered Sleep Disorder Prediction

This project predicts sleep disorders using machine learning. It analyzes sleep patterns, stress levels, physical activity, and other key factors to detect conditions like insomnia, sleep apnea, and other sleep-related issues.

---

## Project Overview
Helixy is designed to predict sleep disorders based on multiple biological and lifestyle factors. The goal is to provide personalized sleep insights and help users take preventive measures for better health.

### Why This Project?
- Research shows that 25% of adults suffer from sleep disorders (CDC Report).  
- Early detection can reduce health risks such as heart disease and diabetes.  
- Sleep issues impact work productivity and mental well-being.  
- AI-powered predictions can assist with self-diagnosis and lifestyle adjustments.  

---

## Key Features
- Predicts insomnia, sleep apnea, and other sleep disorders.  
- Uses a Decision Tree Classifier for high accuracy.  
- Trained on real-world health datasets.  
- Analyzes sleep duration, physical activity, stress level, heart rate, and other factors.  
- Potential future integration with wearable devices such as Apple Watch and Fitbit.  

---

## Dataset Used
- **Dataset Name:** Sleep Health Data  
- **Source:** Public health records / Kaggle dataset  
- **Number of Records:** 374+ sleep health records  
- **Features Used for Predictions:**  
  - Age (years)  
  - Sleep duration (hours per night)  
  - Quality of sleep (rating from 1-10)  
  - Physical activity level (minutes/day)  
  - Stress level (scale of 1-10)  
  - Heart rate (BPM)  
  - Daily steps (steps per day)  
  - BMI and blood pressure 

---

## Machine Learning Model
- **Model Type:** Decision Tree Classifier  
- **Algorithm Used:** Scikit-Learn  
- **Performance Metrics:**
  (Prediciting if the person has disorder)
  - Accuracy: 96%  
  - Precision: 97%  
  - Recall: 94%  
  - F1-Score: 95%  

---

## Technologies Used
- Python  
- Scikit-Learn for machine learning  
- Pandas and NumPy for data processing  
- Joblib for model saving and loading  
- Git and GitHub for version control  

---

## How to Use the Model
### Clone the Repository
