# Road Accident Analysis

## Table of contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview
This project aims to provide insight into road accident occurrences in both rural and urban areas between 2007 and 2010. the operations performed include data cleaning, exploration, Consolidation, data analysis using Pivot tables, filtering, sorting, and visualization. to share my findings, I built a dashboard showing the primary KPIs, Secondary KPIs, and number of casualties. I included a filter panel and established a connection between it and the KPIs for stakeholders to access specific information. By analyzing the various aspects of the road accident data, we seek to identify trends, monitor KPIs, determine the root causes of these accidents, areas, and seasons with the most casualties, and make data-driven recommendations to stakeholders.

### Data Source
Road Accident.csv

### Tools
- Excel - data cleaning, exploration, Consolidation, data analysis using Pivot tables, filtering, sorting, and visualization

### Data Cleaning
1. Loading and inspecting data
2. Handling missing and inconsistent values in the data
3. Converting the month in numbers to text
4. Converting the days in numbers to text

### Exploratory Data Analysis
EDA involves exploring the road accident data to answer key questions:
- which area has the highest casualties?
- what season has the most casualties?
- what vehicle causes the most accidents?

### Data Analysis
```SQL
SELECT * FROM table
WHERE condition = 2;
```

### Results
The analysis results are summarised as follows:
- the rural area has more casualties than urban
- cars tend to cause more accidents than
- there are more accidents in dark places than well-lit areas

### Recommendations
Based on the analysis we recommend the following actions:
- more light in dark areas
- more road network in urban

### Limitations
None

### References
None
