# Cyclistic Divvy-Lyft Trips 2019
#### *Coursera-Google Capstone Case Study*. Cyclistic (Divvy-Lyft) bike-share analysis of member and casual user behavior, how they use Cyclistic bikes differently.


### Introduction

This document provides an overview of the Cyclistic (Divvy-Lyft) Bike-Share Analysis Case Study, detailing the business task, data sources used, data preparation, data processing, and key deliverables for the project.

### Business Task:

The primary business task for this case study is to analyze Cyclistic's historical trip data to understand how annual members and casual riders use Cyclistic bikes differently. This analysis aims to provide insights into the behavior of these two customer segments and inform the development of a marketing strategy to convert casual riders into annual members.

#### Data Sources Used:

The data for this analysis is sourced from [Cyclistic's historical Trip Data](https://divvybikes.com/system-data). It contains information about bike trips, including details about customers, trip duration, station details, and more. The data is publicly available and has been provided by Motivate International Inc. under an appropriate [license agreement](https://divvybikes.com/data-license-agreement). Due to privacy constraints, personally identifiable information has been excluded from the dataset.

#### Data Preparation:

The Cyclistic trip data has been downloaded unzipped and stored appropriately as separate .csv files to upload for analysis. The data is organized into various columns, including customer information, trip details, and timestamps and has been sorted and filtered as needed for the analysis. The credibility of the data has been assessed to ensure it is suitable for analysis and is assumed credible as it was compiled and published by the organization, these datasets ROCCC. Anomalies in the data were identified and documented (highlighted in [R Markdown Report](https://github.com/seanmattison/divvy_trips_2019/blob/main/Cyclistic_Divvy_Report.pdf).

#### Data Processing:

The data has been checked for errors, and necessary cleaning steps have been performed to handle missing or inconsistent data. Appropriate tools, such as:

  * Spreadsheets - for initial inspection and to become familiar with the structure of the data sets, along with checking accuracy and reliability.
  * R - for data cleaning and manipulation, and to analyze the data in order to create compelling visuals.

The data has been transformed to facilitate effective analysis, including creating relevant variables and aggregating data when necessary. Data was regularized to ensure consistency and ease of analysis, uncertain or anomalous data points were marked for exclusion from the final dataset. The cleaning and manipulation process have been documented here: [R Markdown Report](https://github.com/seanmattison/divvy_trips_2019/blob/main/Cyclistic_Divvy_Report.pdf).

#### Analyze Phase:

In this phase, [R Script](https://github.com/seanmattison/divvy_trips_2019/blob/main/Cyclistic_Divvy_Report.Rmd) was created to analyze the data and uncover trends that were highlighted in the data visualizations.

#### Share Phase:

The Tableau visualizations were published and can be accessed [here](https://public.tableau.com/app/profile/sean.mattison/viz/Cyclistic_2019_Case_Study/Daily_comparisons). Visualizations were also included in the PowerPoint presentation. 

#### Act Phase:
A [PowerPoint](https://github.com/seanmattison/Cyclistic_Bike-Share_Case_Study/blob/main/Divvy_Trips_2019_PowerPoint.pdf) presentation was compiled to summarize key findings and insights from the analysis. The presentation serves as a basis for data-driven recommendations for marketing strategies to convert casual riders into annual members. The R version of this project was used to effectively analyze the Cyclistic bike data and generate insights to support data-driven decision-making.
