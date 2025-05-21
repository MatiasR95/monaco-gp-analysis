Monaco GP Analysis for Franco Colapinto’s 2025 Strategy
Overview
This project analyzes 70 Monaco Grand Prix races (1950–2024) to inform Franco Colapinto’s 2025 debut strategy, focusing on qualifying-to-race probabilities and Argentinian legacy. Using the Ergast F1 dataset, 20 SQL queries explore historical wins, pole consistency, and recent points probabilities, visualized in an 8-page Canva report.
Objectives

Historical Context: Highlight 70 races and Argentinian driver performance (1950–2024).
Qualifying Trends: Assess pole consistency and points from 2003–2024 (~20 races).
Recent Insights: Analyze points probabilities and qualifying trends for the last 5 races (2019, 2021–2024, no 2020 GP due to COVID).
Strategy: Guide Colapinto’s qualifying target (Q3 for high points probability).

Data Source

Ergast F1 Database: Includes races, results, qualifying, drivers, constructors tables.
Scope: 70 Monaco races (circuitId = 6), qualifying data from 2003–2024.

Repository Structure

queries/:
historical_analysis/: All races (e.g., win rankings, DNF rates).
qualifying_insights/: Last 20 races (e.g., pole consistency).
recent_performance/: Last 5 races (e.g., points probability).


results/: CSV outputs for each query.
docs/: Canva report PDF (Monaco_Report.pdf).

Key Findings

Historical: 70 races; Ayrton Senna leads with 6 wins; Juan Fangio won twice for Argentina (1950–2024).
Qualifying: Mercedes (35.71% pole frequency), Red Bull (26.32%), Ferrari (23.81%) dominate poles (2003–2024).
Recent: Grids 2–8 have 80–100% points probability, guiding Colapinto’s Q3 target (2019, 2021–2024).
DNF Risk: Mid-grid (grids 5–12) has ~15–23% DNF rates, pole only 1.43% (1950–2024).

Setup

Clone the repository:git clone https://github.com/[YourUsername]/monaco-gp-analysis.git


Import F1_Updated database into SQL Server.
Run queries in SSMS from queries/ subfolders.
View results in results/ CSVs.

Report
The 8-page Canva report (in docs/) visualizes:

Historical wins and Argentinian performance (1950–2024).
Pole consistency and points leaders (2003–2024).
Points probabilities (2019, 2021–2024).
Scorecard: 70 Monaco races.

Future Improvements

Add weather data for race strategy.
Expand to other circuits for broader F1 analysis.

Contact

LinkedIn: [Your LinkedIn URL]
Email: [Your Email]

Project completed: May 24, 2025
