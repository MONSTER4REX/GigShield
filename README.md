# 🚀 GigShield – AI-Powered Parametric Insurance for Gig Workers

## 📌 Overview

GigShield is an **AI-powered parametric insurance platform** designed to protect gig delivery workers from **income loss caused by external disruptions** such as heavy rain, pollution, floods, and curfews.

Delivery workers are the backbone of India’s digital economy, yet they lose **20–30% of their income** due to uncontrollable environmental and social disruptions. GigShield provides a **zero-touch insurance system** that automatically compensates them when such disruptions occur.

---

## 🎯 Problem Statement

Gig delivery workers (Zomato, Swiggy, Amazon, Zepto, etc.) face:

* 🌧️ Heavy rain → deliveries halted
* 🌫️ Pollution → unsafe working conditions
* 🌊 Floods → blocked roads
* 🚫 Curfews → restricted movement

Currently, there is **no income protection system** for these scenarios.

---

## 💡 Solution

GigShield introduces **parametric insurance**, where payouts are automatically triggered based on real-world data instead of manual claims.

### Key Features:

* ✅ AI-based **risk assessment**
* ✅ **Dynamic weekly premium calculation**
* ✅ **Automatic claim triggering**
* ✅ **Instant payout simulation**
* ✅ **Fraud detection system**

---

## 👤 Target Persona (Example)

### Ravi – Food Delivery Partner

* Age: 27
* Platform: Zomato / Swiggy
* Location: Delhi
* Earnings: ₹500–₹800/day

### Pain Points:

* Income loss during rain & pollution
* No financial safety net
* Weekly unstable earnings

---

## 🔄 Application Workflow

1. **User Registration**
   * Worker enters details (location, earnings, platform)

2. **AI Risk Profiling**
   * System analyzes environmental risk factors

3. **Weekly Premium Calculation**
   * Premium dynamically generated

4. **Policy Activation**
   * Worker activates coverage

5. **Real-Time Monitoring**
   * APIs track weather, AQI, traffic

6. **Trigger Detection**
   * Disruption detected automatically

7. **Claim Generation**
   * No manual claim needed

8. **Fraud Check**
   * AI validates claim authenticity

9. **Instant Payout**
   * Compensation credited to worker

---

## 💰 Weekly Premium Model

### Formula:
Weekly Premium = Base Price + Risk Adjustment

### Example:
* Base Premium: ₹25
* Risk Adjustment: ₹10–₹20
* Final Premium: ₹35–₹45/week

### Coverage:
* Weekly Coverage: ₹2000
* Payout per disruption: ₹200–₹400

---

## ⚡ Parametric Triggers

| Trigger    | Condition             |
| ---------- | --------------------- |
| Heavy Rain | Rainfall > 50mm       |
| Pollution  | AQI > 340             |
| Heatwave   | Temperature > 45°C    |
| Flood      | Waterlogging detected |
| Curfew     | Govt restriction      |

---

## 🧠 AI/ML Integration

### 1. Risk Prediction Model
* Predicts environmental risk score
* Used for dynamic premium calculation
* Model: Random Forest / XGBoost

### 2. Fraud Detection Model
* Detects anomalies in claims
* Prevents:
  * GPS spoofing
  * Duplicate claims
* Model: Isolation Forest

---

## 🏗️ System Architecture

```
User App (Mobile/Web)
        ↓
   API Gateway
        ↓
 ----------------------------
| Risk Engine (AI Model)   |
| Fraud Detection          |
| Trigger Engine           |
| NestJS Business Logic    |
 ----------------------------
        ↓
 External APIs (Weather, AQI, Traffic)
        ↓
   Payment System (Razorpay)
        ↓
       Database (PostgreSQL/Redis)
```

---

## 📱 Platform Choice

### Mobile-First App (Flutter)

**Why?**
* Native performance on low-end devices
* Most delivery workers use smartphones
* Cross-platform (Android/iOS)
* Offline capabilities and background triggers

---

## 🛠️ Tech Stack

### Frontend (Mobile App)
* **Flutter**
* **Riverpod** (State Management)
* **Dio** (Networking)
* **Lottie** (Animations)

### Backend (API Service)
* **NestJS** (TypeScript)
* **Prisma ORM**
* **BullMQ** (Task Queues)
* **Passport/JWT** (Authentication)

### AI Engine (Intelligence Layer)
* **Python** (FastAPI)
* **Scikit-learn / XGBoost**
* **Pandas / NumPy**

### Infrastructure
* **PostgreSQL** 15
* **Redis** 7 (Caching & Queues)
* **Docker** & **Docker Compose**
* **Razorpay** (Payments)

---

## 🧪 Development Plan

### Phase 1: Foundation
* Persona research & System design
* Monorepo scaffolding
* Database schema implementation

### Phase 2: Core Features
* Policy management & Workflow logic
* AI premium calculation integration
* Weather/AQI trigger automation

### Phase 3: Polish & Trust
* Fraud detection system
* Instant payout simulations
* Real-time disruptor dashboard

---

## 🏁 Conclusion

GigShield transforms insurance from a **manual, reactive process** into an **automated, AI-driven safety net** for gig workers.

> “From claims-based insurance to real-time income protection.”