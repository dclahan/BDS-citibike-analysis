# 🚲 CitiBike Big Data Analysis
### NYU Big Data Science — Final Project
**Stack:** Databricks Community Edition · Apache Spark · PySpark · Python

---
## Overview
This project analyzes large-scale CitiBike trip data using Apache Spark on Databricks Community Edition. The goal is to demonstrate big data processing principles — distributed computation, lazy evaluation, in-memory processing, and scalable analytics — on a real-world dataset.

---
## Prerequisites
- A free [Databricks Community Edition](https://community.cloud.databricks.com/login.html) account
- A browser
- CitiBike trip data (see [Data](#data) section below)

---
## Environment Setup
### 1. Create a Databricks Account
1. Go to [community.cloud.databricks.com](https://community.cloud.databricks.com/login.html)
2. Sign up for a **free Community Edition** account
3. Verify your email and log in

> ⚠️ Community Edition gives you a single-node Spark cluster with ~5-10GB RAM. This is not sufficient for multi-year CitiBike subsets.

---
### 3. Clone repository in Notebooks
1. Go to **Workspace** → **Home** → click **Import** → **Git Folder**
2. Paste git hash and run notebook 01 for data ingestion
   - free plan gets ratelimited for > 2months or > 10 mil rows of data
3. Tables will be saved and usable from any other notebook after that
   - might be slow, thats what I found 
