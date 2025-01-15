# 🌦️ 30 Days DevOps Challenge - Weather Dashboard 🚀  
**Day 1: Building a Weather Data Collection System with AWS S3 & OpenWeather API**

## 🌍 Weather Data Collection System - DevOps Day 1 Challenge

### Project Overview
This project is a **Weather Data Collection System** designed for Day 1 of the **DevOps 30-Day Challenge**. It integrates:

- 🌦️ **OpenWeather API** for fetching live weather data
- ☁️ **AWS S3** for cloud storage
- 🛠️ **Infrastructure as Code** using Python
- 📁 **Version Control** with Git
- 🐍 **Python Development**
- ⚠️ **Error Handling**
- 🌱 **Environment Management**

---

## 🛠️ Key Features

- 🌡️ **Fetches real-time weather data** for multiple cities
- 💧 **Tracks temperature (°F)**, **humidity**, and **weather conditions**
- ☁️ **Automatically stores weather data** in an **AWS S3** bucket
- 🌆 **Supports multiple cities tracking**
- ⏰ **Timestamps all data** for future reference and historical tracking

---

## 🖥️ Technical Architecture

- **Programming Language**: Python 3.x 🐍
- **Cloud Provider**: AWS (using S3 for data storage) ☁️
- **External API**: OpenWeather API 🌦️

### 📦 Key Dependencies

- **boto3**: AWS SDK for Python 🛠️
- **python-dotenv**: Manage environment variables 🌱
- **requests**: Simplified API calls to OpenWeather 🌐

---

## 🗂️ Project Structure

```bash
weather-dashboard/
  ├── src/
  │   ├── __init__.py
  │   ├── weather_dashboard.py
  ├── tests/
  ├── data/
  ├── .env
  ├── .gitignore
  ├── requirements.txt

