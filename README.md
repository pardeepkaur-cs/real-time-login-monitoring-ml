# Simulated Real-Time Login Monitoring & Alert System

## Overview

This project is a simulated login monitoring system for a healthcare security environment.

It combines a machine learning prediction with simple rule-based risk scoring to identify login activity that may need further review.

The project uses simulated data and does not use real patient or hospital information.

## How It Works

The project follows a simple process:

1. A login event is recorded.
2. Login information is examined.
3. A machine learning model makes a prediction.
4. Rule-based checks calculate a risk score.
5. The system displays an alert when the activity appears suspicious.

## Features

- Login activity monitoring
- Machine learning prediction
- Rule-based risk scoring
- Example security alerts
- Simulated healthcare environment

## Technologies

- Python
- Pandas
- Scikit-learn
- Google Colab

## Example Scenarios

The project includes example login situations to show how the monitoring and alert process works.

These examples demonstrate the workflow and are not a statistical measurement of real-world detection performance.

## Limitations

This is a simulated proof-of-concept project and is not a production healthcare monitoring system.

The dataset is small, so the examples should not be interpreted as evidence of real-world detection accuracy.

A larger dataset and a proper comparison of rule-based, machine learning, and combined approaches would be useful for future research.

## Future Work

Possible future improvements could include:

- Larger datasets
- More user behaviour information
- Streaming login events
- Comparison of different detection methods
- A monitoring dashboard
- More realistic security scenarios
