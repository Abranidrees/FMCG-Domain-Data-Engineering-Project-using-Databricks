# FMCG-Domain-Data-Engineering-Project-using-Databricks
End-to-end Databricks data pipeline using Medallion Architecture to unify analytics across a large enterprise (Atlikon) and an acquired startup (SportBar), delivering consolidated Gold-layer insights for executive dashboards.

## Introduction
Atlikon is a large sports product manufacturing company with a mature data platform based on an OLAP system and a Medallion Architecture (Bronze, Silver, Gold). Recently, Atlikon acquired a small startup, SportBar, which produces energy bars and nutrition drinks. While Atlikon operates a structured, scalable analytics pipeline, SportBar relies on a simple transactional database and manual Excel-based reports and dashboards. This repository demonstrates how a unified data pipeline can be designed using Databricks and the Medallion Architecture to integrate data from both organizations and deliver consolidated, business-ready insights to leadership.
## Problem Statement
After the acquisition, the CEO needs a single, unified view of product performance across both Atlikon and SportBar to support strategic decision-making. However, several challenges exist:
- Atlikon uses a structured Bronze–Silver–Gold OLAP architecture
- SportBar lacks data layers and relies on:
    - Raw databases
    - Manual Excel reporting
- Data models, metrics, and granularity differ between companies
- No centralized, scalable pipeline exists for combined analytics
These differences make it difficult to generate consistent KPIs, dashboards, and cross-company insights.
## Solution
The proposed solution uses Databricks with Medallion Architecture to standardize and integrate data from both companies.
