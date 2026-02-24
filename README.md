# 📈 Investment Portfolio Risk Dashboard (Salesforce)

Built a complete Salesforce mini‑app to track equity trades, calculate risk ratings, and monitor compliance within investment portfolios. Demonstrates business analysis, data modeling, automation, and dashboarding skills.

## 🏦 Business Context

**Scenario:** Portfolio manager needs visibility into trade risk and automatic flagging of compliance issues across their equity holdings.

**Problem:** Manual tracking of trade risk ratings and compliance checks is time‑consuming and error‑prone.

**Goal:** Centralized data model + automation to surface high‑risk trades in a single dashboard.

## 🛠️ Tech Stack

- **Platform:** Salesforce Lightning Experience  
- **Data:** Custom Objects (Portfolios, Trades, Compliance Issues)  
- **Automation:** Record‑Triggered Flow  
- **Data Loading:** Data Import Wizard (CSV)  
- **Visualization:** Reports & Dashboards  

## 📊 Solution Design


**Key Features:**
- **Risk Rating:** Auto‑calculated on Trade insert/update based on business rules (e.g., large position sizes, high volatility symbols).  
- **Compliance Issues:** Automatically created for high‑risk trades.  
- **Dashboard:** Visualizes risk distribution, symbol exposure, and open compliance items.

## 🚀 Implementation

1. **Data Model:** Created 3 custom objects with lookup relationships.  
2. **Automation:** Record‑Triggered Flow on Trades triggers on create/update, calculates Risk Rating, creates Compliance Issue if needed.  
3. **Data Import:** Loaded sample CSV trades via Data Import Wizard (handled lookup mapping challenges).  
4. **Analytics:** Built grouped reports (Trades by Risk Rating, Symbol exposure) → Dashboard with bar charts and summary metrics.

## 📈 Results

- Successfully imported 100+ sample trades across one portfolio.  
- Flow triggered compliance issues for 20% high‑risk trades.  
- Single dashboard provides portfolio‑level risk overview.

## 📸 Screenshots

| Data Model | Risk Flow | Dashboard |
|------------|-----------|-----------|
|<img width="1453" height="490" alt="image" src="https://github.com/user-attachments/assets/6e81b96a-4559-4be1-ae22-c79344d3cf94" />|<img width="633" height="666" alt="image" src="https://github.com/user-attachments/assets/971aad9d-3a99-4ab5-a524-e2a298bad453" />|<img width="1214" height="429" alt="New Trades Report Latest (1)" src="https://github.com/user-attachments/assets/11f9bfe8-140e-4c56-8e48-c5dc6d684f08" />|


## 💡 Key Learnings

- Translating business rules into declarative automation (Flows).  
- Handling data import limitations (lookup mapping).  
- Designing report types for cross‑object analysis.  


