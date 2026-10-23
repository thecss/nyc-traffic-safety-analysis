# NYC Traffic Safety Analysis
> Analyzed NYC traffic collision data in Excel to reveal when collisions peak across months, weekdays, and hours, and which contributing factors are most common and most likely to cause injury or death.

<br>

## 💼 Business Problem

The New York City Police Department's Analytics Team has been tasked with analyzing traffic accident data from January 1st, 2021 to April 9th, 2023 as part of the city's Public Safety Initiative program. The goal is to identify patterns and trends that can help the NYPD prevent future accidents.

To support this, the analysis answers three questions:

1. **When** do collisions peak during the year? (seasonal patterns)
2. **When** during the week are collisions most concentrated? (weekday and hour hotspots)
3. **Why** do collisions happen, and which causes most often lead to injury or
   death? (contributing factors)

<br>

## 📊 Key Findings
### 1️⃣Seasonal Patterns

  
### 2️⃣Weekly Trends


### 3️⃣Contributing Causes


## 🔧Tools
Microsoft Excel (PivotTables, WEEKDAY/HOUR functions, conditional formatting, line charts) 
<br>

## 📂Dataset
NYPD motor vehicle collision data (Maven Analytics), January 1, 2021 to April 9, 2023
<br>

## ⚙️ Methodology

#### Objective 1: Seasonal Patterns
1. Counted `Collision ID` by year and month using a PivotTable
2. Excluded April 2023, since the data ends on April 9th and the month is incomplete
3. Plotted a line chart with each year as a separate line

#### Objective 2: Weekly Trends
1. Extracted weekday with `WEEKDAY` and hour with `HOUR` from the Date and Time columns
2. Counted `Collision ID` by weekday and hour
3. Built a heatmap using a white-white-red 3-color scale so the most dangerous periods stand out

#### Objective 3: Contributing Factors
1. Counted `Collision ID` by contributing factor and kept the top 10, sorted descending
2. Calculated `% of Dangerous Collisions = collisions with an injury or fatality ÷ total collisions` for that factor
3. Added data bars to the percentage column
<br>

## Future Enhancements
1. Build an interactive dashboard in Power BI or Tableau
2. Add street-level analysis to pinpoint high-risk locations, since location data is already in the dataset
<br>

## Acknowledgments
Completed as part of the Traffic Safety Analysis guided project in the Maven Analytics Excel Specialist path. Thanks to Maven Analytics for the structured guidance and dataset.
