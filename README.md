# IPL Playoff Qualification Analysis

## Project Overview
This project analyzes IPL 2024 playoff qualification trends using descriptive analytics and ranking-based prediction models.

The objective was to understand how batting aggression, bowling performance, and match outcomes influenced playoff qualification.

The project was built using:
- Microsoft Excel (preprocessing and metric engineering)
- Power BI (dashboard visualization)

---

## Data Source
The original dataset primarily contained batting statistics and match-level information.

Additional bowling metrics such as:
- average wickets taken per match

were manually aggregated and engineered during the preprocessing stage to support combined batting-bowling analysis.

---

## Objectives
- Analyze relationships between batting and bowling metrics
- Study whether aggressive batting metrics increase playoff qualification probability
- Build a ranking-based qualification model using multiple performance indicators
- Compare actual rankings with predicted rankings

---

## Metrics Used
- Average Strike Rate
- Boundary Percentage
- Average Wickets Taken Per Match
- Net Run Rate (NRR)
- Number of Victories

---

## Methodology

### 1. Boundary Percentage Analysis
Teams with higher boundary percentages were analyzed to study whether aggressive batting styles improved playoff qualification chances.

### 2. Combined Batting + Bowling Ranking Model
A weighted ranking model was created using:
- Average Batting Strike Rate
- Average Wickets Taken

The model generated normalized score rankings for all teams.

### 3. Rank Comparison
Predicted rankings were compared against actual IPL standings to evaluate model performance.

---

## Key Findings
- Teams with higher batting strike rates generally showed stronger overall performance
- Boundary-heavy teams demonstrated a higher likelihood of playoff qualification
- Combined batting and bowling metrics successfully identified most playoff contenders

### Model Performance
- 80% prediction accuracy
- Maximum ranking deviation of only 1 position
- 100% Top-5 contender identification accuracy

---

## Dashboard Features
The Power BI dashboard includes:
- KPI Cards
- Scatter Plot Analysis
- Boundary Percentage Comparison
- Team Ranking Visualizations
- Key Findings Summary

---

## Tools Used
- Microsoft Excel
- Power BI

---

## Future Improvements
- Extend analysis to IPL 2025 and IPL 2026
- Include bowling economy and batting consistency metrics
- Explore machine learning-based qualification prediction models
