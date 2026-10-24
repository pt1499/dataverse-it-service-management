# IT Service Request Management System

## Project Overview

The IT Service Request Management System is a Microsoft Power Platform project built with Microsoft Dataverse. It is designed to help an organization manage internal IT requests through a structured and maintainable data model.

## Business Problem

Organizations often track internal IT requests through emails or spreadsheets. This can make request ownership, prioritization, access management, and reporting difficult.

This project aims to provide a centralized approach to recording and managing service requests.

## Project Objectives

- Design a normalized and maintainable Dataverse data model.
- Use appropriate column data types and table relationships.
- Build a user-friendly model-driven Power App.
- Apply business rules and Dataverse security principles.
- Document solution architecture and design decisions.
- Introduce solution-based ALM and source control as the project evolves.

## Planned Features

- Service request creation and tracking.
- Priority and category classification.
- Department and requester relationships.
- Support agent assignment.
- Views for open and resolved requests.
- Role-based access design.
- Automation and notifications in later iterations.
- Documented solution deployment process.

## Technology Stack

- Microsoft Power Platform
- Microsoft Dataverse
- Power Apps model-driven apps
- Power Automate
- Power Platform CLI and GitHub (planned for later ALM stages)

## Repository Structure

```text
dataverse-it-service-management/
├── README.md
├── docs/
│   ├── data-model.md
│   ├── data-dictionary.md
│   ├── security-design.md
│   └── architecture-decisions.md
├── solution/
│   └── README.md
└── test-cases/
    └── week-1-validation.md
```

## Development Approach

The solution will be developed incrementally in a Power Platform Developer environment. Requirements, architecture decisions, implementation notes, and test results will be documented throughout development.

## Current Status

- [x] Project scope defined
- [ ] Environment inspection completed
- [ ] Initial data model documented
- [ ] Dataverse tables configured
- [ ] Model-driven app implemented
- [ ] Security design validated
- [ ] Solution ALM and deployment documented

## Disclaimer

This project is for learning and portfolio project. All sample records and business scenarios should use fictional data.
