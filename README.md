# Aviation Risk Analysis Project

## Overview
This project analyzes historical aviation accident data to identify patterns in accidents, fatalities, aircraft categories, engine types, and flight purposes. The goal is to provide actionable insights for stakeholders in aviation to make safer and more informed investment decisions.

## Business Understanding
- Aviation safety is critical for airlines, regulators, and aircraft operators.
- Stakeholders need insights on factors most associated with aviation accidents.
- The analysis focuses on:
  - Aircraft category
  - Engine type
  - Purpose of flight
  - Accident severity (damage and fatalities)
- Insights aim to support data-driven safety and investment decisions.

## Data Understanding
- Dataset contains records of aviation accidents from 1962 to 2023.
- Key columns:
  - Event_Date
  - Aircraft_Category
  - Engine_Type
  - Purpose_Of_Flight
  - Aircraft_Damage
  - Total_Fatal_Injuries
- Some columns contain missing values, especially Purpose_Of_Flight.

## Data Preparation
- Cleaned and standardized column names.
- Selected relevant columns for analysis.
- Converted dates to datetime format.
- Handled missing values in key columns.
- Created derived features such as Event_Year.

## Data Analysis & Visualizations
- Explored accident trends over time.
- Compared accidents by aircraft category and engine type.
- Analyzed accident severity (aircraft damage and fatalities).
- Visualizations include bar charts, pie charts, and trend lines.

## Key Findings
- Airplanes account for the majority of accidents.
- Single-engine aircraft have higher accident rates than multi-engine.
- Personal and training flights are riskier than commercial operations.
- Most accidents result in substantial aircraft damage.
- Accident occurrences have declined in recent years.

## Recommendations
- Prioritize multi-engine aircraft for investment.
- Focus on commercial and business flights; avoid high-risk personal/training flights.
- Select aircraft with minimal historical damage records.

## Next Steps
- Develop an interactive dashboard to explore accidents dynamically.
- Expand dataset coverage for recent and international accidents.
- Perform predictive risk modeling to anticipate high-risk aircraft.
- Regularly update insights to maintain data-driven safety decisions.

## Project Files
- `student.ipynb` – Jupyter Notebook with full analysis
- `presentation.pdf` – Non-technical presentation slides
- `data/` – Folder containing dataset(s)
- `README.md` – Project overview and documentation

## Contact
- **ANTONY SILA**
- LinkedIn: [linkedin.com/in/ANTONY-SILA](https://www.linkedin.com/in/antony-sila-4a40a52a7)
- Interactive dashboard:https://public.tableau.com/views/Analysisforflightexpansion/aviationanalysis?
- 
