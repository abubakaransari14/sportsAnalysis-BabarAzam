# Babar Azam T20 International Cricket Analysis 2016-2024

## Project Overview

This project is a **comprehensive data analysis of Babar Azam's T20 international cricket career**.  
The dataset includes **all his matches, scores, dates, grounds, opposition, and batting statistics**.  
The goal is to explore his **performance trends, strengths, and patterns** using **Python, pandas, and matplotlib**, and prepare the analysis for a **Power BI dashboard**.

--- 

## Dataset

- **Source:** https://www.kaggle.com/datasets/ahsanalirajpoot/babar-azam-t20i-stats-20162025-match-by-match
- **Columns Include:**  
  - `Runs`, `BF` (Balls Faced), `4s`, `6s`, `SR` (Strike Rate)  
  - `Pos` (Batting Position), `Dismissal`, `Inns` (Innings)  
  - `Opposition`, `Ground`, `GroundCountry`, `HomeAway`, `Date`  

- **Cleaning Steps:**  
  - Standardized opposition names (e.g., "v England" → "England")  
  - Renamed `Start Date` column to `Date`
  - Converted date column to `datetime`  
  - Added `HomeAway`, `GroundCountry` column (Home, Away) and Ground of the countries 
  - Checked for duplicates and missing values  

---

## Analysis Performed

### Career Summary
- Total Runs  
- Batting Average  
- Strike Rate  
- Highest Score  
- Centuries & Fifties  
- Total Matches / Innings  

### Year-wise Analysis
- Total runs per year  
- Batting average per year  
- Strike rate trends  

### Opposition-wise Analysis
- Runs scored vs each opposition  
- Strike rate vs opposition  
- Fours and sixes vs opposition  
- Dismissal patterns vs opposition  

### Ground / Country Analysis
- Total runs scored in each country  
- Home / Away performance  

### Batting Position Analysis
- Runs, average, and strike rate by batting position  

### Dismissal Analysis
- Overall dismissal breakdown  
- Dismissals per opposition  

### Boundary Analysis
- Total Fours and Sixes per opposition  
- Boundaries per match and position  


## Visualizations

- Bar charts, line charts, stacked/grouped bars  
- Trend lines to show performance patterns  


---

## Tools & Technologies

- **Python** (pandas, matplotlib, numpy)  
- **Jupyter Notebook** (analysis and visualizations)  

---

## Future Work

- Build **predictive models** using ML to forecast runs or classify dismissal type  
- Create **interactive dashboards in Power BI**  
- Add **more advanced visualizations** (heatmaps, shot maps, cumulative trends)  

