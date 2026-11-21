Healthcare Analytics Dashboard

An end-to-end healthcare data analytics project using Python, Pandas and Power BI to explore hospital admissions, patient demographics, medical conditions, billing patterns and length of hospital stays.

The project focuses on transforming raw healthcare records into meaningful insights through data preparation, exploratory data analysis and interactive dashboard visualization.

Project Overview

Healthcare organizations generate large volumes of patient and hospital data. Analyzing this information can help identify admission patterns, understand billing distribution and monitor hospital stay durations.

This project explores a healthcare dataset containing 55,500 patient records to examine operational and financial patterns across hospitals, medical conditions and admission categories.

Objectives

Explore patient demographics and medical conditions.

Analyze hospital admissions across different categories.

Examine healthcare billing distribution.

Calculate and analyze patient length of stay.

Identify patterns across medical conditions and admission types.

Present key findings through an interactive Power BI dashboard.

Technology Stack

Tool

Purpose

Python

Data analysis and preparation

Pandas

Data manipulation and cleaning

Matplotlib / Seaborn

Exploratory data visualization

Power BI

Interactive dashboard development

Jupyter Notebook

Analysis environment

Dataset Description

The dataset contains 55,500 records and 15 columns.

Key attributes include:

Category

Attributes

Patient Information

Age, Gender, Blood Type

Medical Information

Medical Condition, Medication, Test Results

Hospital Information

Hospital, Doctor, Room Number

Admission Details

Admission Type, Date of Admission, Discharge Date

Financial Information

Billing Amount, Insurance Provider

Project Workflow

1. Data Exploration

Loaded the dataset using Pandas.

Examined dataset dimensions, column names and data types.

Checked for missing values.

Performed descriptive statistical analysis.

2. Data Cleaning and Preparation

Converted admission and discharge dates into datetime format.

Standardized patient name capitalization.

Created a new Duration column to calculate hospital stay duration.

Identified negative billing values and excluded those records from billing analysis.

3. Exploratory Data Analysis

Analyzed billing amount distribution.

Examined average hospital stay duration across medical conditions.

Explored patient demographics and medical categories.

Investigated admission and healthcare-related patterns.

4. Power BI Dashboard

Developed a Power BI dashboard to present healthcare metrics and analytical findings in a visual format.

Repository Structure

healthcare-analytics-dashboard/
│
├── Health_care_analytics.ipynb
├── Health_care.pbix
├── Screenshot 2026-05-18 095631.png
└── README.md

Dashboard Preview



Key Analytical Areas

Patient demographics and medical conditions

Hospital admission patterns

Billing amount distribution

Average length of hospital stay

Comparisons across medical conditions
