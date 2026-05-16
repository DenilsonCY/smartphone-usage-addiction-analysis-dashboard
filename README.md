# smartphone-usage-addiction-analysis-dashboard
# Smartphone Usage & Addiction Analysis Dashboard

## Project Overview

This project focuses on analyzing smartphone usage behavior and addiction patterns using demographic, behavioral, and mental health-related data. The analysis was performed using Microsoft Excel for preprocessing and Microsoft Power BI for dashboard development and business intelligence reporting.

The project studies the relationship between smartphone usage, sleep patterns, stress levels, notifications, app usage behavior, and addiction tendencies.

---

# Project Objective

The objective of this project is to analyze smartphone usage behavior and addiction patterns using demographic, behavioral, and lifestyle data. The project aims to identify relationships between screen time, sleep patterns, stress levels, and smartphone dependency.

The project was developed to:

* Analyze user smartphone engagement patterns
* Identify addiction-related behavior
* Understand the effect of screen time on wellbeing
* Study stress and sleep-related behavioral changes
* Build an interactive dashboard for analytical storytelling
* Demonstrate preprocessing, relational modeling, and interactive BI reporting

---

# Dataset Description

The dataset contains behavioral and demographic information related to smartphone usage.

## Main Dataset Features

* User demographics
* Daily screen time
* Social media usage
* Gaming hours
* Work/study hours
* Sleep duration
* Notifications received
* App opens per day
* Stress level indicators
* Addiction-related behavior
* Academic/work impact

---

# Excel Preprocessing & Data Cleaning

Data preprocessing was completed using Microsoft Excel before importing the dataset into Power BI.

## Data Cleaning Activities Performed

### 1. Duplicate Checking

The dataset was checked for duplicate records, and no duplicate entries were identified.

### 2. Missing Value Handling

Missing values were identified and handled appropriately to ensure data consistency.

### 3. Standardization

Categorical values were standardized for consistent analysis and visualization.

### 4. Calculation Corrections

Time-based calculation inconsistencies were corrected to improve analytical accuracy.

### 5. Sorting & Filtering

Sorting and filtering operations were applied using multiple categories for better data validation and segmentation.

### 6. Conditional Formatting

Conditional formatting techniques were used to highlight important categories and behavioral indicators.

---

# Calculated Columns & IF Logic Implementation

Several calculated columns were created using IF conditions and logical formulas.

| Calculated Column        | Purpose                                            |
| ------------------------ | -------------------------------------------------- |
| Age_Group                | Categorize users based on age                      |
| Usage_Category           | Classify users based on smartphone usage intensity |
| Sleep_Risk               | Identify sleep-related risk levels                 |
| Weekend_Usage            | Analyze weekend smartphone behavior                |
| addicted_label_new       | Identify addiction status                          |
| stress_level_new         | Categorize stress intensity                        |
| academic_work_impact_new | Analyze academic/work impact                       |

Behavioral indicators such as stress level, academic impact, and addiction status were derived using logical IF conditions based on:

* screen time
* sleep duration
* notifications
* app usage activity
* weekend usage behavior

---

# Dataset Splitting & Relational Modeling

To demonstrate relational modeling and report connection concepts in Power BI, the dataset was divided into multiple subject-oriented tables.

## Created Tables

### 1. user_details

Contains:

* user_id
* age
* gender
* Age_Group

### 2. usage_data

Contains smartphone usage behavior information.

### 3. mental_health_data

Contains stress, sleep, addiction, and academic impact indicators.

## Relationship Modeling

Relationships were created using:

# user_id

Relationship Structure:

```text
          user_details (1)
             /       \
            /         \
 usage_data (*)   mental_health_data (*)
```

This structure demonstrates:

* normalized data modeling
* report connection
* relational BI architecture
* dynamic filtering
* scalable dashboard interaction

---

# Power BI Dashboard Development

Interactive dashboards were created using Microsoft Power BI to analyze smartphone usage behavior and wellbeing impact.

---

# Dashboard Pages

## 1. Executive Overview

This page provides:

* demographic distribution
* average screen time analysis
* sleep overview
* notification overview
* smartphone usage segmentation

### Main Features

* KPI Cards
* Donut Charts
* Bar Charts
* Slicers
* Interactive filtering

---

## 2. Addiction & Behavioral Analysis

This page focuses on:

* addiction behavior
* stress analysis
* screen time patterns
* sleep relationship analysis
* notification behavior

### Main Features

* Scatter Plot Analysis
* Addiction by Age Group
* Stress Level Comparison
* Interactive drill-through

---

## 3. Wellbeing & Lifestyle Analysis

This page analyzes:

* sleep risk
* academic/work impact
* weekend smartphone behavior
* gaming patterns
* lifestyle impact

### Main Features

* Comparative visual analysis
* wellbeing indicators
* lifestyle-based segmentation
* interactive slicers

---

## 4. User Behavioral Details (Drill Through)

A drill-through page was created to enable detailed demographic analysis.

Users can:

* right-click an age group
* drill through into detailed behavioral analysis
* view filtered user-level data dynamically

This demonstrates advanced Power BI interactivity.

---

# DAX Measures Implemented

Several DAX measures were created for KPI indicators and dashboard analytics.

## Examples

* Total Users
* Avg Screen Time
* Avg Sleep Hours
* Avg Notifications
* Addicted Users
* High Stress Users
* Sleep Risk Users
* Avg Social Media Hours

These measures enabled dynamic dashboard reporting and interactive analysis.

---

# Power BI Features Implemented

The project includes multiple business intelligence concepts:

* KPI Cards
* DAX Measures
* Interactive Slicers
* Drill-through Functionality
* Relational Modeling
* Dynamic Filtering
* Storytelling Dashboard Design
* Scatter Plot Analysis
* Comparative Visualization
* User-Level Behavioral Analysis

---

# Key Findings

The analysis identified several important behavioral trends:

* Adults represent the largest smartphone user segment in the dataset
* Heavy smartphone usage is associated with increased stress levels
* Higher screen time users generally experience lower sleep duration
* Addicted users receive more notifications and app interactions
* Heavy smartphone users show greater academic/work impact
* Weekend usage patterns increase among high-usage users

These findings indicate a strong relationship between excessive smartphone engagement and wellbeing indicators.

---

# Technologies Used

| Tool               | Purpose                                       |
| ------------------ | --------------------------------------------- |
| Microsoft Excel    | Data cleaning & preprocessing                 |
| Microsoft Power BI | Dashboard development & business intelligence |

---

# Conclusion

This project successfully demonstrates how business intelligence tools can be used to analyze smartphone usage behavior and addiction patterns.

The project combines:

* Excel preprocessing
* logical data transformation
* relational modeling
* DAX calculations
* interactive visualization
* storytelling dashboards

The developed dashboards provide meaningful insights into smartphone dependency, stress behavior, sleep patterns, and lifestyle impact using interactive and analytical business intelligence techniques.
