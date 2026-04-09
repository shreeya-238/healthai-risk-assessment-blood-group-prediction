# HealthAI: Intelligent Health Risk Assessment and Fingerprint-Based Blood Group Prediction System
## Project Description

HealthAI is an integrated intelligent healthcare system designed to provide rapid, non-invasive personal health diagnostics through the combination of deep learning-based fingerprint analysis and data-driven health risk assessment.

The system consists of two major modules: a fingerprint-based blood group prediction module and a comprehensive health risk assessment engine. The fingerprint module uses a Convolutional Neural Network (CNN) to classify blood group type from uploaded fingerprint images after preprocessing them into standardized 224×224 grayscale normalized tensors. The model predicts across eight blood group categories and provides confidence scores and probability distributions.

The health risk assessment module evaluates user health based on nine important factors: age, BMI, sleep duration, water intake, physical activity, smoking, alcohol consumption, diet quality, and stress levels. A rule-based scoring engine converts these inputs into a unified 0–100 health risk score and classifies results into Low, Moderate, or High risk categories, along with personalized health recommendations.

The system integrates a React frontend, Flask REST API backend with JWT authentication, and SQLite/MySQL database for secure data handling and persistent storage. Users can upload fingerprint images, complete health assessments, view real-time predictions, and track historical records through an interactive dashboard.

HealthAI aims to improve accessibility, affordability, and speed in health diagnostics, especially for underserved populations, by reducing costs and enabling early health awareness and preventive care.
