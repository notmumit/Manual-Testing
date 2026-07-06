# Manual Testing

## Overview

This repository contains my **Manual Testing Project** based on the **DMoney Portal** application. The assignment covers the complete Software Testing Life Cycle (STLC) activities for the Customer Transaction module, including test planning, test case design, execution, bug reporting, exploratory testing, and documentation.

---

## Project Information

| Item              | Details               |
| ----------------- | --------------------- |
| **Project**       | DMoney Portal         |
| **Module Tested** | Customer Transactions |
| **Testing Type**  | Manual Testing        |



# Repository Contents

This repository includes the following deliverables:

* ✅ Test Estimation
* ✅ Acceptance Criteria
* ✅ Test Data
* ✅ Test Cases (Positive & Negative)
* ✅ Test Execution Report
* ✅ Test Completion Report
* ✅ Exploratory Testing Report
* ✅ Bug Report
* ✅ System Checklist

--

# Modules Covered

### User Registration & Authentication

* Self Registration
* Admin User Creation
* User Activation
* Login
* OTP Verification
* JWT Authentication

### Customer Transaction

* Send Money
* Bank Cash-In via Stripe
* Payment to Merchant

---

# Testing Artifacts

| Document               | Status      |
| ---------------------- | ----------- |
| Test Estimation        | ✔ Completed |
| Acceptance Criteria    | ✔ Completed |
| Test Data              | ✔ Completed |
| Test Cases             | ✔ Completed |
| Test Execution Report  | ✔ Completed |
| Test Completion Report | ✔ Completed |
| Exploratory Testing    | ✔ Completed |
| Bug Report             | ✔ Completed |
| Checklist              | ✔ Completed |

---

# Test Scenarios Covered

## Send Money

* Valid transfer
* Invalid receiver
* Insufficient balance
* Daily limit exceeded
* Monthly limit exceeded
* Transaction count exceeded
* Service fee validation
* Customer-only restriction

## Bank Cash-In (Stripe)

* Successful deposit
* Minimum amount validation
* Maximum amount validation
* Wallet limit validation
* Duplicate PaymentIntent validation
* Invalid card information
* Stripe payment failure

## Payment to Merchant

* Successful payment
* Invalid merchant
* Insufficient balance
* Service fee validation
* Daily transaction limit
* Monthly transaction limit

---

# Testing Techniques Used

* Functional Testing
* Positive Testing
* Negative Testing
* Boundary Value Analysis (BVA)
* Equivalence Partitioning (EP)
* Exploratory Testing
* Acceptance Testing

---

# Defects Identified

Potential defects discovered during exploratory testing are documented in the Bug Report section, including:

* Functional Bugs
* Validation Issues
* UI Issues
* Business Logic Issues
* Error Message Validation

---

# Tools Used

* Microsoft Excel / Google Sheets
* GitHub
* Stripe Test Environment

---

# Repository Structure

```
DMoney-Manual-Testing/
│
├── Test Estimation
├── Acceptance Criteria
├── Test Data
├── Test Cases
├── Test Execution Report
├── Test Completion Report
├── Exploratory Testing
├── Bug Report
├── Checklist
└── README.md
```

---

# Learning Outcomes

Through this project, I practiced:

* Requirement Analysis
* Acceptance Criteria Writing
* Test Planning
* Test Case Design
* Test Execution
* Defect Reporting
* Exploratory Testing
* Software Testing Documentation
* GitHub Repository Management

---


This repository is created for educational purposes as part of an SQA Manual Testing assignment.
# Manual-Testing
