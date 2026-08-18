# 🧪 Manual Testing Project — Demo Web Shop

<p align="center">
  <img src="https://img.shields.io/badge/Testing-Manual%20Testing-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Project-Demo%20Web%20Shop-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Documentation-FRS%20%7C%20Test%20Plan%20%7C%20RTM-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Defect%20Tracking-Bug%20Reporting-red?style=for-the-badge" />
</p>

<p align="center">
  <b>End-to-End Manual Software Testing Project</b>
</p>

<p align="center">
  Requirement Analysis → Test Planning → Test Design → Test Execution → Defect Reporting → Regression → Test Sign-off
</p>

---

## 📌 Project Overview

This repository contains an **end-to-end Manual Testing project** performed on the **Demo Web Shop** application.

The project demonstrates the complete Software Testing Life Cycle (STLC), starting from understanding requirements and exploring the application to designing test scenarios, writing detailed test cases, executing tests, reporting defects, performing re-testing and regression testing, and completing the final test sign-off.

### 🌐 Application Under Test

**Demo Web Shop**

🔗 https://demowebshop.tricentis.com/

The Demo Web Shop is an e-commerce web application used for practicing functional and non-functional software testing concepts.

---

# 🎯 Project Objectives

The main objectives of this project are:

* Understand the application's business requirements and functionality.
* Analyze the Functional Requirement Specification (FRS).
* Identify test scenarios from requirements.
* Design comprehensive test cases.
* Prepare a Test Plan.
* Create a Requirement Traceability Matrix (RTM).
* Execute test cases against the application.
* Identify, document, and track defects.
* Perform Sanity Testing.
* Perform Re-testing of fixed defects.
* Perform Regression Testing.
* Validate application functionality from an end-user perspective.
* Complete the testing process with Test Sign-off.

---

# 🏗️ Testing Process

```text
                    ┌─────────────────────┐
                    │   Requirement       │
                    │      Analysis       │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │    Test Planning    │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │    Test Design      │
                    │ Scenarios & Cases   │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │   Test Execution    │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Defect Reporting &  │
                    │      Tracking       │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │ Re-testing &        │
                    │ Regression Testing  │
                    └──────────┬──────────┘
                               ↓
                    ┌─────────────────────┐
                    │    Test Sign-off    │
                    └─────────────────────┘
```

---

# 📚 Manual Testing Concepts Covered

## 📅 Day 1 — Software Testing Fundamentals

* What is Software?
* Types of Software
* What is Software Testing?
* What is Software Quality?
* Project vs Product
* Why do we need Software Testing?
* Error, Bug & Failure
* Why Software Has Bugs

---

## 📅 Day 2 — SDLC & Testing Fundamentals

* Software Development Life Cycle (SDLC)
* Waterfall Model
* Spiral Model
* V-Model
* Static Testing
* Dynamic Testing
* Verification
* Validation
* White Box Testing
* Black Box Testing

---

## 📅 Day 3 — Testing Levels & Quality

* Static Testing
* Dynamic Testing
* Review
* Walkthrough
* Inspection
* QA — Quality Assurance
* QC — Quality Control
* QE — Quality Engineering
* Levels of Software Testing
* Unit Testing
* Integration Testing
* System Testing
* User Acceptance Testing (UAT)

---

# 📅 Day 4 — Functional & Non-Functional Testing

### Functional Testing

* System Testing
* GUI Testing
* GUI Checklist
* Usability Testing
* Functional Testing
* Object Properties Testing
* Database Testing
* Error Handling Testing
* Calculation & Manipulation Testing
* Link Existence Testing
* Link Execution Testing
* Cookies & Sessions Testing

### Non-Functional Testing

* Performance Testing
* Security Testing
* Recovery Testing
* Compatibility Testing
* Installation Testing
* Sanitation / Garbage Testing
* Functional vs Non-Functional Testing

---

# 📅 Day 5 — Testing Types

* Regression Testing
* Re-testing
* Regression vs Re-testing
* Smoke Testing
* Sanity Testing
* Exploratory Testing
* Ad-hoc Testing
* Monkey Testing
* Exploratory vs Ad-hoc vs Monkey Testing
* Positive Testing
* Negative Testing
* Positive vs Negative Test Cases
* End-to-End Testing
* Localization Testing
* Globalization / Internationalization Testing

---

# 📅 Day 6 — Test Case Design Techniques

Black-box test design techniques covered:

### 1. Equivalence Class Partitioning

Dividing input data into valid and invalid groups to reduce the number of test cases while maintaining effective coverage.

### 2. Boundary Value Analysis

Testing values at and around the boundaries of valid input ranges.

### 3. Decision Table Testing

Testing combinations of conditions and corresponding business rules/actions.

### 4. State Transition Testing

