# Trina Vertex S+ NEG18R.28 — V-I / P-V Curve Simulator

An interactive, browser-based tool to simulate **Voltage-Current (V-I)** and **Power-Voltage (P-V)** curves for the **Trina Vertex S+ NEG18R.28** series solar modules, built on the single-diode model with datasheet-accurate parameters.

🔗 **Live Tool:** [https://akhlad123.github.io/vi-curve-simulator/](https://akhlad123.github.io/vi-curve-simulator/)

---

## Features

- **Module Variant Selection** — Choose from 485W to 510W variants (TSM-NEG18R.28)
- **Real-time curve generation** — V-I and P-V curves update instantly as parameters change
- **Environmental conditions** — Adjust irradiance (G) and cell temperature (T)
- **String configuration** — Set number of modules in series and parallel
- **STC vs. adjusted specs** — Side-by-side comparison of Standard Test Condition values vs. current operating point
- **MPP marker** — Maximum Power Point highlighted on both curves
- **Voltage lookup** — Enter any voltage to instantly read out current, power, and operating point details

---

## How to Use

1. Select a **module variant** from the dropdown
2. Adjust **irradiance** (W/m²) and **cell temperature** (°C) using the sliders
3. Set the **string size** (modules in series × parallel)
4. Read off the **adjusted STC specs** and observe the curves update in real time
5. Use the **voltage lookup** to query any specific operating point

---

## Technology

- Pure **HTML / CSS / JavaScript** — no build step, no dependencies to install
- **[Chart.js](https://www.chartjs.org/)** (v4.4.7) for interactive charting
- Single-diode model physics for accurate curve simulation

---

## Running Locally

No server needed — just open `index.html` directly in any modern browser:

```bash
# Clone the repo
git clone https://github.com/Akhlad123/vi-curve-simulator.git

# Open in browser
start vi-curve-simulator/index.html   # Windows
open vi-curve-simulator/index.html    # macOS
```
