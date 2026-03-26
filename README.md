# Real-Time Login Monitoring & Alert System (ML + Rule-Based)

## Overview
This project simulates a real-time cybersecurity monitoring system for healthcare environments. It combines machine learning with rule-based logic to detect suspicious login activity.

## Motivation
Healthcare systems are highly sensitive and require strong protection against unauthorized access. Traditional systems rely either on rules or machine learning. This project demonstrates a hybrid approach for better detection.

## Features
- Real-time login simulation
- Machine learning-based prediction
- Rule-based risk scoring system
- Alert generation for suspicious activity
- Visualization of login patterns

## System Workflow
1. User login attempt is recorded  
2. Features such as login time, device, download size, and location are analyzed  
3. Machine learning model predicts behavior  
4. Risk score is calculated  
5. Alerts are triggered for suspicious activity  

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

## Example Output
Login: [2, 2, 250, 1]  
ML Prediction: Suspicious  
Risk Score: 80  
ALERT: Suspicious Activity Detected  

## Future Improvements
- Integration with real-time streaming data  
- Deployment as a web-based dashboard  
- Advanced anomaly detection models  
