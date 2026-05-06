# NBA Shot Quality & Optimization (SqO)

**Shot Quality & Optimization (SqO)** is a spatial analytics framework designed to model personalized shooting efficiency for individual NBA players. While traditional metrics rely on league-wide averages, SqO builds a continuous **Gaussian Kernel Density Estimation (KDE)** surface using real-time data from the NBA Stats API.

## 🏀 Key Features
* **Continuous PPS Surfaces:** Generates Points Per Shot (PPS) heatmaps that reveal efficiency gradients within traditional shot zones.
* **Bayesian Smoothing:** Uses a Bayesian prior to prevent overfitting in sparse court zones (e.g., corners for non-shooters).
* **Strategic Audit:** Quantifies Expected Value (EV) across four strategic zones: Rim, Midrange, Corner 3, and Above-Break 3.
* **Defensive Scouting:** Automates the generation of scouting reports based on a player's unique "shooting signature."

## 📊 Sample Findings (2023-24 Season)
The framework identifies high-value anomalies that traditional scouting might overlook:
* **Stephen Curry:** Corner 3 efficiency is **41% above league average** (1.571 PPS).
* **Giannis Antetokounmpo:** Corner 3 efficiency was **0.00 PPS**, suggesting a "hard-shade" defensive strategy.
* **DeMar DeRozan:** Midrange efficiency (0.916 PPS) is **17% above baseline**, defying the "inefficient midrange" narrative.

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/atsi2004/nba-sqo-analytics.git](https://github.com/atsi2004/nba-sqo-analytics.git)
