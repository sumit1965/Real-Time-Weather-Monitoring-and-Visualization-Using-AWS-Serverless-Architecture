
# 🌦️ Real-Time Weather Monitoring and Visualization Using AWS Serverless Architecture

## 📌 Project Overview

This project is a cloud-native weather monitoring system designed to collect, process, store, and visualize real-time weather data using AWS Serverless Services.

The system fetches weather information from the Open-Meteo API, processes it through AWS Lambda, stores the records in DynamoDB, and displays them through a responsive web dashboard hosted on GitHub Pages.

The project demonstrates practical implementation of modern serverless architecture while operating entirely within AWS Free Tier limits.

---

## 🚀 Key Features

- Real-time weather monitoring
- Serverless cloud architecture
- REST API integration
- Automated data processing
- DynamoDB data storage
- Interactive web dashboard
- AWS Free Tier deployment
- API fallback mechanism for reliability
- Secure IAM-based access control
- Cross-platform web access

---

## 🏗️ System Architecture

```text
Open-Meteo API
       │
       ▼
AWS Lambda
       │
       ▼
API Gateway
       │
       ▼
DynamoDB
       │
       ▼
GitHub Pages Dashboard
       │
       ▼
End User


