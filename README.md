# Infosys_Springboard_Virtual_Internship-2026_Batch-11_Team-A
Capstone project for the Infosys Springboard Virtual Internship (2026 Batch – Team A). This project analyzes Indian election data using Power BI, featuring interactive dashboards on election overview, party performance, demographics, trend analysis, close contests, and winning factor evaluation.


## Project Title - ElectViz: Election Data Visualization for Media 

A comprehensive analytical dashboard system for understanding Indian election patterns, voter behavior, and winning factors.


## Project Overview

Indian elections involve complex dynamics such as vote share
distribution, constituency-wise competition, demographic diversity, and
candidate profiles. Raw datasets often fail to convey these complexities
clearly. 
ElectViz is a Power BI–based analytical solution designed to transform
raw election data into interactive dashboards. It provides a structured, visual, and data-driven approach to understanding electoral trends, competitiveness, and winning strategies across elections conducted
between 2009 and 2021. The project emphasizes clarity, accuracy, and insight generation through
advanced data modeling and visualization techniques.

## 📁 Project Files Structure

This repository contains the following files and folders related to the ElectViz Election Analytics Dashboard project:

- **Individual ppt's/**  
  Contains individual presentation files prepared by team members for project reviews and evaluations.

- **Team ppt**  
  Includes the consolidated team presentation showcasing the overall project, dashboard features, and insights.

- **ElectViz Project Completion Report.pdf**  
  Final project completion report describing objectives, methodology, tools used, dashboard modules, insights, and outcomes.

- **LICENSE**  
  Specifies the licensing terms under which this project is distributed.

- **README.md**  
  Provides an overview of the project, setup instructions, file structure, and usage details.

- **election_dashboard_updated.pbix**  
  Power BI dashboard file containing interactive visualizations, filters, and analytics based on Indian election data.

- **updated_election_data.csv**  
  Cleaned and preprocessed dataset used as the primary data source for the Power BI dashboard.



## Problem Understanding

Election data is inherently complex and multi-dimensional, involving numerous factors such as:
- Vote margins and turnout percentages
- Party dominance across constituencies
- Demographic representation
- Regional variations and trends

**Key Challenges Addressed:**
- Why do parties with higher vote margins sometimes win fewer seats?
- How does election competitiveness evolve over time?
- What factors contribute to consistent electoral success?

Traditional tabular analysis fails to provide clear explanations for these phenomena. This project bridges that gap by transforming raw data into **visual, insight-driven dashboards** that explain both *what happened* and *why it happened*.



## Dataset Information

### Source
The dataset is sourced from publicly available Indian election data repositories and official election records from kaggle.

### Dataset Name : Indian State Level Election Assembly Constituency Dataset

### Dataset Structure and Column Explanation

| Column Name | Description |
|-------------|-------------|
| Year | Year in which the election was conducted |
| State Name | Name of the Indian state or union territory |
| Assembly Constituency Name | Name of the electoral constituency |
| Candidate Name | Name of the contesting candidate |
| Candidate Type | Category of candidate (SC, ST, BL, General) |
| Party Name | Political party associated with the candidate |
| Gender | Gender of the candidate |
| Total Votes | Total number of votes received by the candidate |
| Total Valid Votes | Total valid votes gained in the constituency |
| Vote Share (%) | Percentage of votes received by the candidate |
| Winning Candidate | Indicator showing whether the candidate won |
| Winning Margin (%) | Percentage difference between winner and runner-up |
| Turnout (%) | Voter turnout percentage in the constituency |
| Seats Won | Number of seats won by a party or candidate |

### Data Preparation
- Cleaned and transformed using **Power Query**
- Validated for accuracy and consistency
- Structured for optimal performance in Power BI



## Tools and Technologies

| Tool                                | Purpose                                                                |
| ----------------------------------- | ---------------------------------------------------------------------- |
| **Power BI Desktop**                | Dashboard development and interactive visualization                    |
| **DAX (Data Analysis Expressions)** | Calculated measures, KPIs, and advanced analytics                      |
| **Power Query**                     | Data cleaning, transformation, and modeling                            |
| **Microsoft Excel / CSV**           | Raw data storage and preprocessing                                     |
| **GitHub**                          | Version control, code collaboration, and project repository management |
| **GitLab**                          | Source code management, CI/CD pipelines, and team collaboration        |



