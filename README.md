# Introduction to Aviation_data_ANALYSIS Project.
 Analysis of aircraft accidents to understand trends and recommend low-risk aircraft.

## Overview
This project aims to help my company, expanding into the aviation industry, assess the risks of different aircraft models by analyzing historical aviation accident data. The company needs insights to determine which aircraft are of least risk for commercial and private enterprises.

## Data
The dataset contains information on various aircraft accidents, including the type of accident, the model of the aircraft, and severity. The data is stored in the `data/` folder.We are also provided with US_State codes for reference that are also found within the 'data/' folder.

## Jupyter Notebooks
The data analysis and data exploration is done in the Jupyter Notebook(ipynb file) found in the `Aviation_data_ANALYSIS/` folder,Which is the main/root folder.

## Presentation
The final presentation slides can be found in the `Presentations/` folder.

## Interactive Dashboard
Here is a link to view the interactive dashboad that displays some visualizations for you,viewers, to explore my analysis.Here https://public.tableau.com/views/AVIATION_ACCIDENTS_ANALYSIS_DASHBOARD/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Requirements
The project requires the following libraries:
- pandas
- matplotlib
- seaborn
Which are already installed in the developmental environment used for the project.

# Aircraft Risk Analysis Project

## Overview
This project aims to analyze aviation accident data to find low-risk aircraft models to use in commercial and private company endavours. Comparing aircraft manufacturers, models, accident patterns, and safety-influencing factors based on past accident data, we recommend stakeholders on the safest aircraft to purchase.

---
## Business Understanding
### Stakeholders:
- **Executives of Companies:** Would prefer selecting low-risk aircraft for commercial flights.
- **Safety and Operations Teams:** Would prefer objective facts to inform fleet purchasing decisions.
- **Finance Team:** Would prefer low cost and low risk.

### Key Business Questions:
1. Which airplane manufacturers and models pose the highest and lowest accident risk?
2. What are accident trends over time?
3. What are the variables (e.g., number of engines) that the accident rate is correlated with?
4. Based on data,what are the  models of aircraft that would be low-risk for the company to purchase ?

## Data Understanding and Analysis
### Source of Data:
Data given to this project is from the National Transport Safety Board(NTSB) on aviation accidents over 1962 and 2023.

### Data Description:
- **Make** Plane manufacturer.
- **Model:** Plane model.
- **Injury.Severity:** Injuries from the accidents (e.g., Fatal, Minor, None).
- **Aircraft.Category:** Type of aircraft(airplane,helicopter,glider e.t.c)
- **Engine.Count:** Number of engines on an aircraft.
- **Event.Date** The date accideent occurred.

### Three Useful Visualizations:
1. **Accident Frequency by Make and Model**
- Accident frequency by different models and makes of aircraft.
- High-risk and low-risk aircraft are determined.

2. **Accident Trends Over Time**
- Examines how often the accidents occur each year to determine whether or not there are trends and patterns over the years.

3. **Number of Engines vs. Number of Accidents**
- Studies whether or not there is any correlation between the number of engines and the number of accidents.

---
## Conclusion
### Summary of Findings:
1. **High-Risk vs. Low-Risk Aircraft:**
- The data shows that certain manufacturers, i.e., **Cessna and Piper**, are prone to more accidents.
- Certain types of airplanes have fewer accidents compared to others, thus are low-risk if used in the business sector.

2. **Trend Analysis:**
- Trend accidents vary on an annual basis, and the safest years offer probable industry determinants of safety.

3. **Aircraft Design Considerations:**
- Single-engine and multi-engine aircraft have various rates of accidents,but it is clearly visible that multi-engine aircrafts are more safer that single-engine aircraft.
Based on our analysis, the company should consider aircraft models with **low accident rates** within budget and operation constraints. The safest among those in the dataset would then be filtered on this criterion based on external factors like **maintenance records, pilot training, and compliance** before actual selection is done.

--- 

The report above is evidence-based advice for selecting **the safest aircraft** for business operations with least operational risk.

