# WIP Update Automation Engine

A Python-based data automation solution designed to streamline production Work-In-Progress (WIP) management by automatically reconciling update files against master production datasets.

## Overview

Managing WIP spreadsheets manually is time-consuming, error-prone, and difficult to scale across large production environments. This project automates the process of comparing, validating, and updating WIP records using incoming update files.

The solution reduces manual effort, improves data accuracy, and provides a repeatable workflow for production planning and operational reporting.

## Business Problem

Production teams frequently receive updated WIP files containing revised quantities, statuses, and production information.

Traditional workflows require:

- Manual Excel lookups
- Copy-pasting between sheets
- Data validation checks
- Record matching across multiple attributes
- Error-prone updates

This automation eliminates those repetitive tasks and ensures consistent updates across datasets.

## Solution

The automation pipeline:

1. Loads the original WIP dataset
2. Loads the latest update file
3. Matches records using business keys
4. Applies updates automatically
5. Preserves existing data integrity
6. Generates a refreshed WIP output file
7. Produces audit-friendly comparison results

## Key Features

- Automated Excel processing
- Multi-column record matching
- Production data reconciliation
- Update validation
- Error reduction
- Scalable workflow
- Repeatable execution
- Business-friendly outputs

## Technology Stack

- Python
- Pandas
- NumPy
- OpenPyXL
- Jupyter Notebook

## Data Engineering Concepts Demonstrated

- ETL-style processing
- Data transformation pipelines
- Data quality validation
- Record matching logic
- Automated reporting
- Batch processing
- Operational data workflows

## Workflow

```text
Original WIP File
        │
        ▼
Data Validation
        │
        ▼
Update File Ingestion
        │
        ▼
Record Matching Engine
        │
        ▼
Transformation Logic
        │
        ▼
Updated WIP Output
        │
        ▼
Comparison & Audit Report
