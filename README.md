# Energetic Corporations Facing Pandemic Effects

## Overview

This project analyzes the impact of the **COVID‑19 pandemic** on major multinational energy corporations through a **financial market perspective**. Using stock market data and time‑series analysis, the study investigates how the pandemic affected **stock prices, volatility, and returns** of large energy firms operating in different countries.

The analysis combines **economic intuition** with **data‑driven methods implemented in Python**, providing empirical evidence on how a global shock propagated through the energy sector.

---

## Motivation

Energy corporations are traditionally considered relatively stable due to their size, diversification, and strategic importance. However, the COVID‑19 pandemic represented an unprecedented shock characterized by:

* A sudden collapse in global energy and oil demand
* Supply chain disruptions
* Increased uncertainty in financial markets

The project aims to assess whether and to what extent these firms maintained financial stability during the crisis, and how quickly they recovered in the post‑pandemic period.

---

## Corporations Analyzed

The study focuses on four major energy multinationals:

* **BP** (United Kingdom)
* **Royal Dutch Shell** (Netherlands)
* **ExxonMobil** (United States)
* **Eni** (Italy)

These companies were selected to capture cross‑country differences in exposure to the pandemic and to compare firms with similar core activities but different geographic and strategic characteristics.

---

## Data

* **Source:** Yahoo Finance
* **Frequency:** Daily closing prices
* **Time span:** January 2018 – November 2023
* **Tickers:** BP, SHEL, XOM, E

The dataset allows the comparison of pre‑pandemic, pandemic, and post‑pandemic dynamics.

---

## Methodology

The analysis is implemented in **Python** using standard data science libraries:

* `pandas` for data manipulation
* `numpy` for numerical computations
* `yfinance` for data collection

The following steps are performed:

1. Download and clean historical stock price data
2. Visualize price dynamics over time
3. Compute daily returns and volatility
4. Calculate and analyze logarithmic returns

---

## Empirical Analysis

### Stock Price Dynamics

A comparison of stock price trends shows strong **comovement** among all four firms. The most severe decline occurs in **March–April 2020**, coinciding with the global lockdown phase. While recovery paths differ slightly, all companies exhibit a clear rebound starting from 2021.

### Volatility Analysis

Volatility is measured through the **standard deviation of returns**. Results show:

* Low volatility in the pre‑pandemic period
* Sharp volatility spikes during the first wave of COVID‑19
* A gradual stabilization after 2021

Despite the crisis, volatility remains relatively contained, supporting the idea that large energy firms are comparatively resilient assets.

### Log Returns

Logarithmic returns are used to properly account for compounding effects and multi‑period analysis. The results identify three main phases:

1. **2018 – early 2020:** Stable market conditions
2. **2020 – 2021:** Strong negative shocks and high uncertainty
3. **2022 – 2023:** Recovery phase, with temporary disturbances linked to the energy crisis

---

## Results

Key findings of the project include:

* A significant negative impact of COVID‑19 on energy stock prices
* Sharp but temporary increases in volatility
* Strong recovery in prices and returns from 2021 onward
* Evidence of resilience and long‑term stability of large energy corporations

---

## Skills and Competencies Acquired

* Financial time‑series analysis
* Python programming for economic data
* Volatility and return modeling
* Data visualization and interpretation
* Empirical analysis of macroeconomic shocks

---

## Conclusion

The project shows that although the COVID‑19 pandemic caused a severe short‑term disruption in the energy sector, large multinational energy corporations demonstrated **remarkable resilience**. Stock prices, volatility, and returns suggest that these firms were able to absorb the shock and progressively return to pre‑pandemic levels, confirming their role as relatively stable players in global financial markets.
