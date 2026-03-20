<a name="readme-top"></a>

<div align="center">
  <img src="DEVTrails-ProjectLogo.png" alt="GigGuard Logo" width="400">

  <h1>🛡️ GigGuard — Parametric Wage Protection</h1>
  <h3><em>"Securing the Gig Economy, One Shift at a Time"</em></h3>

  <p>
    <img src="https://img.shields.io/badge/DEVTrails_2026-Guidewire-blueviolet?style=for-the-badge" alt="DEVTrails 2026"/>
    <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"/>
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
    <img src="https://img.shields.io/badge/XGBoost-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="ML"/>
  </p>

  <p>
    <strong>AI-enabled parametric insurance for India's Quick-Commerce heroes.</strong><br/>
    No claim forms. No manual reviews. Automatic payouts for lost hours in < 180 seconds.
    <br/><br/>
    <a href="INSERT_YOUR_VIDEO_LINK_HERE">View Strategy Video</a>
    ·
    <a href="https://github.com/YOUR_USERNAME/GigGuard/issues">Report Bug</a>
  </p>
</div>

---

## 🚩 The Problem: The "Invisible" Wage Gap

GigGuard addresses the systemic financial vulnerability of India's 12 million delivery partners who are currently trapped in a "No-Work, No-Pay" cycle.

* **The "Safety-First" Penalty:** When extreme weather hits, a rider’s uptime drops to zero. Choosing safety over riding results in a **30% "Safety Penalty"** on monthly take-home pay, causing immediate distress for rent and EMI payments.
* **The "Friction Tax":** Traditional insurance is incompatible with gig work. The time required to file a manual claim for a ₹500 loss is often worth more than the claim itself, making recovery economically irrational for the worker.
* **The "Impact" Blindspot:** Existing insurance is **Reactive** (Accidents only). GigGuard covers the **Proactive** reality: riders aren't injured, but the *market* is inaccessible due to AQI 400+ pollution, heatwaves, or curfews.
* **The Sachet-Economy Mismatch:** Gig workers operate on **weekly payouts**, yet insurance demands monthly/annual premiums. There is a lack of "Sachet Insurance" that matches their real-world cash flow.

---

## 👤 Targeted Persona: The Q-Comm Rider
**Primary Target:** Delivery partners for Grocery/Quick-Commerce (e.g., Zepto, Blinkit).
* **The Scenario:** A rider in a flood-prone urban zone loses a 4-hour peak dinner shift due to heavy rainfall.
* **GigGuard Impact:** Instead of losing critical earnings, parametric triggers detect the rainfall via Weather APIs and initiate a wage recovery payout automatically—no paperwork needed.

---

## 🧠 The "Guardian" AI Engine
GigGuard is an intelligent risk engine designed to protect livelihoods through two core AI pillars:

### 1. Dynamic Pricing Model (XGBoost)
* **Zone-Specific Risk:** Adjusts weekly premiums based on hyper-local data (e.g., flood-prone vs. safe zones).
* **Predictive Modeling:** Dynamic coverage adjustments based on 7-day predictive weather forecasting.

### 2. Intelligent Fraud Defense
* **Anti-Spoofing:** Machine learning to identify GPS spoofing or fabricated weather claims.
* **Activity Validation:** Cross-referencing location and platform activity to prevent duplicate or false claims.

---

## 🛠 Tech Stack
* **Frontend:** React Native (Mobile-first for real-time rider validation).
* **Backend:** Python (FastAPI) for high-performance ML serving.
* **Database:** PostgreSQL (Supabase) for real-time policy and claim tracking.
* **Oracles:** Weather APIs (OpenWeather) for parametric triggers.
* **Payments:** Mock payment gateways (Razorpay test mode) for instant payout simulation.

---

## 🗺️ Development Roadmap

### 📍 Phase 1: Ideation & Foundation (Weeks 1-2)
**Current Status: COMPLETE (Deadline: March 20)**
* **Persona Identification**: Selected **Quick-Commerce** partners as the primary sub-category.
* **Core Strategy**: Defined strict **Loss of Income Only** scope and **Weekly Pricing** model.
* **Foundation**: Repository initialized and 2-minute strategy video recorded.

### 🛠️ Phase 2: Automation & Protection (Weeks 3-4)
**Timeline: March 21 – April 4**
* **Parametric Trigger Engine**: Build 3–5 automated triggers using Weather or Social disruption APIs.
* **Zero-Touch Logic**: Design a claim process where triggers automatically initiate payouts without user intervention.
* **AI Integration**: Develop the initial ML model for dynamic weekly premium adjustments.

### 🚀 Phase 3: Scale & Optimize (Weeks 5-6)
**Timeline: April 5 – April 17**
* **Advanced Fraud Detection**: Deploy models to identify GPS spoofing and validate rider activity during disruptions.
* **Instant Payout System**: Integrate mock payment gateways to demonstrate real-time wage recovery.
* **Final Delivery**: Consolidate code, record 5-minute walkthrough, and finalize the Pitch Deck.

---
**Team GigGuard — Guidewire DEVTrails 2026**
*Every second on the road counts. We protect the seconds you lose.*
## 🔄 Project Workflow: The "Zero-Touch" Cycle
```
GigGuard operates on a fully automated loop, moving from risk assessment to instant recovery in four distinct stages.



### Stage 1: Intelligent Onboarding & Dynamic Pricing
* **Rider Registration:** The delivery partner (Persona: Q-Comm Rider) connects their platform ID (e.g., Zepto/Blinkit) via the mobile app.
* **Kavach AI Risk Scoring:** Our **XGBoost model** analyzes the rider’s primary delivery hub.
* **Weekly Sachet Premium:** Instead of a flat fee, the AI generates a customized weekly premium (e.g., ₹42/week) based on hyper-local weather forecasts and historical disruption data for that specific pincode.

### Stage 2: Real-Time Parametric Monitoring
* **Data Oracles:** The backend continuously polls **OpenWeather** and **IMD APIs** for environmental triggers (Rainfall > 50mm, Temp > 45°C, or AQI > 400).
* **Threshold Detection:** The system monitors for "Market Blockers"—events that physically prevent a rider from safely completing shifts.
* **Platform Heartbeat:** The system checks for sudden spikes in "App Outages" reported via social/API signals.

### Stage 3: AI-Driven Fraud & Activity Validation
* **The "Guardian" Check:** Before a claim is initiated, the AI performs a three-way validation:
    1. **Location Check:** Did the disruption happen in the rider's active work zone?
    2. **Activity Pulse:** Was the rider logged in or scheduled to work during the disruption?
    3. **Anti-Spoofing:** Machine Learning algorithms detect anomalies like GPS spoofing or fabricated weather reports to ensure system integrity.

### Stage 4: Automated Claim & Instant Payout
* **Zero-Touch Initiation:** Once the parametric threshold is hit and AI validates the activity, a claim is **automatically created**—the rider never has to "file" anything.
* **Instant Wage Recovery:** Using a simulated **UPI/Razorpay Gateway**, the lost income is pushed directly to the worker’s wallet.
* **Transparency:** The rider receives a push notification: *"Heavy rain detected in your zone. ₹500 Wage Recovery has been credited to your wallet."*

---
### Technical Sequence Diagram
1. **Trigger:** Weather API → Returns Rainfall > Threshold.
2. **Validate:** Backend → Checks Active Weekly Policies for that Pincode.
3. **Verify:** AI Layer → Confirms Rider Activity & Fraud Check.
4. **Execute:** Payout Service → Disburses funds via Mock API.
5. **Notify:** FCM/Push Notification → Confirms credit to Rider.
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>
