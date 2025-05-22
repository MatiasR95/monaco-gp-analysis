# 🏁 Monaco GP SQL Analysis – Strategy Insights for Franco Colapinto (2025)

Welcome to the Monaco GP analysis project — a data-driven exploration of one of Formula 1’s most iconic circuits, crafted to support **Franco Colapinto’s 2025 debut** with strategic insights grounded in history, performance trends, and qualifying probabilities.

This project blends **SQL querying, historical research, and storytelling through data**, with a final report built in Canva and over 20 structured queries into the **Ergast F1 dataset**.

---

## 🎯 Objectives

- **🏆 Historical Context**: Analyze 70 Monaco GP races (1950–2024) and highlight the legacy of Argentinian drivers like Juan Manuel Fangio.
- **🚦 Qualifying Trends**: Focus on 2003–2024 to uncover pole consistency and constructor dominance (Ferrari & Red Bull lead with ~25% each).
- **📊 Recent Insights (2019, 2021–2024)**: Analyze performance post-2022 regulation changes to reveal real-world Q3-to-points probabilities (~60%) and pole-to-win conversions (~80%).
- **🇦🇷 Argentinian Focus**: Offer a performance lens on Argentinian drivers and contextualize Colapinto’s return to F1.
- **🔧 Strategy**: Inform qualifying targets, race expectations, and risk zones — especially given Monaco’s tight layout and higher DNF rates mid-grid.

---

## 🗃️ Repository Structure

monaco-gp-analysis/
│
├── queries/
│ ├── historical_analysis/ # Insights from all Monaco races (1950–2024)
│ ├── qualifying_insights/ # Pole data, constructor trends (2003–2024)
│ ├── recent_performance/ # Focused analysis (2019, 2021–2024)
│
├── docs/
│ └── MonacoGP_Report.pdf # Final visual summary (Canva report)


---

## 🧰 Tools & Data

- **SQL Server (SSMS)** – Main analysis environment.
- **F1 Dataset** – Comprehensive open-source F1 data (races, results, drivers, constructors, qualifying). Find it here: https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020
- **Canva** – For report design and visual storytelling.

---

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/monaco-gp-analysis.git

   Set up your environment:

2.**Load the F1_Updated database into SQL Server**.

Run queries directly via SSMS, organized in the /queries/ folders.

3.**View query results:**

Navigate to /results/ for each CSV output.

4.**Read the full report:**

Open the Canva report in /docs/MonacoGP_Report.pdf

📌 Key Highlights
Senna rules Monaco with 6 victories; Fangio still the top Argentinean with 2.

80% pole-to-win conversion in recent races — reinforcing Monaco’s qualifying power.

Q3 starters (positions 1–10) have a ~60% chance of scoring points.

Drivers starting 5–10 face a higher DNF risk, due to Monaco’s narrow track and overtaking challenges.
