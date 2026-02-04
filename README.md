# Mathematical Framework for Optimizing Fan Attention
### Trosmic Sports | Statistics Intern Assessment

**Author:** Debdeep Das  
**Education:** M.Sc. Statistics, IIT Kanpur  
**Date:** February 2026

---

## 📌 Executive Summary
Fan attention is a finite resource governed by decay (forgetting) and saturation (burnout). This project proposes a **discrete time-series model** to optimize the scheduling of the **World Kabaddi Champions League (WKCL)**. 

Using Python simulations and statistical theory, I demonstrated that an **Optimized Spacing Strategy** yields significantly higher total season engagement (+1.3%) compared to traditional "Clustered" scheduling.

## 🚀 Key Features
- **Mathematical Framework:** Modeled attention ($A_t$) as a mean-reverting process with constraints.
- **Calibrated Simulation:** Validated the "Spacing Rule" ($\tau \approx \beta^{-1}$) using synthetic data in Python.
- **Strategic Implementation:** Developed algorithms for "Smart Push Notifications" and "Segmented Marketing" to prevent fan fatigue.

## 📊 Simulation Results
I simulated a 30-day season with two scheduling strategies.
- **Clustered Schedule (Traditional):** Matches grouped on Day 5, 6, 7.
- **Spaced Schedule (Optimized):** Matches spaced by 7 days.

| Metric | Clustered Strategy | Spaced Strategy | Improvement |
|:--- |:---:|:---:|:---:|
| **Total Engagement** | 11,373,214 | 11,527,295 | **+1.35%** |
| **Saturation Events** | High | Low | **Optimal** |

> **Conclusion:** By waiting for the "Regeneration Term" $\delta(A_{max} - A_t)$ to recover, we maximize the marginal utility of every match event.

## 🛠️ How to Run the Code
This repository contains implementations in both **Python** (for production logic) and **R** (for statistical validation).

### Prerequisites
```bash
pip install numpy pandas
