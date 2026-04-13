# 📊 Visualising Sample Data Distributions

## 👨‍🎓 Project Details
- **Name:** Shreyansh Tiwari  
- **Roll No:** 25SCS1003001300  
- **Course:** B.Tech CSE (AI/ML Project)  
- **University:** IILM University  

---

## 📌 Project Overview
This project focuses on **data visualization and machine learning** using a student dataset.  
It transforms raw data into meaningful insights through various visualization techniques and predictive models.

The project also includes a **Flask-based web application** that displays student data and generated plots interactively.

---

## 🎯 Objectives
- Analyze student dataset using visualization techniques  
- Identify patterns, trends, and outliers  
- Build machine learning models for prediction  
- Create an interactive dashboard using Flask  


## ⚙️ Technologies Used
- Python 🐍  
- Pandas & NumPy  
- Matplotlib  
- Scikit-learn  
- Flask  

---

## 📊 Features

### 🔹 Data Visualization
The project generates multiple visualizations:
- Bar Chart (Grade Distribution)  
- Histogram (IQ Distribution)  
- Scatter Plot (CGPA vs IQ)  
- Attendance Analysis  
- Skills Frequency Chart  
- Correlation Heatmap  

👉 These help in identifying patterns, relationships, and outliers in data :contentReference[oaicite:0]{index=0}  

---

### 🤖 Machine Learning Models
- CGPA Prediction (Regression)  
- Pass/Fail Classification  
- Defaulter Prediction  
- Student Clustering (K-Means)  

👉 Models are trained and saved using `.pkl` files for reuse :contentReference[oaicite:1]{index=1}  

---

### 🌐 Web Application
- Built using Flask  
- Displays:
  - Top 10 students  
  - All generated plots  
- Runs on: `http://localhost:5000`  

---

## 📁 Dataset Description
- Total Records: **100 Students**  
- Features: **13 attributes**  

Some important columns:
- Age, Gender, Grade  
- IQ, CGPA, Attendance  
- Fees (paid & outstanding)  
- Skills  

👉 Dataset is clean and well-structured with no missing values :contentReference[oaicite:2]{index=2}  

run plots & modela
python generate_plots_and_models.py

Run Flask App
python app.py

Open in Browser
http://127.0.0.1:5000/

