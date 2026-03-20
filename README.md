# gigguard
AI-Powered Parametric Insurance for Gig Workers

# 🛡️ GigGuard — AI-Powered Parametric Insurance for India's Gig Workers

> Protecting the income of India's delivery workforce against uncontrollable external disruptions — automatically, intelligently, and affordably.

---

## 📌 Problem Statement

India's gig delivery workers (Zomato, Swiggy, Zepto, Blinkit, Amazon, Flipkart, Dunzo) are the backbone of the digital economy. Yet they are completely exposed to income loss caused by events outside their control — extreme weather, severe pollution, local curfews, and strikes.

A single bad week can wipe out 20–30% of their monthly earnings. They have no safety net. No insurance. No fallback.

**GigGuard changes that.**

---

## 👤 Persona — Who We're Protecting

### Primary Persona: Rajan, 28 — Delivery Partner, Chennai

- Works across Zomato, Swiggy, and Zepto
- Earns approximately Rs 700–900/day on active days
- Works 6 days/week → Rs 4,500–5,400/week
- Has no employer, no benefits, no income protection
- Loses full daily income when disruptions prevent him from working

### Covered Platforms
- Food Delivery: Zomato, Swiggy
- Quick Commerce: Zepto, Blinkit
- E-Commerce Logistics: Amazon, Flipkart

---

## ⚡ Parametric Triggers

| Disruption | Trigger Threshold | Daily Payout |
|---|---|---|
| Heavy Rainfall | More than 15 mm/hr for 3+ hrs | Rs 400 |
| Extreme Heat | More than 43 degrees C | Rs 300 |
| Severe Pollution | AQI more than 300 | Rs 350 |
| Flood Warning | IMD Orange/Red Alert | Rs 450 |
| Local Strike / Curfew | Zone-level disruption | Rs 400 |
| Cyclone / Storm | IMD Red Alert | Rs 500 |

---

## 💰 Weekly Premium Model

| Tier | Weekly Earnings | Weekly Premium | Max Weekly Payout |
|---|---|---|---|
| Basic | Up to Rs 3,500 | Rs 49 | Rs 1,400 |
| Standard | Rs 3,500–5,500 | Rs 79 | Rs 2,100 |
| Pro | Rs 5,500–8,000 | Rs 109 | Rs 3,000 |

---

## 🔄 Application Workflow
```
1. ONBOARDING
   Worker downloads GigGuard app
   Enters name, city, delivery platforms
   Links UPI payment
   AI generates risk profile
   Selects weekly plan

2. POLICY ACTIVATION
   Policy activates Monday 00:00
   Coverage runs 7 days
   Worker dashboard shows live risk level

3. REAL-TIME MONITORING
   GigGuard monitors Weather APIs, AQI APIs, IMD alerts

4. AUTOMATIC TRIGGER
   Threshold crossed in worker zone
   System validates worker location and activity
   Fraud engine runs anomaly check

5. PAYOUT
   Claim auto-initiated
   Payout processed within 2 hours via UPI
   Worker notified via push notification
```

---

## 🤖 AI/ML Integration

- **Premium Calculation** — XGBoost model based on city, zone, season, platform count
- **Fraud Detection** — Isolation Forest model for anomaly detection
- **Risk Profiling** — Risk score 0–100 generated on onboarding
- **Predictive Alerts** — ML model predicts high risk days in advance

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| Mobile App | React Native (Expo) |
| Web Dashboard | React |
| Backend | Node.js, Express |
| AI/ML Service | Python, FastAPI |
| Database | Firebase Firestore |
| Weather API | OpenWeatherMap |
| AQI API | CPCB Open API |
| Payments | Razorpay Sandbox |

---

## 📱 App Screens

1. Onboarding — platform selection, city, UPI linking
2. Home — active policy, live risk level, weather triggers
3. My Policy — plan details, coverage list, renewal date
4. Payouts — auto-payout history with disruption details
5. Profile — plan settings, payment method, zone preferences

---

## 🚫 Out of Scope

GigGuard does NOT cover:
- Health or medical expenses
- Life insurance
- Accident coverage
- Vehicle repair or damage
- Theft

---

## 👥 Team

- Poovizhi A — Project Lead
- Poovizhi A — Frontend Web
- Aradhana B— Mobile App
- Pavithra S — Backend
- Pranav K — AI/ML
- Jaivardhini E - UI/UX 

---

## 📎 Links

- GitHub Repository: https://github.com/Poovizhi1101/gigguard
- Figma Design: https://www.figma.com/make/1Muytx6xamxK8Sdp3QkjrD/GigGuard-home-screen-design?fullscreen=1&t=q2dUszMvyRUPm2wD-1
- Demo Video: https://www.loom.com/share/866ac2f92c6b4246aa59bb8df766d740

---

*Built for the Guidewire Hackathon 2025 — AI-Powered Insurance for India's Gig Economy*
