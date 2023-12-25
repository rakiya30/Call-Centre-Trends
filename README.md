### Phone Now Call-Centre-Trends
## An Overview of Long-term Trends in Customer and Agent Behaviour

### Project Overview

This data analysis project aims to provide inghts and recommendation on long- term trends in customer and agent  behaviour that reflects all the relevant Key Performance Indicators(KPIs) and metrics in the dataset. 

### Problem Statement

I received an email from Claire, the call centre manager, asking me to create a visually engaging dashboard that provides transparent insights into the call centre trends for the first quarter of the year 2021. This dashboard will be used as a basis of discussion with management.

### Data Source

The dataset used for this analysis was provided by PhoneNow, it consists of 10 columns and 5000 rows

### Tools

- Powerbi (Data Cleaning, Data Modeling, Data Analysis and Visualisation)

  ### Data Cleaning and Preparation

In the initil preparation phase, we performed the folloing tasks:
1. Data Loading and inspection.
2. promoted headers.
3. handling missing values.
4. Replacing Null values with 0.
5. Checked for blank cells and missing values using the column quality check.
6. Changed data type for Date and Time columns.
7. Replaced values Y/N with Yes/No.
8. Removed Duplicates.
9. Removed columns that were not relevant to the analysis.
10. Renamed Columns


![applied steps](https://github.com/rakiya30/Call-Centre-Trends/assets/154539987/c70570eb-7802-4380-88f4-d94b3c5ec79b)

### Data Modelling

The dataset comprised of just one table that was modelled into into four tables creating a one to many relationship to the fact table


![Data modelling phone now](https://github.com/rakiya30/Call-Centre-Trends/assets/154539987/d21faf36-50dd-4bfc-afd9-22ae7c7327c8)

### Dax Measures Creation

In addition to the data cleaning and data modelling,I created some Mesures to gain critical and deeper insights. 

the following measures were created:
- Total calls Resolved (
- Total calls Unresolved
- Overall customer satisfaction
- Count of satisfaction Rating

### Exploratory Data Analysis
- What is the Overall customer satisfaction?
- Overall calls answered/abandoned
- Calls by time
- What is the Average speed of answer by agent?
- Agents performance quadrant (average handle time talk duration/calls answered)
- What is the total number of calls resolved?
- what is the average satisfaction rating?

### Data Analysis/ Insights


![Phone Now Call Centre Trends](https://github.com/rakiya30/Call-Centre-Trends/assets/154539987/a6aa831d-4d37-4f64-94ba-e6d5dd502f7d)


The results of my analysis is summarized as follows:

1. A total of 4054 calls where answered by the agents.
2. A total of 946 calls were abandoned.
3. 54.75 accounted for the average speed of answer in seconds.
4. 40.46 overall customer satisfaction.
5. Agent Martha had the highest sped of answer in seconds and was 13.14% higher than Stewart which had the lowest speed of answer in seconds.
6. Accross all 8 agents the speed of answer in second ranged from 31570 - 35717.
7. Agent Jim had the highest number of calls answered at 536 with an overall satisfaction rate of 40.24%.
8. Agent Stewart had the highest number of calls abandoned with a total of 105 unanswered calls.
9. Agent Dan had the highest number of calls answered that was resolved at 471.



 



