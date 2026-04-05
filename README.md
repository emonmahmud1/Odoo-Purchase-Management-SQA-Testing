# Odoo Purchase Management System - Manual Testing Project

## Project Overview
This repository contains a comprehensive manual functional testing project for the **Odoo Purchase Management System (v18.0)**. The goal of this project was to ensure the reliability and functional accuracy of the purchase workflow, from vendor creation to confirming purchase orders.

## Tools & Environment
- **ERP Platform:** Odoo v18.0 (Runbot)
- **Test Management:** Microsoft Excel (Test Cases)
- **Bug Tracking:** Jira
- **Testing Type:** Manual Functional Testing

## Project Structure
- `docs/`: Detailed testing strategy, scope, and environment setup (Test Plan)
- `test-cases/`: 30 detailed test cases covering:
  - User Authentication (Login)
  - Product & Vendor Management
  - Request for Quotation (RFQ)
  - Purchase Order (PO) Processing
- `bug-reports/`: Jira-exported issue logs including priority, status, and descriptions of identified defects
- `Mindmap/`: Mind map used to visualize test coverage
- `summary/`: Final testing summary and key findings

## Key Features Tested
- **Login Functionality:** Validation of credentials and error handling
- **Product & Vendor Module:** Creation, validation of mandatory fields, and duplicate checks
- **RFQ Workflow:** Adding products, auto-populating vendor data, and filtering
- **Purchase Order:** Converting RFQs to POs, generating PDF reports, and lock functionality

## Identified Bugs (Samples)
Some critical issues identified during testing include:
- System allows saving products with negative prices
- No duplicate warning for existing vendors
- Missing eye button in the password field for visibility toggle
- Improper email format validation in vendor creation

## Mind Mapping (Test Coverage)
To visualize the test scenarios and ensure maximum coverage, a mind map was created for the Odoo Purchase Module.

![Mind Map](Mindmap/Odoo%20Purchase%20Module%20Testing_Emon_mahmud.png)

## Tested By
**Emon Mahmud**
