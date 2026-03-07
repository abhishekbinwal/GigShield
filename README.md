# GigShield

AI-powered parametric insurance platform that protects delivery partners from **income loss caused by external disruptions** such as heavy rain, extreme heat, pollution spikes, curfews, or platform outages.

---

## 🚀 Project Overview

Gig workers like **Zomato, Swiggy, Blinkit, Amazon and Flipkart delivery partners** rely on daily earnings. When unexpected disruptions occur (weather events, app crashes, or city restrictions), their work stops and their income drops to zero.

**GigShield** provides a safety net by offering a **weekly micro‑insurance model** that automatically compensates workers when predefined disruption triggers occur.

Instead of traditional insurance claims, GigShield uses **parametric triggers and real‑time data** to initiate automatic payouts.

---

## 🎯 Problem Statement

Delivery partners face frequent income interruptions due to:

- Heavy rain and flooding
- Heatwaves and extreme temperatures
- Severe air pollution
- Curfews or mobility restrictions
- Platform outages or system failures

Currently, there are **very limited financial safety nets** for these workers.

GigShield aims to solve this by providing **fast, transparent and automated income protection**.

---

## 💡 Solution

GigShield uses **AI + parametric insurance** to automatically detect disruption events and trigger payouts.

### Key Idea

If a disruption crosses a predefined threshold:

Example

Rainfall > 80mm
OR
AQI > 400
OR
Platform outage > 30 minutes

➡ Automatic payout is triggered for affected delivery partners.

No manual claims required.

---

## ⚙️ Core Features

### 1️⃣ AI Powered Risk Assessment

- Dynamic weekly premium calculation
- Risk prediction based on location
- Weather and disruption history analysis

### 2️⃣ Intelligent Fraud Detection

- GPS based location validation
- Worker activity verification
- Anomaly detection in claims
- Duplicate claim prevention

### 3️⃣ Parametric Automation

- Real‑time disruption monitoring
- Automatic claim initiation
- Instant payout processing

### 4️⃣ Weekly Micro‑Insurance Model

Gig workers operate on a weekly earning cycle.

Example Plans

| Plan | Weekly Premium | Max Weekly Payout |
|-----|-----|-----|
| Basic | ₹30 | ₹500 |
| Standard | ₹60 | ₹1200 |
| Premium | ₹100 | ₹2500 |

---

## 📡 Data Sources & Integrations

GigShield relies on multiple external data feeds.

- Weather APIs (rainfall, temperature)
- Air quality APIs (AQI data)
- Traffic & road condition APIs
- Simulated delivery platform activity
- Payment gateway sandbox for payouts

---

## 🤖 AI / ML Components

GigShield uses AI for:

- Risk modeling for premium calculation
- Predicting disruption probability
- Fraud detection using anomaly detection
- Validating worker activity patterns

---

## 🏗️ Proposed Architecture

```
Delivery Partner App
        │
        ▼
Backend API Server
        │
 ┌───────────────┬───────────────┐
 │               │               │
 ▼               ▼               ▼
Risk Engine   Fraud Detection   Trigger Engine
 │               │               │
 ▼               ▼               ▼
Weather API   Location Data   Platform Status
        │
        ▼
 Payment Gateway
```

---

## 🛠️ Tech Stack (Planned)

Frontend

- React / React Native

Backend

- Node.js / Express

Database

- MongoDB / Firebase

AI / ML

- Python
- Scikit-learn

External APIs

- Weather API
- Traffic API
- Payment Gateway Sandbox

---

## 📅 Development Roadmap

Phase 1 – Research & Ideation

- Persona research
- Disruption analysis
- Parametric trigger design

Phase 2 – System Design

- AI risk modeling
- Fraud detection architecture

Phase 3 – Prototype Development

- API integrations
- Trigger monitoring system

Phase 4 – Testing & Demo

- Automated payout simulation
- Hackathon presentation

---

## 📌 Coverage Scope

GigShield **ONLY covers income loss due to external disruptions.**

Not Covered:

- Vehicle repairs
- Medical expenses
- Accidents
- Life insurance

---

## 👨‍💻 Authors

Built for an AI Innovation Hackathon.

Creator: Aditya

---

## ⭐ Vision

To build a **global safety net for gig workers**, ensuring that no delivery partner loses their livelihood due to uncontrollable external disruptions.
