🚀 Databricks 14 Days AI Challenge

Lakehouse, Apache Spark & AI-Ready Data Engineering

This repository contains my hands-on implementation of the Databricks 14 Days AI Challenge — a structured learning program focused on mastering Databricks Lakehouse fundamentals, Spark analytics, data engineering workflows, and preparation for AI/ML solutions.

The goal is to build production-style data pipelines on the Databricks Lakehouse platform and apply them to large-scale e-commerce data processing & analytics.

📌 Challenge Overview

Participants explore Databricks and Spark fundamentals, build scalable workflows, and apply advanced transformations while sharing progress publicly. The challenge includes guided lessons, tasks, and real-world learning on the Databricks platform.

Key focus areas:

Databricks Lakehouse architecture

Apache Spark & PySpark essentials

Data ingestion, transformation, and analytics

Delta Lake for reliability and governance

Preparation for downstream AI/ML applications

🧰 Technology Stack
Component	Purpose
Databricks	Unified data & AI platform
Apache Spark (PySpark)	Distributed data processing
Delta Lake	ACID tables, schema enforcement
Unity Catalog & Volumes	Governed storage & metadata
SQL / Python	Notebook workflows
GitHub	Version control & sharing
Power BI (upcoming)	Downstream visualization
ML & AI pipelines (upcoming)	Predictive modeling & features
📂 Repository Structure
databricks-14days-ai-challenge/
│
├── Day01-PlatformSetup/      # Intro to Databricks & workspace
├── Day02-SparkFundamentals/  # Spark architecture & DataFrames
├── Day03-Transformations/    # Joins, window functions, UDFs
├── Day04-DeltaGovernance/    # Delta tables, Unity Catalog
├── ingestion/                # Ingestion notebooks & scripts
├── bronze/                   # Raw/refined tables
├── silver/                   # Cleaned business data
├── gold/                     # Analytics/feature datasets
├── ai_ml/                    # Features for AI & ML
└── README.md

📊 Data Description

This project works with large multi-month e-commerce event datasets (~5 GB+), enabling realistic ingestion and transformation scenarios. Data is organized, processed, and validated using Databricks volumes and Delta Lake tables.

💻 What You’ll Find Here
✔ Databricks Platform Setup

Signup & environment configuration

Workspace, cluster, and notebook navigation

✔ Apache Spark Analytics

Understanding drivers, executors, DAGs

DataFrames vs RDDs

Lazy evaluation & notebook magic (%sql, %python, %fs)

✔ Advanced Transformations

Complex joins (inner/outer/left/right)

Window functions for rolling totals & ranking

User-Defined Functions (UDFs)

✔ Delta Lake & Governance

Delta table creation & optimization

Schema enforcement & evolution

Unity Catalog integration and data governance

🎯 Challenge Goals

Build enterprise-grade social/e-commerce data pipelines

Learn to manage data at scale using Lakehouse patterns

Prepare cleaned datasets for AI & ML tasks

Share progress publicly on social channels using designated tags

🙌 Acknowledgements

This challenge is organized and supported by:

Databricks – Unified Lakehouse platform provider

Codebasics – Content guidance & materials

Indian Data Club – Community host & orchestrator

Huge thanks for enabling structured, hands-on learning!

📌 Official Challenge Tags
#DatabricksWithIDC #Databricks #IndianDataClub #Codebasics
