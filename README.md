# IBM Data Analyst Capstone Project

This repository contains my final capstone project for the IBM Data Analyst Specialization. The project showcases my data analysis, visualization, and reporting skills developed over the course of the program using the Stack Overflow Developer Survey dataset. The project covers various aspects of data analytics, including data distribution, outlier detection, correlation analysis, and creating a dashboard to visualize key trends.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Key Findings](#key-findings)
4. [Technologies Used](#technologies-used)
5. [How to Run the Project](#how-to-run-the-project)
6. [Conclusion](#conclusion)
7. [Certification](#certification)

## Project Overview

This project analyzes the **2019 Stack Overflow Developer Survey** dataset to uncover insights about the technologies developers use, future technology trends, and demographic patterns. The project culminates in a fully interactive dashboard created using **IBM Cognos Analytics**, which allows users to explore these insights.

## Data Sources

We utilized two main datasets:

1. **Demographics Data** (`m5_survey_data_demographics.csv`): Contains information about respondent demographics.
2. **Technologies Data** (`m5_survey_data_technologies_normalised.csv`): Contains information about the technologies respondents currently use and want to learn.

These datasets are modified subsets from the original Stack Overflow Developer Survey 2019 dataset.

## Key Findings

1. **Top Technologies Used**: HTML/CSS, Java, Bash/Shell/PowerShell, and JavaScript were the most commonly used languages. MySQL and PostgreSQL led the database usage.
   
2. **Future Technology Trends**: There’s a growing interest in learning Bash/Shell/PowerShell, Elasticsearch, and MongoDB, indicating a shift towards NoSQL and performance-driven technologies.

3. **Demographic Insights**: The median respondent age was 29, with noticeable work-hour trends for mid-career professionals (ages 30-35), suggesting possible challenges with work-life balance in this group.

## Technologies Used

- **Python**: For data cleaning, analysis, and visualization
  - Libraries: `pandas`, `matplotlib`, `seaborn`
  
- **SQLite**: For querying the dataset
- **IBM Cognos Analytics**: For creating dashboards and visualizations
- **Jupyter Notebook**: For coding and analysis

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/screachail/Data-Analytics-Capstone-Project.git

2. Navigate to the project directory:
   cd data-analytics-capstone-project

3. Open the Jupyter Notebook of your interest to view and run the project segment.
