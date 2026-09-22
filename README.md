Excelerate DVA Team 15 — Data Visualization Associate Project

📌 Project Overview

This repository documents my work as part of Team 15 during the Data Visualization Associate Remote Internship, supported by Saint Louis University and powered by Excelerate.

The project focused on preparing learner and opportunity data for reliable analysis and reporting. My work involved data integration, cleaning, validation, standardization, quality checks, analysis, and visualization.

A major part of the project was identifying data-quality issues that could affect downstream reporting and ensuring that the integrated dataset was clean and consistent enough to support reliable analysis.

Project Period: July–August 2026
Role: Data Visualization Associate Intern
Team: Excelerate DVA Team 15
Partner Institution: Saint Louis University


🎯 Project Objective

The main objective was to transform multiple datasets containing learner and opportunity information into a more reliable dataset that could support analysis and visualization.

The project involved:

* Integrating learner and opportunity data
* Identifying data-quality issues
* Removing corrupted and duplicate records
* Standardizing categorical values
* Cleaning date fields
* Handling missing and invalid values
* Identifying test and placeholder records
* Validating the resulting dataset
* Preparing the cleaned data for analysis and reporting
* Communicating findings through visualizations and presentations


🗂️ Data Integration

The learner and opportunity datasets were integrated using the relationship between:

* learner_data.sk
* opportunity_data.opportunity_id

Different candidate fields were tested before establishing the usable relationship between the datasets.

Final Integration Results

* 14,825 rows in the final integrated dataset
* 14,709 rows containing opportunity details
* 99.2% usable match rate
* 0 duplicates after the final cleaning process


🧹 Data Cleaning & Validation

A detailed data-quality review was carried out before the data was used for analysis.

Duplicate & Corrupted Records

* Removed 204 corrupted/duplicate rows
* Identified 45 additional problematic records through key validation
* Performed a final duplicate check, which returned zero duplicates

Categorical Standardization

* Standardized four categorical fields to ensure consistent values across the dataset.

Test & Placeholder Records

* Identified 86 test/placeholder opportunities
* Set affected opportunity fields to NULL rather than treating test records as genuine opportunity information.

Date Validation

* Standardized date fields to improve consistency and usability for analysis.

Numeric Validation

* Identified invalid numeric outliers in three fields
* Nulled invalid values rather than allowing them to distort analysis.

Missing-Value Analysis

* Audited missing values across the integrated dataset.
* Applied appropriate cleaning and backfilling where supported by the available data.
* Overall missingness was reduced from approximately 61.2% to below 1% after the cleaning process.


📊 Data Quality Results

Metric	Result
Final integrated records	14,825
Records with opportunity details	14,709
Usable join match rate	99.2%
Corrupted/duplicate records removed	204
Additional issues identified through key validation	45
Test/placeholder opportunities identified	86
Final duplicate check	0 duplicates
Missingness after cleaning	<1%

These checks improved the reliability of the dataset and reduced the risk of using inconsistent or invalid records in subsequent analysis.


📈 Analysis & Visualization

After the data-cleaning and validation stage, the prepared dataset was used for analytical reporting and visualization.

The project included:

* Exploratory analysis of learner and opportunity data
* Identification of relevant patterns and trends
* Dashboard development
* Visual reporting
* Presentation of findings to the team
* Recommendations based on the available data

The visualization stage helped make the prepared data easier to understand and supported data-driven discussions.


🧠 Key Learning & Business Value

One of the major lessons from the project was that data quality comes before reliable analysis.

Incomplete, duplicated, inconsistent, or incorrectly classified records can affect the reliability of dashboards and business decisions. The cleaning and validation process therefore served as an important foundation for the subsequent analytical work.

The project strengthened my practical experience in:

* Data quality assessment
* Data cleaning
* Data validation
* Data integration
* SQL-based data work
* Exploratory data analysis
* Data visualization
* Business reporting
* Communicating analytical findings
* Working collaboratively in a remote team


🛠️ Tools & Technologies

* SQL
* PostgreSQL
* pgAdmin
* Looker Studio
* Microsoft Excel
* Google Sheets
* GitHub


📁 Repository Structure

• Excelerate-DVA-Team15

• README.md

• Week1
   Week 1 deliverable

• Week2
   Data Cleaning & Validation deliverable

• Week3
  Dashboard & Analytical Report

• Week4
   Final Presentation
   Additional presentation materials


📄 Project Deliverables

Week 1 — Data Setup & Initial Exploration

Initial work focused on understanding the available datasets, their structure, relationships, and data-quality considerations.

Week 2 — Data Cleaning & Validation

Focused on identifying and resolving data-quality issues, integrating the datasets, standardizing values, handling missing/invalid records, and validating the final dataset.

Week 3 — Dashboard & Analytical Reporting

Focused on transforming the prepared data into analytical outputs and visual reports.

Week 4 — Final Presentation

Summarized the project process, findings, recommendations, and overall team work.


💡 Skills Demonstrated

Data Analytics

* Data cleaning
* Data validation
* Data integration
* Exploratory analysis
* Data-quality assessment

Technical

* SQL
* PostgreSQL
* Microsoft Excel
* Looker Studio
* Google Sheets

Business & Communication

* Translating data issues into business implications
* Reporting analytical findings
* Data visualization
* Recommendation development
* Team collaboration
* Remote project communication


🎓 What This Project Added to My Experience

This internship gave me practical experience working through a real-world data workflow — from raw and inconsistent records through cleaning, validation, analysis, visualization, and communication of results.

It also strengthened my interest in using data not only to produce reports, but to understand business problems, identify patterns, and support better decisions.


📌 Project Status

Completed — August 2026

Data Visualization Associate Remote Internship
Excelerate × Saint Louis University
Team 15


🔗 Repository Contents

This repository contains selected project documentation and deliverables demonstrating the workflow and analytical work completed during the internship.
