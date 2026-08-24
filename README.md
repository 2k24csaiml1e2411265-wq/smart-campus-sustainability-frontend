# 🌱 Smart Campus Sustainability Dashboard — Frontend

> **AI-powered sustainability monitoring dashboard for PSIT Kanpur**

A modern, responsive web dashboard for monitoring **Energy, Solar, Water and Sustainability metrics** across campus departments.

The frontend visualizes real-time/simulated data, AI-generated insights, anomalies, forecasts, department rankings and Green Scores through an interactive dashboard.

---
## 🚀 Live Demo

[🌱 Smart Campus Sustainability Dashboard](https://psit-dashboard-frontend.vercel.app/)

---

## 🚀 Features

* 📊 Energy, Solar & Water monitoring
* 🏫 Department-wise sustainability leaderboard
* 🤖 AI anomaly visualization
* 📈 Usage trend & forecasting charts
* 🌱 Green Score visualization
* 🚨 Recent anomaly/usage alerts
* 📱 Responsive desktop & mobile UI
* 📑 Reports and data visualization
* 🔄 API-based live data updates

---

## 🏗️ Architecture

```text
                    Smart Campus Dashboard
                              │
                              ▼
                     React Frontend
                              │
                    REST API Requests
                              │
                              ▼
                       FastAPI Backend
                              │
                              ▼
                         Supabase
                         PostgreSQL
                              │
                              ▼
                         AI / ML Layer
                ┌─────────────┼─────────────┐
                ▼             ▼             ▼
          Anomaly         Forecasting    Green Score
          Detection
```

---

## 🛠️ Tech Stack

| Technology   | Purpose                  |
| ------------ | ------------------------ |
| React        | Frontend framework       |
| Vite         | Development & build tool |
| Tailwind CSS | UI styling               |
| Recharts     | Data visualization       |
| Axios        | API communication        |
| JavaScript   | Application logic        |
| Vercel       | Frontend deployment      |

---

## 📂 Project Structure

```text
frontend/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── hooks/
│   ├── assets/
│   ├── App.jsx
│   └── main.jsx
│
├── .env.example
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <YOUR_FRONTEND_REPOSITORY_URL>
cd frontend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file:

```env
VITE_API_URL=http://localhost:8000
```

For production:

```env
VITE_API_URL=<YOUR_DEPLOYED_BACKEND_URL>
```

### 4. Start development server

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

---

## 🔌 Backend Integration

The frontend communicates with the FastAPI backend through REST APIs.

Example API flow:

```text
React UI
   ↓
Axios
   ↓
FastAPI REST API
   ↓
Supabase PostgreSQL
   ↓
AI/ML Processing
   ↓
JSON Response
   ↓
Dashboard Visualization
```

---

## 📊 Dashboard Modules

### Resource Monitoring

Displays:

* Energy consumption
* Solar generation
* Water usage

### AI Insights

Displays:

* Detected anomalies
* Forecasted resource usage
* Green Score
* Sustainability trends

### Department Leaderboard

Ranks departments based on sustainability performance.

### Alerts

Displays important events such as:

* High energy consumption
* Abnormal water usage
* Low solar generation
* Unusual usage patterns

---

## 🌍 Sustainability Goal

The dashboard is designed to support:

* **SDG 7 — Affordable & Clean Energy**
* **SDG 11 — Sustainable Cities & Communities**
* **SDG 13 — Climate Action**

---

## 🚀 Deployment

Recommended deployment:

```text
GitHub
   │
   ▼
Vercel
   │
   ▼
React Frontend
```

Configure the production backend URL through the Vercel environment variables.

---

## 🔐 Security

* API URLs stored through environment variables
* No secret keys committed to Git
* HTTPS recommended for production
* Backend responsible for authentication and data validation

---

## 🔮 Future Improvements

* 📱 Dedicated mobile application
* 🔔 Push notifications
* 🌐 Real IoT sensor integration
* 📊 Advanced analytics
* 🌱 Carbon footprint tracking
* 🏫 Campus ERP integration
* ⚡ Automated resource-control interface

---

## 👨‍💻 Project

**Smart Campus Sustainability Dashboard — PSIT Kanpur**

Built as an AI/ML-powered sustainability monitoring and analytics platform.

**Frontend:** React + Vite
**Backend:** FastAPI
**Database:** Supabase PostgreSQL
**AI/ML:** Scikit-learn + Prophet

---
