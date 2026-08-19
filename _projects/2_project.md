---
layout: page
title: National Flood Command Center (NFCC) – CiviSenti
description: A community-driven flood reporting and intelligence system that combines WhatsApp-based community reports with rainfall and flood-risk data to support flood monitoring in Ghana..
importance: 2
category: research
---

## Overview

The **National Flood Command Center (NFCC)** is a flood monitoring and early-warning platform designed to support flood intelligence and climate resilience in Ghana.

As part of the NFCC engineering team, I contributed to **CiviSenti**, a community flood-reporting system that enables people to submit flood observations through WhatsApp and transforms those reports into structured data for monitoring and analysis.

## My Contribution

I developed the **CiviSenti WhatsApp Community Flood Reporting **, focusing on the data ingestion, processing, validation, and reporting workflow.

My work included building the WhatsApp flood-report processing logic to receive and parse incoming reports, extract relevant information, validate submissions, structure the data, store processed reports, and generate report summaries.

The reporting workflow captures information such as:

* Reporter information
* Flood location
* GPS latitude and longitude
* Flood description
* Photo and media metadata
* Estimated flood severity

I also contributed to integrating available rainfall and flood-risk information into the reporting workflow to provide additional context for community-submitted observations.

## CiviSenti Reporting Flow

1. A community member submits a flood report through WhatsApp.
2. The WhatsApp payload is received by the CiviSenti bot.
3. The bot extracts relevant information from the submission.
4. The information is converted into a structured flood report.
5. Reports are validated for completeness and data quality.
6. Validated reports are processed and stored for monitoring and analysis.
7. Report summaries are generated for administrative review.
8. Community reports are surfaced through the NFCC dashboard.

## Dashboard Integration

I integrated CiviSenti community reports into the NFCC administrative dashboard, enabling monitoring of:

* Total community flood reports
* Validated reports
* Flood severity
* Report locations
* Report timestamps
* Community-submitted flood observations

This integration connects **community-generated observations with structured flood-monitoring data**.

## Data Engineering & Automation

I also contributed to the data and engineering workflows supporting CiviSenti and the broader NFCC platform.

My work included:

* Automating **CHIRPS rainfall data ingestion**
* Building automated CiviSenti validation workflows using GitHub Actions
* Implementing report processing and structured data storage
* Developing report summarization functionality
* Developing and fixing pytest fixtures for the NFCC data pipeline
* Resolving CI and testing issues
* Documenting CiviSenti setup and testing procedures
* Integrating the CiviSenti feature into the existing NFCC codebase

## Impact

CiviSenti adds a community-generated data layer to flood monitoring by enabling people to report flooding through WhatsApp. These reports can provide localized observations that complement rainfall and other environmental data, helping create a more accessible and community-centered approach to flood intelligence.

The project reflects my interest in applying **data science, data engineering, and AI technologies to practical climate and societal challenges in Africa**.

## Technologies

**Python · WhatsApp · Twilio · Streamlit · GitHub Actions · Pytest · CHIRPS · Data Ingestion · Data Validation · Data Processing · Data Pipelines · CI/CD**

## Repository

[View the NFCC Platform on GitHub](https://github.com/NFCC-Ghana/nfcc-platform)
