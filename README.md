# Enterprise Healthcare Analytics Platform

End-to-end Healthcare Analytics Engineering project built with Microsoft Fabric, Power BI, PySpark, Lakehouse architecture, and enterprise-style data modeling.

---

## Project Overview

This project simulates a modern enterprise healthcare analytics platform using Microsoft Fabric.

The platform implements a complete analytics engineering workflow:

- Raw healthcare data ingestion
- Multi-layer Lakehouse architecture
- Data transformation pipelines
- Gold layer business modeling
- Warehouse serving layer
- Semantic modeling
- Executive Power BI dashboards

---

## Architecture

![Architecture](architecture/fabric-healthcare-architecture.png)

---

## Technology Stack

- Microsoft Fabric
- Power BI
- PySpark
- SQL
- Lakehouse Architecture
- Warehouse
- Data Pipelines
- Semantic Modeling
- ETL / ELT

---

## Data Architecture

### Bronze Layer
Raw healthcare CSV ingestion into Lakehouse storage.

### Silver Layer
Cleaned and transformed datasets using Fabric Dataflows.

### Gold Layer
Business-ready analytical tables modeled with PySpark notebooks.

Implemented Gold tables:

- dim_patient
- dim_doctor
- dim_treatment
- dim_date
- fact_appointments
- fact_billing

---

## Pipeline Orchestration

The project includes automated Fabric pipeline orchestration for:

- notebook execution
- data movement
- warehouse loading
- dependency handling

---

## Power BI Dashboards

### Executive Overview

![Executive Overview](screenshots/executive-overview.png)

### Operational Analytics

![Operational Analytics](screenshots/operational-analytics.png)

### Financial Analytics

![Financial Analytics](screenshots/financial-analytics.png)

---

## Key Business Metrics

- Revenue Analytics
- Appointment Trends
- Doctor Performance
- Cancellation Rate
- No-show Analysis
- Payment Status Analysis
- Treatment Revenue Analysis

---

## Enterprise Concepts Practiced

- Medallion Architecture
- Star Schema Modeling
- Semantic Modeling
- ETL / ELT Pipelines
- Data Warehouse Integration
- Analytics Engineering
- Business Intelligence Reporting

---

## Author

Emre BAKIR

LinkedIn:
www.linkedin.com/in/emre-bakir