Validating system behavior when moving from one state to another based on events or conditions.

### 5. Error Guessing

Designing test cases based on tester experience and common areas where defects are likely to occur.

---

# 📅 Day 7 — STLC

The project follows the major activities of the **Software Testing Life Cycle (STLC)**:

```text
Requirement Analysis
        ↓
Test Planning
        ↓
Test Design / Development
        ↓
Test Environment Setup
        ↓
Test Execution
        ↓
Defect Reporting & Tracking
        ↓
Re-testing
        ↓
Regression Testing
        ↓
Test Closure
```

---

# 📅 Day 8 — Test Documentation

## 📄 Test Plan

The Test Plan defines:

* Testing objectives
* Scope
* Testing approach
* Testing types
* Resources
* Environment
* Schedule
* Entry criteria
* Exit criteria
* Risks and assumptions

## 📝 Use Case vs Test Scenario vs Test Case

| Document          | Purpose                                                |
| ----------------- | ------------------------------------------------------ |
| **Use Case**      | Describes how a user interacts with the system         |
| **Test Scenario** | High-level functionality or condition to be tested     |
| **Test Case**     | Detailed steps used to verify a specific functionality |

## 🔗 RTM — Requirement Traceability Matrix

RTM is used to map:

```text
Requirement
     ↓
Test Scenario
     ↓
Test Case
     ↓
Execution Result
     ↓
Defect
```

This helps ensure that every requirement is covered by appropriate test cases.

---

# 🐞 Defect Management

The project also covers the complete defect management process.

### Defect Report Contents

A defect report may contain:

* Defect ID
* Defect Title
* Module
* Description
* Preconditions
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Environment
* Screenshot / Evidence
* Reported By
* Assigned To
* Status

### Severity

Severity represents the **impact of the defect on the application**.

Examples:

* Critical
* High
* Medium
* Low

### Priority

Priority represents **how urgently the defect should be fixed**.

Examples:

* P0 — Critical
* P1 — High
* P2 — Medium
* P3 — Low

---

# 🔄 Defect Life Cycle

```text
New
 ↓
Assigned
 ↓
Open
 ↓
Fixed
 ↓
Retest
 ↓
Verified
 ↓
Closed
```

Possible alternate flows:

```text
Fixed → Reopened → Assigned → Fixed
```

Other statuses may include:

* Duplicate
* Rejected
* Deferred
* Not a Bug
* Cannot Reproduce

---

# 🧪 Testing Types Used in the Project

| Testing Type              | Purpose                                                       |
| ------------------------- | ------------------------------------------------------------- |
| **Smoke Testing**         | Verify that the major application functions are working       |
| **Sanity Testing**        | Verify specific functionality after a change/fix              |
| **Functional Testing**    | Verify application functionality against requirements         |
| **Regression Testing**    | Ensure existing functionality is not broken by changes        |
| **Re-testing**            | Verify that a previously reported defect has been fixed       |
| **Positive Testing**      | Validate the application using valid inputs                   |
| **Negative Testing**      | Validate application behavior using invalid/unexpected inputs |
| **End-to-End Testing**    | Validate complete business workflows                          |
| **Exploratory Testing**   | Simultaneous learning, test design and execution              |
| **Usability Testing**     | Evaluate ease of use and user experience                      |
| **Compatibility Testing** | Verify behavior across browsers/devices/environments          |

---

# 🛒 Demo Web Shop — Functional Areas

The application was explored from an end-user perspective across major e-commerce workflows such as:

* 🏠 Home Page
* 👤 User Registration
* 🔐 Login / Logout
* 🔑 Account Management
* 📚 Product Categories
* 🔎 Product Search
* 📦 Product Details
* 🛒 Shopping Cart
* ❤️ Wishlist
* 💳 Checkout
* 📍 Address Information
* 🚚 Order Processing
* 📜 Order History
* 🔗 Navigation & Links
* ⚠️ Validation & Error Messages

---

# 📊 Project Deliverables

The repository contains / is intended to contain the following testing artifacts:

```text
📁 Manual-Testing-Project
│
├── 📄 FRS
│
├── 📄 Test Plan
│
├── 📊 Test Scenarios
│
├── 📝 Test Cases
│
├── 🔗 RTM
│
├── 🐞 Defect Reports
│
├── 📊 Test Execution Report
│
├── 🔄 Regression Testing
│
├── 🔁 Re-testing
│
└── ✅ Test Sign-off
```

---

# 🔍 Example Test Scenario

### Scenario: Verify User Login

Possible test cases include:

