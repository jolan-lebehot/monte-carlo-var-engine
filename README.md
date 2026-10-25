# Monte-Carlo Value-at-Risk (VaR) Engine

A quantitative finance project implementing a **Monte-Carlo Value-at-Risk engine** based on **Geometric Brownian Motion (GBM)**, developed as a 1A student personal project at **Grenoble INP - Ensimag**.

## 🚀 Overview
This project models future asset price dynamics (e.g., Apple stock) using stochastic calculus and estimates asset risk metrics (VaR at 95% and 99%) over a simulation horizon.

### Key Features
* **Return Dynamics:** Analytical comparison between simple and log-returns (highlighting time additivity and price positivity constraints).
* **Stochastic Modeling:** Derivation of Geometric Brownian Motion via **Itô's Lemma** and normal distribution scaling over time steps $\Delta t$.
* **Theoretical Rigor:** Justification of market noise using the Central Limit Theorem assuming independent and identically distributed (i.i.d.) increments.
* **Empirical Implementation:** Python integration within RStudio (`yfinance`, `NumPy`, `Matplotlib`) to project 100+ Monte-Carlo price paths.
* **Risk Engine:** Empirical P&L distribution construction and Value-at-Risk quantile evaluation.

---

## 📄 Documentation & Code
* 📖 **Full Academic Report:** [View sim_Var.pdf](./sim_Var.pdf)
* 💻 **Source Code:** [View sim_Var.Rmd](./sim_Var.Rmd)

---

## 🛠️ Requirements & Setup
The project runs inside an RStudio environment using Python.

### Python Dependencies
```bash
pip install yfinance numpy matplotlib
