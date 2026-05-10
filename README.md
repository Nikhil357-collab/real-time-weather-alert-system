# real-time-weather-alert-system
Built a Weather Forecast &amp; Air Quality Monitoring Application using Python, FastAPI, Streamlit, and OpenWeather APIs. Implemented real-time weather tracking, AQI monitoring, automated risk alerts, forecast analytics, CSV reporting, and interactive dashboard visualization for environmental and climate monitoring.
# 🌦️ Weather Forecast & AQI Alert Dashboard

A real-time Weather Forecast & Air Quality Monitoring Application built using Python, FastAPI, Streamlit, and OpenWeather APIs.

The application fetches live weather and AQI data, analyzes environmental risks, generates automated alerts, and visualizes forecasts through an interactive dashboard.

---

# 🚀 Project Overview

This project provides:

- Real-time weather monitoring
- AQI (Air Quality Index) tracking
- Weather risk alerts
- Forecast analysis
- Interactive charts
- CSV report generation
- FastAPI backend services
- Streamlit dashboard interface

---

# ❗ Problem Statement

People and businesses often struggle to monitor rapidly changing weather conditions and pollution levels.

This system helps users by:

- Monitoring environmental conditions
- Predicting weather risks
- Alerting users about dangerous situations
- Providing easy-to-read dashboards

---

# 🌍 Industry Relevance

Useful for:

- Travelers
- Farmers
- Event planners
- Logistics companies
- Smart city monitoring
- Environmental analytics
- Climate awareness systems

---

# ✨ Features

## Weather Features

- Current weather data
- Temperature monitoring
- Humidity tracking
- Wind speed analysis
- Forecast extraction

## AQI Features

- AQI monitoring
- PM2.5 analysis
- PM10 analysis
- Pollution alerts

## Alert System

- Heat alerts
- Rain alerts
- Humidity alerts
- Wind alerts
- AQI alerts

## Dashboard Features

- Streamlit dashboard
- Forecast charts
- Alert notifications
- Interactive data tables

## Reporting

- CSV weather reports
- Historical log generation

---

# 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| Python | Core programming |
| FastAPI | Backend API |
| Streamlit | Dashboard |
| OpenWeather API | Weather data |
| Pandas | Data processing |
| Matplotlib | Visualization |
| Requests | API calls |
| JSON | Data handling |

---

# 📂 Folder Structure

```bash
weather-aqi-alert-dashboard/
│
├── backend/
│   ├── app.py
│   ├── weather_service.py
│   ├── alert_engine.py
│   ├── report_generator.py
│   └── config.py
│
├── dashboard/
│   └── streamlit_app.py
│
├── reports/
├── screenshots/
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

---

# 🔑 API Setup Instructions

## Step 1: Create OpenWeather Account

Visit:

https://openweathermap.org/api

---

## Step 2: Generate API Key

Copy your generated API key.

---

## Step 3: Create .env File

```env
API_KEY=your_api_key_here
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/weather-aqi-alert-dashboard.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run FastAPI Backend

```bash
cd backend
uvicorn app:app --reload
```

Backend runs at:

```bash
http://127.0.0.1:8000
```

---

# ▶️ Run Streamlit Dashboard

Open second terminal:

```bash
cd dashboard
streamlit run streamlit_app.py
```

Dashboard runs at:

```bash
http://localhost:8501
```

---

# 📊 Sample Output

```text
City: Pune

Temperature: 40°C
Humidity: 88%
Condition: Rain

Alerts:
🔥 High Temperature Alert
🌧️ Rain Alert
💧 High Humidity Alert
🔴 AQI Unhealthy
```

---

# 📸 Screenshots

## Dashboard

Add screenshot here:

```bash
screenshots/dashboard.png
```

## AQI Monitoring

```bash
screenshots/aqi.png
```

## Alerts

```bash
screenshots/alerts.png
```

## FastAPI Swagger Docs

```bash
screenshots/swagger.png
```

---

# 🔒 Security Notes

- Never upload `.env`
- Never expose API keys
- Use `.env.example`
- Use `.gitignore`

---

# 🚀 Future Enhancements

- Email notifications
- SMS alerts
- WhatsApp integration
- AI weather prediction
- Docker deployment
- PostgreSQL database
- Next.js frontend
- Weather maps

---

# 👨‍💻 Author

Nikhil Bhoyar

---

# 📜 License

MIT License
