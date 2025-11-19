# ⚡ EV Smart Charging Optimization System

A Python-based system designed to optimize electric vehicle (EV) charging using machine learning, routing algorithms, and SQLite databases. The project predicts charging demand, recommends optimal charging stations, and generates efficient travel routes using real-world datasets. It includes automated data pipelines, backend APIs, and a lightweight frontend for real-time visualization.

## 🚀 Features

- Machine learning models for EV charging demand prediction  
- Automated data pipelines for cleaning, transforming, and preparing datasets  
- Routing engine that identifies the most efficient charging paths using geographic data  
- SQLite-backed database system for storing charging stations and model outputs  
- Modular backend providing APIs for predictions, routing, and station details  
- Simple Python-based frontend for viewing predictions and optimized routes  
- Scalable architecture suitable for EV data analysis and energy planning  

## 🛠️ Tech Stack

- **Python**  
- **Machine Learning (scikit-learn, pandas, numpy)**  
- **SQLite**  
- **REST API (custom backend)**  
- **Geographic routing algorithms**  

## 📁 Project Structure

```
ev-smart-charging/
│── app_backend.py          # Backend API handling system requests
│── app_frontend.py         # Lightweight frontend visualizing outputs
│── data_pipeline.py        # Data cleaning and preprocessing workflow
│── train_models.py         # Machine learning model training script
│── routing_provider.py     # Routing and path optimization engine
│── database.py             # Database schema & connectivity logic
│── ev_charging.db          # Main SQLite database
│── data/                   # Raw datasets
│── exported_data/          # Processed datasets
│── ml_models/              # Stored ML models
│── requirements.txt        # Project dependencies
│── How to run.txt          # Instructions for running the app
```

## ▶️ How to Run

1. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```

2. Run the backend server:  
   ```
   python app_backend.py
   ```

3. Start the frontend interface:  
   ```
   python app_frontend.py
   ```

4. (Optional) Retrain machine learning models:  
   ```
   python train_models.py
   ```

## 📄 License

This project is licensed under the **MIT License**.


Developed By; Tarun Attri, Harshit Pathak, Saiyam Jain, Rajdeep Chaudhary
