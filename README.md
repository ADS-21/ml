# 🤖 Travel Planner ML Module

This repository contains the machine learning backend for the **Travel Planner Web App**, which provides destination recommendations based on user preferences such as budget, duration, and travel type.

## 📁 Repository Contents

- `model.pkl` – Trained machine learning model used for prediction
- `encoder.pkl` – Label encoder for preprocessing user inputs
- `requirements.txt` – Python dependencies for running the Streamlit app
- `streamlit.py` – Streamlit-based web application script

## 🧠 Project Overview

This ML module predicts travel destination categories based on the user’s input:
- Budget range
- Trip duration (number of days)
- Preferred destination type (e.g., beach, hill station, adventure, etc.)

The model was trained using Scikit-learn, and the interactive web interface is built using Streamlit.

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/ADS-21/ml.git
   cd ml