| TC ID        | Test Case                               |
| ------------ | --------------------------------------- |
| TC_LOGIN_001 | Login using valid username and password |
| TC_LOGIN_002 | Login using invalid username            |
| TC_LOGIN_003 | Login using invalid password            |
| TC_LOGIN_004 | Login with blank username               |
| TC_LOGIN_005 | Login with blank password               |
| TC_LOGIN_006 | Login with both fields blank            |
| TC_LOGIN_007 | Verify password masking                 |
| TC_LOGIN_008 | Verify login error message              |
| TC_LOGIN_009 | Verify successful logout                |
| TC_LOGIN_010 | Verify session behavior after logout    |

---

# 🧠 Key Testing Principles Learned

The project helped apply important software testing principles:

1. **Testing shows the presence of defects, not their absence.**
2. **Exhaustive testing is impossible.**
3. **Early testing saves time and cost.**
4. **Defects tend to cluster.**
5. **Pesticide paradox — repeating the same tests may stop finding new defects.**
6. **Testing is context dependent.**
7. **Absence-of-errors is a fallacy.**

---

# 🛠️ Tools & Technologies

<p align="center">

<img src="https://img.shields.io/badge/Manual%20Testing-0078D4?style=for-the-badge" />
<img src="https://img.shields.io/badge/MS%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" />

</p>

### Tools Used

* Manual Testing
* Microsoft Excel
* Web Browser / Chrome
* Git
* GitHub
* Test Documentation
* Defect Tracking

---

# 📈 Skills Demonstrated

Through this project, I demonstrated practical knowledge of:

* Software Testing Fundamentals
* SDLC & STLC
* Requirement Analysis
* FRS Analysis
* Test Planning
* Test Scenario Design
* Test Case Design
* Black Box Testing
* Functional Testing
* Non-Functional Testing
* GUI Testing
* Database Testing Concepts
* Test Data Design
* Boundary Value Analysis
* Equivalence Partitioning
* Decision Table Testing
* State Transition Testing
* Error Guessing
* RTM Preparation
* Test Execution
* Defect Reporting
* Severity & Priority Classification
* Defect Life Cycle
* Smoke Testing
* Sanity Testing
* Re-testing
* Regression Testing
* Test Closure

---

# 📋 End-to-End Project Workflow

```text
        REQUIREMENTS
             │
             ▼
        FRS ANALYSIS
             │
             ▼
        TEST PLANNING
             │
             ▼
      TEST SCENARIO DESIGN
             │
             ▼
        TEST CASE DESIGN
             │
             ▼
           RTM
             │
             ▼
     ENVIRONMENT SETUP
             │
             ▼
       TEST EXECUTION
             │
        ┌────┴────┐
        ▼         ▼
      PASS      FAIL
                  │
                  ▼
          DEFECT REPORTING
                  │
                  ▼
             DEFECT FIX
                  │
                  ▼
              RE-TEST
                  │
                  ▼
           REGRESSION TEST
                  │
                  ▼
             TEST CLOSURE
                  │
                  ▼
             TEST SIGN-OFF
```

---

# 🎓 Learning Outcome

This project provided hands-on experience in performing **manual software testing from requirement analysis through test sign-off**.

The focus was not only on writing test cases but also on understanding how a professional QA process works across the complete testing lifecycle.

---

# 📂 Repository Structure

```text
Manual-Testing-Project/
│
├── README.md
│
├── FRS/
│   └── Functional_Requirement_Specification
│
├── Test-Plan/
│   └── Test_Plan
│
├── Test-Scenarios/
│   └── Test_Scenarios
│
├── Test-Cases/
│   └── Test_Cases
│
├── RTM/
│   └── Requirement_Traceability_Matrix
│
├── Defects/
│   └── Defect_Reports
│
├── Test-Execution/
│   └── Test_Execution_Report
│
└── Test-Signoff/
    └── Test_Signoff
```

---

# 🔗 Application Under Test

<p align="center">

### 🛍️ Demo Web Shop

<a href="https://demowebshop.tricentis.com/">
  <img src="https://img.shields.io/badge/Visit%20Demo%20Web%20Shop-Visit%20Application-success?style=for-the-badge" />
</a>

</p>

---

# 👨‍💻 Author

## Mahadevu M P

**Software Engineer | Data & QA Enthusiast**

📧 Email: **[mahadevump657@gmail.com](mailto:mahadevump657@gmail.com)**

💼 LinkedIn: **[Mahadevu M P](https://www.linkedin.com/in/mahadevu-m-p-58b51426/)**

🐙 GitHub: **[Devputta](https://github.com/Devputta)**

---

# ⭐ If You Find This Project Useful

If this repository helps you understand **Manual Testing, STLC, Test Case Design, RTM, Defect Management, or QA processes**, consider giving it a ⭐ star.

---

<p align="center">

### 🧪 Test. Find. Fix. Verify. Deliver. 🚀

**Manual Testing Project | Demo Web Shop | End-to-End QA Process**

</p>
