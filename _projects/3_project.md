---
layout: page
title: Loan Intake Agent
description: A conversational AI agent that helps customers navigate vehicle financing through application intake, loan simulation, prequalification, document retrieval, FAQs, and loan-offer tracking.
importance: 3
category: work
---

## Overview

The **Loan Intake Agent** is a conversational AI system I worked on at **Autochek Africa** to help customers navigate the vehicle-financing process through a single conversational interface.

The agent was designed around a set of specialized tools that allowed it to handle different stages of the financing journey. Instead of functioning only as a question-and-answer chatbot, it could understand what a customer was trying to accomplish and use the appropriate tool to support the workflow.

The agent supported six core capabilities:

- **Application Details** — collecting information required for a financing application
- **FAQs** — answering common questions about the financing process
- **Loan Documents** — helping customers obtain required loan documents
- **Loan Simulation** — allowing customers to simulate financing scenarios
- **Prequalification** — supporting the customer prequalification workflow
- **Loan Offer Status** — allowing customers to check the status of their loan offer

## Problem

The vehicle-financing journey involves several different customer interactions. A customer may need to ask questions, provide application information, obtain documents, estimate loan repayments, complete prequalification, and later follow up on the status of a loan offer.

These activities can become fragmented when each capability is handled through a separate workflow or interface.

The goal of this project was to provide a conversational entry point that could connect customers to these financing workflows while maintaining a natural interaction.

## My Contribution

I contributed to the design and development of the loan-intake agent and its conversational workflows.

My work involved:

- Designing conversational flows for loan intake
- Integrating the agent with specialized tools
- Collecting and structuring application information
- Working with tool/function calling
- Handling different customer intents
- Connecting conversational interactions with backend workflows
- Designing how information should move between the conversational layer and individual tools

A central part of the work was determining when the agent should respond directly and when it should invoke a tool to perform an operation or retrieve information.
## Conversational Loan Intake

The agent provides a conversational interface through which customers can provide relevant information for a financing application.

Instead of relying entirely on static forms or repeated manual interactions, the system guides users through the information-collection process and converts their responses into structured application data.

This creates a more accessible and efficient intake experience while supporting downstream analytical workflows.

## Agent Tools

#### Application Details

The application-details tool supported the collection of information required during the loan-application process.

The conversational interface allowed customers to provide information naturally while the underlying workflow handled the structured application data required by the financing process.

#### FAQs

The FAQ capability allowed customers to ask questions about the financing process and receive relevant answers through the same conversational interface.

#### Loan Documents

The loan-document capability helped customers access the documents required as part of the financing process.

#### Loan Simulation

The loan-simulation tool allowed customers to explore financing scenarios conversationally.

#### Prequalification

The prequalification capability supported the process of determining whether a customer could proceed to the next stage of the financing journey.

#### Loan Offer Status

The loan-offer-status capability allowed customers to check the status of an existing loan offer.
## Agentic Workflow

The core of the system was the interaction between the conversational agent and its specialized tools.

A typical interaction could involve:

1. A customer starts a conversation about vehicle financing.
2. The agent determines the customer's intent.
3. If the customer has a general question, the FAQ capability is used.
4. If the customer wants to apply, the application-details workflow collects the required information.
5. If the customer wants to understand repayment scenarios, the loan-simulation tool is used.
6. The customer can proceed through the prequalification workflow.
7. The customer can later retrieve required documents or check the status of a loan offer.

This allowed multiple related financing capabilities to be accessed through a single conversational interface.

## Business Impact

The agent was designed to make the financing journey more accessible and reduce friction by bringing several customer-facing capabilities into a single conversational experience.

It supported:

- More conversational loan intake
- Easier access to financing information
- Reduced need for repetitive customer interactions
- A unified interface for multiple financing workflows
- Easier access to loan simulations and application-related processes
- Self-service follow-up on loan offers
## Responsible AI

Because the system operates within a financial-services workflow, reliability and responsible handling of customer information are important considerations.

The agent was designed to support and facilitate financing workflows rather than independently make final financial decisions. This distinction is particularly important when applying conversational AI to financial services.

## Technologies

Python · Machine Learning · Predictive Analytics · Conversational AI · Agentic AI · Workflow Automation · Data Analytics
