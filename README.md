# FIFA World Cup Analytics Dashboard (1930–2026)

#  Project Overview

The FIFA World Cup Analytics Dashboard is an interactive Power BI project that explores the history, performance, and evolution of the FIFA Men's World Cup from 1930 to 2026.

The project combines historical tournament statistics with the 2026 match schedule to examine championship records, match outcomes, goal-scoring trends, attendance, host countries, and tournament stages.

The dataset is based on publicly available football records and open-source datasets. Historical information was collated from past World Cup tournaments, while the 2026 schedule contains match dates, participating teams, venues, host countries, and tournament stages.

This analysis transforms the raw data into interactive visualizations that make historical patterns and upcoming fixtures easier to explore.



# Data Sources and Background

This project uses publicly available football data from two open-source sources:

### 1. Historical FIFA World Cup Data (1930–2022)

The historical data is referenced from the [Fjelstul World Cup Database](https://worldcups.ai/data), developed by Joshua C. Fjelstul, Ph.D. The database documents the history of the FIFA Men's and Women's World Cups, including tournament results, match statistics, goals, teams, players, stadiums, and attendance.

The dataset is available through [DataHub's FIFA World Cup collection](https://datahub.io/football/worldcup), which organizes the historical records into downloadable CSV files for analysis.

### 2. FIFA World Cup 2026 Schedule

The 2026 fixture data is referenced from [OpenFootball's World Cup repository](https://github.com/openfootball/worldcup.json), an open-source project that provides structured football match data in JSON format.

The schedule covers the expanded 48-team tournament, comprising 104 matches across the group and knockout stages.




# Project Objectives

- Examine the most successful countries in World Cup history.
- Explore changes in goals and attendance across tournaments.
- Compare host countries using average attendance.
- Analyze the distribution of the 2026 matches across stages and stadiums.
- Present historical records and the 2026 schedule in an interactive dashboard.

# Tools Used


Microsoft Excel used for Data storage, inspection, and preparation 
Power BI used for Data modeling, visualization, and dashboard development 
Power Query used for Data cleaning and transformation 
DAX used for KPI calculations and analytical measures 

# Data Preparation and Analysis Workflow

### Step 1: Data Collection
Imported the historical World Cup dataset and 2026 match schedule into Power BI from Excel.

### Step 2: Data Cleaning
Reviewed data types, column names, missing values, date and time fields, and country/team naming consistency.

### Step 3: Data Modeling
Organized the historical and schedule tables for analysis, establishing appropriate relationships and measures where required.

### Step 4: KPI Development
Created measures for total World Cup titles, historical matches, goals, average attendance, scheduled matches, and host countries.

### Step 5: Visualization
Selected charts and tables based on the analytical questions, using filters to enable interactive exploration.

### Step 6: Dashboard Design
Designed a single-page dashboard with a dark theme, football-inspired visuals, and consistent colors to improve readability and navigation.

## 6. Dashboard Components

| Visual | Analytical Purpose |
|---|---|
| KPI Cards | Summarize historical titles, matches, goals, average attendance, and 2026 schedule figures |
| Most Successful Countries | Compare countries by number of World Cup titles |
| World Cup Evolution | Track goals and average attendance across tournaments |
| Matches by Stage | Examine the distribution of scheduled 2026 matches across tournament stages |
| Historical Records Table | Display runners-up and top scorers by tournament year |
| Host Countries Map | Compare host countries using average attendance |
| 2026 Match Timeline | Explore the schedule by date and tournament stage |
| Stadium Distribution | Compare the number of scheduled matches across stadiums |
| Total Teams Chart | Show the distribution of teams across the tournament format |

## 7. Key Insights

The dashboard is designed to help users identify:

- Which countries have won the most World Cup titles.
- How goal-scoring and attendance patterns have changed over time.
- Which historical host countries recorded higher average attendance.
- How the 2026 schedule is distributed across stages and stadiums.
- How the expanded 2026 tournament differs from earlier editions.

## 8. Interactive Features

Users can explore the dashboard through filters for:

- Host country
- Match date
- Champion
- Tournament stage

These filters allow users to focus on specific tournaments, countries, or match periods.

## 9. Conclusion

This project demonstrates how historical sports data and an upcoming tournament schedule can be transformed into an interactive analytical dashboard. It combines data preparation, DAX measures, data visualization, and dashboard design to communicate football history and tournament structure in an accessible format.

The project also strengthened my practical skills in Power BI, data modeling, analytical storytelling, and presenting data-driven insights.

## 10. Disclaimer

This is an independent educational and analytical project. It is not affiliated with or endorsed by FIFA. Historical records and the 2026 schedule are based on publicly available datasets and may require verification against official sources.

