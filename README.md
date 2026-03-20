Guide Wire readme doc



🚀 Project Title: RakshakPay

AI-Powered Parametric Insurance for Gig Workers

📌 Problem Statement

India’s gig workers (delivery partners) face income loss due to external disruptions like weather, pollution, or curfews. Currently, there is no system to protect their daily earnings.
This project builds an AI-powered parametric insurance platform that provides automatic income protection based on real-world triggers.

📄 Based on problem statement:

🎯 Objective

To design a system that:

Calculates weekly insurance premium using AI
Detects external disruptions automatically
Triggers instant claim payouts
Prevents fraud using intelligent validation

👤 Target Persona

Food Delivery Partner (Swiggy/Zomato)
Scenario:
Works 8–10 hours/day
Income depends on daily deliveries
Heavy rain → cannot work → income loss

⚙️ System Workflow
User Registration →  
Risk Profiling (AI) →  
Weekly Premium Calculation →  
Policy Activation →  
Real-Time Monitoring (Weather/API) →  
Disruption Detected →  
Auto Claim Triggered →  
Instant Payout
💰 Weekly Premium Model

Premium is dynamically calculated based on:

Factor	Impact
Location Risk	High flood zone → ↑ premium
Weather Forecast	Rainy week → ↑ premium
Work Hours	More hours → ↑ coverage
Historical Safety	Safe user → ↓ premium
Example:
Base Premium = ₹50
+ Rain Risk = ₹20
- Safe Zone Discount = ₹10

Final Premium = ₹60/week
🌦️ Parametric Triggers
Event	Condition
Heavy Rain	Rainfall > 50mm
Heatwave	Temp > 40°C
Pollution	AQI > 300
Curfew	Govt / Mock API

👉 If triggered → automatic payout (₹300–₹800)

🤖 AI/ML Integration
1. Risk Prediction Model
Predicts probability of disruption
Used for premium calculation

2. Fraud Detection Model
Detects:
GPS spoofing
Fake claims
Duplicate claims

🔐 Fraud Detection Logic
Compare user GPS vs API location
Detect repeated claims
Validate activity logs

🏗️ Tech Stack
Layer	Technology
Frontend	React.js
Backend		Node.js / Flask
ML Model	Python (scikit-learn)
Database	MongoDB
APIs		Weather API (OpenWeather)
Payments	Razorpay (test mode)
📊 Dashboard
👤 Worker Dashboard:

Weekly coverage
Earnings protected
Claim history

🛠️ Admin Dashboard:
Risk zones
Fraud alerts
Claim analytics

🔥 Unique Features
Zero-touch claim system
Hyperlocal AI pricing
Real-time disruption detection
Instant payout simulation

🧪 MVP Features

User registration
Premium calculator
Weather trigger simulation
Auto payout system
Basic dashboard

📅 Development Plan
Phase 1:
Idea + README + basic UI

Phase 2:
Backend + APIs + ML integration

Phase 3:
Fraud detection + dashboard + scaling

🎥 Demo Plan
User logs in
Simulate heavy rain
System detects disruption
Claim triggered automatically
₹ credited instantly
