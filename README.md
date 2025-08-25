# Win Rate Differentials

This project is based on an Open Dataset from Kaggle and fully prepared using **Power BI Desktop**.<br/>
Objective: Report for **Exploratory Data Analysis** for the evaluation of team-level performance across home and away venues.

We have a raw extract from **Transfermarkt** covering the **2022/23 season** of England's top-tier football league, the **Premier League**.

Phase-wise explanation:
## 1. Preparation
  - Data Profiling, cleaning, and transformation done using the Power Query tool.
  - .CSV files with team and player metrics cleaned for modelling.
## 2. Modelling
  - A Star Schema was created with game results as the fact table.
  - Dimensions include clubs, player appearances, competitions, date, results, and goals record.
  - Calculated tables created using DAX - Date, Results, Goals Record.
## 3. Visualize 
   #### Page 1
  - Table Grid visual for consolidated team data.
  - Bookmark and action buttons to configure the display state for viewing Home and Away tables separately.
   #### Page 2
  - Line Charts to evaluate team performance with goal splits across home and away vs total goals over the season.
  - Average constant line and slicer to view selective club data for comparison.
## 4. Analyze
  - Page 1: Used for descriptive analysis based on team results and how they differed with the venue change.<br/>
    E.g., Nottingham Forest have a stark contrast in home and away results, with most of their wins coming at their home ground.<br/>
    This follows the general trend across the league.
  - Page 2: Used for diagnostic analysis based on Goals scored and conceded by the team, and their split across home and away stadiums.<br/>
    E.g.. Leicester City has scored an above-average number of goals at home, but it did not translate into wins as they conceded around the same amount. This saw them finish in the bottom 3, resulting in relegation.
   
