# Healthcare-SQL-PowerBI-Project

This project aims to analyze the OCD patient dataset and visualize meaningful insights through Power BI. The data includes details about patients' symptoms, diagnoses, medications, and demographics. SQL queries are used to extract important metrics, and Power BI is used to build interactive dashboards.

## Table of Contents
- [Introduction](#introduction)
- [SQL Queries](#sql-queries)
  - [Average Duration of Symptoms](#average-duration-of-symptoms)
  - [Family History of OCD](#family-history-of-ocd)
  - [Most Common Obsession Type](#most-common-obsession-type)
  - [Diagnosis Analysis](#diagnosis-analysis)
  - [Y-BOCS Scores](#y-bocs-scores)
- [Power BI Dashboard](#power-bi-dashboard)
  - [Visualizations](#visualizations)
  - [Steps to Build Dashboard](#steps-to-build-dashboard)
- [How to Run](#how-to-run)
- [License](#license)

## Introduction

This project focuses on the analysis of OCD patient data. The dataset contains information on patients' symptoms, diagnoses (e.g., depression, anxiety), medications, and personal demographics (e.g., age, marital status, education). SQL queries are used to extract the data, and Power BI is used to visualize the insights.

## SQL Queries

Below are some of the key SQL queries used to generate insights from the OCD patient dataset.

### Average Duration of Symptoms
**SQL Query**:
```sql
SELECT AVG(`Duration of Symptoms (months)`) AS Average_Duration
FROM ocd_patient;