## Visualizations Used

The dashboards emphasize visual storytelling over raw tables, utilizing:

- **KPI Cards** — Seats Won, Vote Share, Turnout, Winning Margin
- **Bar and Column Charts** — Party performance comparisons
- **Line and Area Charts** — Trend analysis over time
- **Stacked Bar Charts** — Cumulative insights
- **Scatter and Bubble Charts** — Correlation analysis
- **Pie and Donut Charts** — Proportional representation
- **Shape Map** — Geographical analysis
- **Slicers and Buttons** — Interactive filtering and navigation



## Key Insights

### Competitiveness Trends
- Elections have become more competitive over time with an increase in close contests
- Median winning margin is a better competitiveness indicator than average margin

### Seats vs. Votes Paradox
- Higher vote margins do not always translate into more seats won
- Parties winning many close contests convert votes into seats more efficiently

### Candidate and Demographic Patterns
- Candidate consistency and repeat victories significantly impact long-term success
- Voter turnout and demographic patterns show substantial regional variation

### Vote Efficiency
- Strategic vote distribution across constituencies matters more than raw vote share
- Winning margin efficiency is a critical factor in seat conversion



## Dashboard Structure

The project comprises seven interactive dashboards, each focusing on a specific analytical dimension:

1. **Election Overview Dashboard** — High-level election metrics and KPIs
2. **Party Performance Analysis** — Comparative party analysis across elections
3. **Gender Distribution Analysis** — Gender-based representation and patterns
4. **Candidate Demographic Analysis** — Comprehensive candidate demographics
5. **Electability Analysis** — Factors influencing candidate success
6. **Trend Analysis** — Electoral trends and patterns over time
7. **Election Outcome and Winning Factor Analysis** — Determinants of electoral victory



## Learning Outcomes

This project demonstrates the following competencies and skills:

### Technical Skills Gained
- Proficiency in Power BI Desktop for dashboard development and data visualization
- Advanced DAX (Data Analysis Expressions) for creating complex calculations and KPIs
- Data modeling techniques including relationship management and schema design
- Power Query for ETL (Extract, Transform, Load) operations
- Visual analytics and interactive report design
- Statistical analysis and trend identification
- Geospatial data visualization using maps

### Soft Skills Developed
- Analytical thinking and problem-solving
- Data-driven storytelling and presentation
- Attention to detail in data cleaning and validation
- Project planning and time management
- Collaborative teamwork and communication
- Critical thinking in interpreting complex datasets
- Professional documentation and reporting



## Conclusion

This project successfully transforms complex election data into an analytical and decision-support dashboard system. By combining trend analysis, demographic insights, and outcome evaluation, the dashboards provide a deeper understanding of electoral behavior beyond surface-level statistics.

The work showcases the power of data visualization in making sense of multi-dimensional datasets and supporting evidence-based decision-making.



## Collaborators

1. **Swayam Bana**
2. **Nandhini B**
3. **Vaibhav Pawar**
4. **Diksha Palliwal**
5. **Sharmika Shri R**

## Acknowledgements

We would like to express our heartfelt gratitude to:

- **Infosys Springboard Team** – for organizing this valuable internship opportunity.
- **Our Mentor(Nityashree Ma'am)** – for her continuous support and feedback.
- **My Teammates** – for collaboration, encouragement, and insights.

This internship has been a significant step in our professional growth and technical journey.

## References

- **Election Dataset Source** – Kaggle  
  Dataset Link: [https://www.kaggle.com/datasets/awadhi123/indian-election-dataset?select=indian-state-level-election.csv]

- **Microsoft Power BI Documentation**  
  https://docs.microsoft.com/en-us/power-bi/

- **DAX Guide and Resources**  
  https://dax.guide/

- **Infosys Springboard Virtual Internship** – Course materials and resources



## License

This project is licensed under the MIT License - see the LICENSE file for details.

Copyright (c) 2026 Infosys Springboard Virtual Internship - Team A

Permission is hereby granted, free of charge, to any person obtaining a copy of this project and associated documentation files, to deal in the project without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the project, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the project.


**Note:** This project is created strictly for educational and learning purposes as part of the Infosys Springboard Virtual Internship program. The analysis and insights are based on publicly available data and should not be interpreted as political opinions or forecasts.

**Made by Team A - Infosys Springboard Virtual Internship (2026 Batch-11)**
