# EV-Smart-Charging-Optimization-System
A Python-based EV Smart Charging system that uses machine learning, routing algorithms, and SQLite databases to predict charging demand, recommend optimal stations, and generate efficient routes. Includes automated data pipelines, backend APIs, and a simple frontend for real-time insights, and supports scalable EV data analysis and energy planning.

⚡ EV Smart Charging Optimization System

An end-to-end system designed to optimize Electric Vehicle (EV) charging using machine learning, geographic data, routing algorithms, and a modular backend–frontend architecture. The project predicts charging demand, processes large datasets, recommends optimal charging stations, and provides visual outputs for users.

🚀 Features

Machine Learning Models for EV charging demand prediction

Automated Data Pipeline for data cleaning, preprocessing, and model training

Backend API System to serve predictions, station details, and optimized routes

Routing Engine that selects efficient travel paths and charging stations using geographic datasets

SQLite Database Integration for storing charging stations, routing data, and processed results

Lightweight Frontend Interface built in Python for visualizing predictions and station details

Model Training Scripts to retrain/refresh ML models as new data becomes available

🗂️ Project Structure
ev-smart-charging/
│── app_backend.py          # Backend API handling requests
│── app_frontend.py         # Simple frontend interface
│── data_pipeline.py        # Data cleaning & preprocessing pipeline
│── train_models.py         # ML model training script
│── ml_models/              # Saved trained machine learning models
│── routing_provider.py     # Routing and path optimization logic
│── database.py             # Database creation & connection methods
│── ev_charging.db          # Main SQLite database
│── data/                   # Raw datasets
│── exported_data/          # Cleaned / processed datasets
│── How to run.txt          # Running instructions
│── requirements.txt        # Dependencies

🧠 Machine Learning Components

Preprocessing and cleaning of EV charging datasets

Model training for future charging demand prediction

Time-based and location-based feature engineering

Automated pipeline for updating and saving new models

🧭 Routing & Optimization

Uses geographic datasets from California region

Computes nearest charging stations

Optimizes routes using custom algorithms

Provides recommended station + estimated travel & charging impact

🗄️ Database

Uses SQLite for fast and lightweight storage:

Charging station details

Geographic mappings

Cleaned datasets

Model outputs and logs
