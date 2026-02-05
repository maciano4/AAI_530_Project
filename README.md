# Single Elder Home Monitoring: Gas And Position 

# AAI-530 Final Project: Data Analytics and Internet of Things

## University Of San Diego 



Group: 05

**Contributors:**
- Ahmed Eldahmy, 
- Divya Kamath,
- Christopher Akeibom Toh 

 **Instructor**: Prof. Kahila Mokhtari Jadid, PhD
 
## 📋 Table of Contents

1. [Project Overview](#project-overview)
2. [Problem Statement](#-problem-statement)
3. [Dataset](#-dataset)
4. [Project Architecture](#-project-architecture)
5. [Models Implemented](#-models-implemented)
6. [Dashboard](#-dashboard)
7. [References](#-references)

 ## 🎯Project Overview 
 An end-to-end IoT and machine learning system for monitoring air quality and indoor activity to improve safety for elderly individuals living alone.

 **Key Objectives:**
 
-Detect hazardous gas conditions (CO, CO₂, MOX) in a single elder home using continuous IoT sensor monitoring.

-Identify abnormal inactivity and behavioral patterns through indoor motion sensor data and time-series analysis.

-Enable early warnings and timely caregiver intervention via real-time alerts and predictive analytics.

-Leverage edge and cloud computing to ensure low-latency safety checks, scalability, and system reliability.

-Apply machine learning models to extract actionable insights from raw IoT sensor data.

-Visualize system status, trends, and ML insights through an intuitive Tableau Public dashboard.

## 🌍 Problem Statement

Elderly individuals living alone face increased risks from undetected gas leaks and prolonged inactivity, while traditional home monitoring systems often rely on manual intervention and generate false alarms, limiting timely and reliable safety responses.

## 📊 Dataset
This project uses the **Single Elder Home Monitoring: Gas and Position** dataset from the UCI Machine Learning Repository.

- **Source:** UCI Machine Learning Repository  
- **Dataset:** Single Elder Home Monitoring: Gas and Position  
- **Link:** https://archive.ics.uci.edu/dataset/799/single+elder+home+monitoring+gas+and+position  
- **Description:** Time-series IoT data collected from a real-world deployment in a single elderly household, including gas sensor readings (CO, CO₂, MOX, temperature, humidity) and room-level motion sensor data for indoor activity monitoring.

The dataset contains real sensor noise, missing values, and temporal dependencies, making it suitable for time-series forecasting, anomaly detection, and machine learning applications in smart home and healthcare monitoring.

## 🏗️ Project Architecture

### System Pipeline

<img width="571" height="1351" alt="Untitled Diagram drawio (1)" src="https://github.com/user-attachments/assets/b08a006f-68c1-4564-88db-5e0c2aa1a834" />

## 🧠 Models Implemented

This project implements two machine learning models to analyze IoT sensor data collected from a single elder home.

### 1. Long Short-Term Memory (LSTM) Network
A deep learning LSTM model is used to learn temporal patterns from gas sensor readings and indoor motion data. The model captures long-term dependencies in time-series data to identify abnormal environmental or behavioral patterns that may indicate safety risks.

- **Type:** Deep Learning (Recurrent Neural Network)
- **Input Data:** Gas sensor readings and motion sensor sequences
- **Purpose:** Behavioral pattern learning and anomaly detection

### 2. Time-Series Forecasting (Multiple Linear Regression)
A multiple linear regression model is used to predict future gas concentration levels (CO and CO₂) based on historical sensor data and engineered lag features. This enables early detection of rising gas levels before they reach hazardous thresholds.

- **Type:** Traditional Machine Learning
- **Input Data:** Lagged gas sensor values, rolling statistics, and environmental features
- **Purpose:** Short-term gas level prediction and proactive safety alerts

## 📈 Dashboard

A Tableau Public dashboard is used to visualize system status, historical trends, and machine learning insights, including gas concentration forecasts and activity patterns.

🔗 Tableau Public link: [add link here]

## 📚 References 

**Papers**

UCI Machine Learning Repository.  
Single Elder Home Monitoring: Gas and Position Dataset.  
https://archive.ics.uci.edu/dataset/799/single+elder+home+monitoring+gas+and+position


## 🛠️ Libraries & Frameworks

- Python
- pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
- TensorFlow / Keras
- Tableau Public


## 📄 License
This project is developed as part of AAI-530:: Data Analytics and Internet of Things course at University of San Diego.

