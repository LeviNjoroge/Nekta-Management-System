# NEKTA Management System

**Developer:** Levi Njoroge Junior  
**Year:** 2022  

---

## Table of Contents
- [Overview](#overview)
- [System Features](#system-features)
- [Project Scope and Objectives](#project-scope-and-objectives)
- [System Design](#system-design)
- [System Implementation](#system-implementation)
- [User Guide](#user-guide)
- [Installation Requirements](#installation-requirements)
- [Troubleshooting](#troubleshooting)
- [License](#license)

---

## Overview
The **NEKTA Management System** (NektaMS) is an automated information management system designed to streamline operations for Nekta, a company involved in beekeeping and honey sales. The system replaces the existing manual file system, improving accuracy and efficiency in managing farmer registrations, processing orders, and generating reports.

## System Features
The system offers:
- **Farmer Registration**: Stores details for each farmer, reducing repetitive data entry.
- **Order and Sales Processing**: Automates tracking of customer orders and sales.
- **Transport Management**: Tracks transport requests, costs, and logistics for product deliveries.
- **Training Management**: Registers trainees and manages training schedules and payments.
- **Report Generation**: Automatically generates various reports to support company decision-making.

## Project Scope and Objectives
### Main Objective
To improve Nekta’s operational efficiency and profitability through automation.

### System Objectives
- Enable fast and accurate entry of sales, orders, and training information.
- Provide accessible records for farmers, sales, purchases, transport, and training data.
- Generate and present key reports that allow managers to make informed business decisions.

## System Design
The design includes:
- **System Flowchart**: An end-to-end flow of the processes within the system, from data entry to report generation.
- **Database Structure**: Tables for Farmers, Sales, Purchases, Transport, and Trainees, each with relevant fields for efficient data storage and retrieval.
- **Form Designs**:
   - **Farmer’s Registration Form**
   - **Orders Form**
   - **Purchase Form**
   - **Transport Form**
   - **Trainee Registration Form**
- **Report Templates**: Structured templates for each report type to standardize output across various functions.

### Database Relationships
Tables are linked by identifiers like Farmer ID and Sales ID, creating a relational database that supports accurate and consistent data management.

## System Implementation
Developed in **Microsoft Access**, the NektaMS involves:
- **Tables**: Created for each category, such as Farmers, Products, Purchases, Sales, and Transport.
- **Forms and Queries**: Forms simplify data entry, while queries enable quick data processing and report generation.
- **Security**: Password-protected access to prevent unauthorized entry.

## User Guide
### Loading and Logging In
1. Open the system from the Start Menu by selecting **NektaMS**.
2. Enter the username and password on the login screen.
3. Navigate through the main menu options for data entry, report generation, and other functions.

### Data Entry Procedure
- **Farmer Registration**: Enter farmer details via the **Farmer Registration Form**.
- **Order Processing**: Use the **Orders Form** to record new orders.
- **Purchase Entry**: Log purchases using the **Purchase Form**.
- **Transport and Training**: Track transport needs and register trainees through respective forms.

### Report Generation
Reports for Farmers, Sales, Purchases, Transport, and Training can be accessed from the main menu, summarizing key data for management review.

## Installation Requirements
- **Hardware**: Central Server, Workstations, Laser Printer, Thermal Printers.
- **Software**: Windows OS (10 or later), Microsoft Office (2016 or later), Antivirus.

## Troubleshooting
Common issues and solutions:
- **Incorrect ID Number Format**: Ensure full 8-digit ID is entered.
- **Email Format Error**: Use `@` and a domain, e.g., `example@domain.com`.
- **Invalid Login**: Check username and password, or consult the administrator if login fails.

## License
Licensed under the MIT License. See LICENSE file for details.

---
