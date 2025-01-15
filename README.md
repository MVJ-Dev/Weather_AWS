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
## ⚙️ Setup Instructions

1. **Clone the repository**:  
To get started, clone the repository to your local machine by running the following command:
--Bash
git clone https://github.com/MVJ-Dev/weather_aws_repo.git

2. Install dependencies:
pip install -r requirements.txt

3. Configure environment variables (.env):
In order to interact with the OpenWeather API and AWS, create a .env file in the root directory and add the following lines:
OPENWEATHER_API_KEY=your_openweather_api_key
AWS_BUCKET_NAME=your_aws_bucket_name
- Replace your_openweather_api_key with your actual OpenWeather API key.
- Replace your_aws_bucket_name with your S3 bucket name.

4. Configure AWS credentials:
To allow the application to access your AWS S3 bucket, run the following command to configure your AWS credentials:
aws configure
- Enter your AWS Access Key ID and AWS Secret Access Key when prompted.
- For Default region name, enter us-east-1 (or another region of your choice).
- Set Default output format to json.

5. Run the application:
Finally, run the weather dashboard with this command:
python src/weather_dashboard.py




