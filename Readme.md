# Fraud Detection App

A web application that detects anomalous credit card transactions using machine learning.

---

## Features

- Analyze single transactions for anomalies.
- Batch analysis of multiple transactions via CSV upload.
- Visual summary of normal vs anomalous transactions.

---

## Technology

- Python, Flask
- scikit-learn (DBSCAN for anomaly detection)
- HTML, CSS, JavaScript, Chart.js

---
# Transaction Insights Dashboard

This repository contains the Transaction Insights Dashboard, a tool designed to analyze and detect anomalies in transactions based on time, amount, and various parameters (V1, V2, V3).

## Screenshots

### 1. Transaction Insights Dashboard - Initial View
<img width="1916" height="1136" alt="image" src="https://github.com/user-attachments/assets/cfa26ccf-aaed-4721-9c87-7668230d51aa" />

*Description*: The initial interface of the Transaction Insights Dashboard where users can input transaction details.

### 2. Transaction Insights Dashboard - Anomaly Detected
<img width="1341" height="1039" alt="image" src="https://github.com/user-attachments/assets/2a6e105a-9853-4a51-9df3-adb659d9ccae" />

*Description*: A view showing the detection of an anomaly in a transaction with a highlighted alert.

### 3. Transaction Insights Dashboard - Normal Transaction
<img width="1344" height="1063" alt="image" src="https://github.com/user-attachments/assets/e490295a-32d8-4753-86d6-0ed8cda36eed" />

*Description*: A view indicating a normal transaction with no anomalies detected.

### 4. Transaction Insights Dashboard - CSV Upload and Anomaly Summary
<img width="1351" height="1067" alt="image" src="https://github.com/user-attachments/assets/02e114ce-6ac9-495e-9428-0640f75fdcc1" />
<img width="1340" height="1067" alt="image" src="https://github.com/user-attachments/assets/5bb6b560-3623-462c-ab1d-77181d3e6f23" />

*Description*: The CSV upload feature and a summary of analyzed transactions, including normal and anomalous counts.

---

## Notes

- The app uses a clustering model (DBSCAN) to detect anomalies.
- Large datasets and trained models are not included in the repository.

