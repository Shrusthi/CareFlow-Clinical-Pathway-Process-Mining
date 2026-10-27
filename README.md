# CareFlow – Clinical Pathway Process Mining

## Project Overview
CareFlow is a healthcare process mining project that analyzes hospital event logs to understand patient journeys, activity patterns, and waiting-time gaps. The project uses data analysis and visualization to help identify potential bottlenecks in the clinical pathway.

## Objectives
- Analyze patient journeys using hospital event logs.
- Understand the sequence and frequency of hospital activities.
- Calculate time gaps between consecutive recorded events.
- Explore patient pathways and potential process bottlenecks.
- Present key findings through a Power BI dashboard.

## Tools and Technologies
- **Python** – Data analysis and preprocessing
- **Jupyter Notebook** – Analysis and experimentation
- **Pandas** – Data manipulation and cleaning
- **PM4Py** – Process mining analysis
- **Microsoft Power BI** – Interactive dashboard and visualization
- **GitHub** – Project version control and documentation

## Project Files
 File
 | Description 

 `Careflow_Analysis.ipynb` -Notebook for data analysis, patient pathways, and process mining 
 
 `hospital_event_logs.csv` - Original hospital event log dataset 
 
 `cleaned_hospital_event_logs.csv`  -Cleaned dataset used for analysis and visualization 
 
`CareFlow_Clinical_Pathway_Dashboard.pbix` - Power BI dashboard file 

 `README.md` - Project documentation 

## Dataset Description
The event log dataset contains records of hospital activities. The analysis uses fields such as:

- `Case_ID` – Identifier for a patient journey in the dataset
- `Activity_Name` – Recorded hospital activity
- `Timestamp` – Date and time of the recorded event

The cleaned dataset is used for the dashboard and relevant analysis.

## Key Performance Indicators (KPIs)
The Power BI dashboard includes:

- **Total Patients:** 200
- **Total Events:** 959
- **Unique Activities:** 5
- **Average Time Between Events:** 12.76 minutes
- **Longest Time Between Events:** 30 minutes
- **Average Patient Journey Duration:** 48.44 minutes

## Dashboard Visualizations
The dashboard presents:
- Hospital activity frequency
- Patient activity distribution
- Unique patients by activity
- Activity transition analysis
- KPI cards summarizing the event log and patient journey times

## How to Use
1. Clone or download this repository.
2. Open `Careflow_Analysis.ipynb` in Jupyter Notebook to explore the analysis.
3. Install the required Python libraries before running notebook cells.
4. Open `CareFlow_Clinical_Pathway_Dashboard.pbix` using Microsoft Power BI Desktop.
5. Use the dashboard filters to explore activities and individual patient journeys.

## Expected Outcome
The project demonstrates how process mining and data visualization can be used to explore clinical pathways, understand recorded activity patterns, and identify potential waiting-time bottlenecks.

## Project Status
The project includes data analysis, a cleaned dataset, and a Power BI dashboard. Further validation and analysis can improve the interpretation of clinical pathway patterns.

