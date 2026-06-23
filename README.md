# 🏈 NFL Sports Betting Analytics Platform

## Overview

The NFL Sports Betting Analytics Platform is an end-to-end data engineering and analytics project designed to integrate NFL game, betting, customer, weather, and stadium data into a centralized PostgreSQL database.

This project demonstrates database design, ETL development, SQL analytics, and statistical modeling by transforming multiple independent data sources into a unified analytics environment capable of supporting sportsbook reporting and customer behavior analysis.

---

### Entity Relationship Diagram

![ERD](images/ERD.png)

---

## Project Objectives

* Design a normalized relational database for sportsbook operations
* Integrate multiple NFL-related datasets into a single platform
* Build ETL workflows to clean and transform source data
* Generate analytical reports using SQL
* Evaluate customer profitability and betting performance
* Apply statistical modeling techniques to identify factors influencing customer value

---

## Technology Stack

| Category                | Technologies     |
| ----------------------- | ---------------- |
| Database                | PostgreSQL       |
| Programming             | Python           |
| Data Processing         | Pandas, NumPy    |
| Analytics               | SQL              |
| Statistical Modeling    | StatsModels      |
| Development Environment | Jupyter Notebook |

---

## Database Architecture

The database consists of six primary entities:

### Customer

Stores customer demographic and account information.

### Bet

Captures wagering activity, betting outcomes, and commission calculations.

### Game

Contains NFL game details including teams, scores, and outcomes.

### Team

Stores team-level information used for game and betting analysis.

### Stadium

Maintains venue information and stadium characteristics.

### Station

Stores weather station data used to evaluate environmental impacts on games.

---

## ETL Workflow

Raw Data Sources

⬇

Python / Pandas Data Cleaning

⬇

Data Transformation & Validation

⬇

PostgreSQL Relational Database

⬇

SQL Analytics & Reporting

⬇

Statistical Modeling & Insights

---

## Key Features

### Database Design

* Normalized relational schema
* Primary and foreign key constraints
* Referential integrity enforcement
* Multi-table analytical queries

### ETL Development

* Data cleansing and validation
* Data transformation workflows
* Batch loading into PostgreSQL
* Automated preprocessing using Pandas

### SQL Analytics

Examples of analytical questions addressed:

* Which customers generate the highest commission revenue?
* Which teams produce the most profitable betting opportunities?
* How does betting activity vary throughout the NFL season?
* Which customer segments are most valuable?

### Statistical Modeling

Regression analysis was performed to evaluate relationships between customer attributes and customer value.

Variables analyzed include:

* Age
* Income
* Household size
* Betting preferences
* Customer demographics

---

## Business Value

This project demonstrates how sportsbook organizations can:

* Track customer profitability
* Measure betting performance
* Analyze commission revenue
* Identify high-value customer segments
* Support data-driven business decisions

---

## Skills Demonstrated

### Data Engineering

* Database Design
* ETL Development
* Data Integration
* Data Quality Management

### Analytics

* SQL Reporting
* Statistical Analysis
* Customer Segmentation
* Business Intelligence

### Technical Skills

* PostgreSQL
* SQL
* Python
* Pandas
* NumPy
* StatsModels
* Jupyter Notebook

---

## Repository Structure

```text
NFL-Sports-Betting-Analytics-Platform/

├── notebooks/
│   └── fp_alikimatangi.ipynb
│
├── docs/
│   ├── Data_Dictionary.xlsx
│   └── Portfolio_Case_Study.pdf
│
├── images/
│   └── ERD.png
│
├── sql/
│   └── analytics_queries.sql
│
└── README.md
```

---

## Resume Highlights

* Designed and implemented a PostgreSQL sports betting analytics platform integrating NFL game, weather, stadium, customer, and wagering datasets.
* Developed Python ETL pipelines using Pandas to cleanse, transform, and load multi-source data.
* Created SQL reporting solutions to analyze customer profitability, commission revenue, and betting performance.
* Applied statistical modeling techniques to identify factors influencing customer value and betting behavior.

---

## Author

**Aliki Matangi**

Aspiring Data Analyst | Analytics Engineer | Data Engineer

GitHub: https://github.com/aliki-matangi
