---
layout: page
title: National Flood Command Center (NFCC) – CiviSenti
description: A community-driven flood intelligence system that combines WhatsApp reporting, rainfall and risk data, and AI-assisted validation for flood monitoring in Ghana.
importance: 2
category: research
---

## Overview

The **National Flood Command Center (NFCC)** is an AI-powered flood early-warning and intelligence platform designed to support flood monitoring and climate resilience in Ghana.

As part of the NFCC engineering team, I worked on **CiviSenti**, a community flood-reporting system that enables people to report flooding through WhatsApp and transforms those reports into structured information that can support flood monitoring and emergency decision-making.

## My Contribution

I designed and implemented the **CiviSenti WhatsApp Community Flood Reporting MVP**.

The system processes incoming community flood reports and extracts useful information including:

- Reporter information
- Flood location
- GPS latitude and longitude
- Description of the flooding
- Photo and media metadata
- Estimated flood severity

I developed the processing pipeline used to validate, structure, store, and summarize these community reports.

The system also checks reports against available NFCC rainfall and flood-risk data, providing an additional layer of validation before reports are surfaced for administrative review.

## CiviSenti Reporting Flow

1. A community member submits a flood report through WhatsApp.
2. The WhatsApp payload is received by the CiviSenti bot.
3. Relevant information is extracted and converted into a structured flood report.
4. The report is validated for completeness and quality.
5. Available rainfall and flood-risk data are used to support validation.
6. Validated reports are stored for analysis and monitoring.
7. Reports are displayed on the NFCC dashboard for review.

## Dashboard Integration

I integrated CiviSenti reports into the NFCC administrative dashboard, allowing the team to monitor:

- Total community flood reports
- Validated reports
- Reports supported by rainfall/risk evidence
- Flood severity distributions
- Locations and timestamps of reported flooding

This creates a bridge between **community observations and data-driven flood intelligence**.

## Engineering & MLOps

Beyond the reporting pipeline, I also contributed to the engineering infrastructure supporting the platform.

My work included:

- Building automated validation workflows with GitHub Actions
- Developing and fixing pytest fixtures for the NFCC data pipeline
- Resolving CI/testing issues
- Documenting the CiviSenti setup and testing process
- Supporting the local WSL/Ubuntu development environment
- Integrating the feature with the existing NFCC codebase

## Impact

Flood-monitoring systems often depend primarily on centralized sensor or satellite data. CiviSenti introduces a human-centered layer by allowing communities experiencing flooding to contribute real-time observations using WhatsApp, a platform already widely accessible to users.

The project reflects my interest in building **responsible, accessible, and practical AI systems for climate resilience and societal impact in Africa**.

## Technologies

Python · WhatsApp Integration · Twilio · Streamlit · GitHub Actions · Pytest · Data Validation · Applied AI · Climate Technology · CI/CD

## Repository

[View the NFCC Platform on GitHub](https://github.com/NFCC-Ghana/nfcc-platform)
