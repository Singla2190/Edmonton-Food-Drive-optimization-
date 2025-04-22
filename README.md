# 🥫 Food Drive Donation Predictor

A machine learning-powered web application designed to help organizations predict food donation volumes based on historical data and location-specific factors. Built by Team 2 at NorQuest College.

![Main Image](main%20image.png)

---

## 📌 Project Overview

This project aims to optimize food drive logistics and improve donation efficiency by leveraging historical donation data and location insights. Using regression models, it predicts future food donations and presents results via an interactive web interface.

---

## 📁 Project Structure

Food_drive_project-main/ ├── app.py # Flask application for deployment ├── requirements.txt # Python dependencies ├── location.csv # Location-specific data ├── Food Drive Data Collection 2024(1-448).csv # Main dataset ├── knn_regressor_model.pkl # Trained ML model ├── *.ipynb # EDA and model development notebooks ├── *.png # Visual assets (logos, UI image) └── README.md # Project overview


---

## 🔍 Features

- Exploratory Data Analysis (EDA) on donation patterns
- Predictive modeling using K-Nearest Neighbors (KNN)
- User-friendly web interface for donation prediction
- Visual branding with local partner logos

---

## 🚀 How to Run

1. **Clone the repository**  
   git clone https://github.com/your-username/Food_drive_project.git
   cd Food_drive_project-main

2. **Install dependencies**
Make sure you have Python 3.7+ and run:

pip install -r requirements.txt

3. **Run the application**
python app.py

4. **Open your browser and go to:**
http://127.0.0.1:5000

## 🧠 Model Details

- Model Used: K-Nearest Neighbors Regressor
- Inputs: Location, event details, historical donation data
- Output: Estimated donation volume

## 📊 Notebooks Included
- Team_2_food_drive_eda.ipynb: Exploratory data analysis
- Modelling_Brand_NEW_final.ipynb: Model training and evaluation

## 🖼️ Visuals and Branding
Includes official logos and branding for:
- NorQuest College
- Edmonton Food Bank
- JustServe

## 👥 Team
Team 2 – NorQuest College
Contributors: - Rahul Singla
              - Deeksha
              - Jasnoor Kaur Khangura
              - Ravneet Singh plaha
  
## 📃 License
This project is for educational purposes under NorQuest College. For external use or collaboration, please contact the project supervisor.

## 📬 Contact
For questions or contributions, please open an issue or contact us via GitHub.
