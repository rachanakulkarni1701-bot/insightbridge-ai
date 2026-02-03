# InsightBridge

**InsightBridge** is an AI-powered root-cause investigation agent designed to autonomously diagnose why key business metrics deviate from expected behavior.

---

## Overview

Business dashboards are effective at showing *what* changed, but they rarely explain *why* it changed. When metrics such as membership counts fluctuate unexpectedly, teams often rely on manual, time-intensive analysis to determine whether the change was driven by discounts, regional behavior, channel mix, or seasonality.

InsightBridge addresses this gap by automatically launching a structured investigation whenever a membership anomaly is detected. The agent evaluates multiple competing hypotheses, quantifies their contribution to the observed change, and generates a clear, executive-ready explanation grounded in data.

---

## Problem Statement

Organizations frequently observe unexpected changes in membership or retention metrics but struggle to identify the underlying causes quickly and consistently. Root-cause analysis is typically manual, inconsistent across analysts, and difficult to reproduce. InsightBridge automates this investigative process, enabling faster, more reliable diagnosis of business anomalies.

---

## Key Capabilities

- Automatic detection of membership anomalies  
  (sudden changes, seasonal deviations, or sustained trends)
- Autonomous root-cause investigation
- Hypothesis-driven analysis across:
  - Discounts and promotions
  - Regional behavior
  - Channel mix
  - New vs renewal memberships
  - Seasonality vs abnormal patterns
- Quantified contribution of each driver
- Executive-ready explanation with confidence indicators

---

## How InsightBridge Works

1. **Anomaly Detection**  
   Identifies abnormal membership behavior compared to historical and seasonal baselines.

2. **Investigation Trigger**  
   Automatically initiates an investigation when predefined anomaly conditions are met.

3. **Hypothesis Testing**  
   Evaluates multiple potential causes using deterministic analytics.

4. **Root-Cause Attribution**  
   Ranks drivers based on their contribution to the observed change.

5. **Explanation Generation**  
   Produces a concise, business-readable summary with confidence and limitations.

---


## Tech Stack

- Python
- Pandas, NumPy
- Deterministic analytical logic
- Large Language Models (LLMs) for explanation synthesis
- Streamlit (UI)
- Plotly (visualization)

---

## Motivation

This project is inspired by real-world challenges observed in enterprise environments, where teams regularly detect metric fluctuations but lack fast, reliable, and explainable tools to diagnose their causes. InsightBridge aims to encode and automate this investigative reasoning into a repeatable system.
