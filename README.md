# Maven Fuzzy Factory E-Commerce Information System

**Tools:** Snowflake (SQL), Power BI (DAX, Power Query, Data Modelling), Excel

## Project Overview

This project translates commercial e-commerce questions into analytical requirements across acquisition channels, customer behaviour, conversion performance, products, refunds, and profitability.

## Key Contributions

- Analysed more than **1.7 million records** across six relational tables using Snowflake SQL, validating completeness, date ranges, relationships, joins, and metric consistency.
- Developed reusable Snowflake SQL analytics views with standardised definitions for revenue, gross profit, conversion rate, refund rate, bounce rate, sessions, orders, and revenue per session.
- Built a four-page interactive Power BI dashboard covering executive performance, marketing performance, product performance, and landing-page performance.
- Tracked **472.9K sessions**, **32.3K orders**, **$1.94M revenue**, and **$1.22M gross profit** across channels, devices, products, and time periods.
- Identified **gsearch** as generating **66% of total revenue**, a mobile conversion rate of **3.09%** compared with **8.50%** on desktop, and a high-traffic landing page requiring optimisation.
- Documented data definitions, validation checks, analytical reasoning, and recommendations for technical and non-technical stakeholders.

## Dashboard

[Open the live Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiMTVmMmU3OWItMGY3OS00ZTQ0LWI3YjMtNzE3ZDA2ZThhOWNmIiwidCI6ImJlOTdiY2NhLWEzZTItNDc4Yy1iMWM1LWQ5YTRkMWI2NTY3YyJ9)

## Project Structure

```text
datasets/                                      Raw Maven Fuzzy Factory CSV files
Maven Fuzzy Factory SQL Power BI Project/
├── sql/                                       Database setup, validation, and analytics views
├── powerbi/                                   Power BI report, SQL exports, and dashboard screenshots
├── reports_and_demonstrations/                Project documentation
└── README.md                                  Project summary
```

## Data Source

Data source: [Maven Analytics — Toy Store E-Commerce Database](https://mavenanalytics.io/data-playground/toy-store-e-commerce-database)
