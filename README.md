# 🏁 Monaco GP SQL Analysis – Strategy for Colapinto's 2025 Debut

This project analyzes historical and recent Monaco Grand Prix data to inform Franco Colapinto’s 2025 race strategy, focusing on qualifying-to-race probabilities and Argentinian driver legacy. Using the [F1 dataset from Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020), 20 SQL queries explore race outcomes, qualifying trends, and position changes, culminating in a Canva report.

## 🎯 Project Objectives

- **Historical Context:** Analyze 70 Monaco GPs (1950–2024) and the performance of Argentinian drivers.
- **Qualifying Trends:** Focus on pole positions and points conversion from 2003–2024.
- **Recent Performance:** Examine grid position outcomes in the last 5 races (2019, 2021–2024).
- **Strategic Insights:** Highlight Q3 targets and position gain/loss for optimal race strategy.

## 🗃️ Repository Structure

```
monaco-gp-analysis/
├── queries/
│   ├── historical_analysis/      # Full-race trends (wins, DNFs, constructors)
│   ├── qualifying_insights/      # 2003–2024 analysis (poles, consistency)
│   ├── recent_performance/       # 2019, 2021–2024 (Q3 vs points, DNF risk)
│   └── argentinian_context/      # Performance of Argentine drivers
├── results/                      # CSV outputs
├── docs/                         # Final Canva report
└── README.md
```

## 🔍 Key Insights

- **Senna dominates** with 6 Monaco wins; **Fangio leads Argentina** with 2 victories.
- **Ferrari and Red Bull** share ~50% of poles from 2003–2024.
- **Pole-sitters win 80%** of the time in recent GPs.
- **Q3 qualifiers** have a **60%+ chance** of scoring points.
- **Mid-grid starters (P5–P10)** face **higher DNF risk** due to Monaco’s tight layout.

## ⚙️ Setup Instructions

```bash
git clone https://github.com/your-username/monaco-gp-analysis.git
```

1. Import the F1 dataset into SQL Server.
2. Open and run queries using SSMS (`queries/` folder).
3. Check output files in `results/`.
4. View the final PDF report inside the `docs/` folder.

## 📈 Report Overview

- Historical winners and Argentinian legacy.
- Pole position dominance and consistency.
- Position gain/loss and Q3 conversion (2019–2024).

## 🌱 Future Improvements

- Add weather data for deeper analysis.
- Expand strategy models to tyre management.

---

📬 **Contact**: [matiasrossi95@outlook.com](mailto:matiasrossi95@outlook.com)  
🌐 **Portfolio**: [Visit Portfolio Website](https://matirossi87mr.wixsite.com/matiasrossi-porfolio)  

---

_Project completed: May 24, 2025_
