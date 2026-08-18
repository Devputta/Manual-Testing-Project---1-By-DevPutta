# 🧪 Manual Testing Project — End-to-End QA Portfolio

<p align="center">
  <img src="https://img.shields.io/badge/Manual%20Testing-End--to--End-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Functional%20Testing-Covered-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Test%20Cases-Excel-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Defect%20Reporting-Covered-red?style=for-the-badge" />
</p>

<p align="center">
  <b>Software Testing • Test Design • Test Execution • Defect Management • QA Documentation</b>
</p>

<p align="center">
  A practical end-to-end Manual Testing project demonstrating the complete Software Testing Life Cycle (STLC).
</p>

---

## 📌 About This Project

This repository contains my **Manual Software Testing practice and project work**, covering the complete testing process from **requirement analysis to test sign-off**.

The repository includes practical testing artifacts such as:

* Functional Requirement understanding
* Test Plans
* Test Scenarios
* Detailed Test Cases
* Requirement Traceability Matrix (RTM)
* Test Execution
* Bug / Defect Reports
* Smoke Testing
* Sanity Testing
* Re-testing
* Regression Testing
* Test Sign-off
* Test Case Design Techniques
* Reusable testing templates

The project primarily focuses on web-based e-commerce applications, including:

* 🛒 **Demo Web Shop**
* 🛍️ **OpenCart**

---

# 🌐 Applications Under Test

## 🛒 Demo Web Shop

**Application:** Demo Web Shop by Tricentis

🔗 https://demowebshop.tricentis.com/

The Demo Web Shop application was used to practice end-to-end functional testing, including requirement analysis, scenario identification, test case design, execution, and defect identification.

### Major Functional Areas

* User Registration
* Login / Logout
* User Account
* Product Categories
* Product Search
* Product Details
* Shopping Cart
* Wishlist
* Checkout
* Address Management
* Order Processing
* Order History
* Navigation
* Validation Messages
* Error Handling

---

## 🛍️ OpenCart

OpenCart was used for additional practical testing activities involving:

* Test Scenario Design
* Test Case Design
* Test Execution
* Bug Reporting
* Defect Tracking
* Result Documentation

---

# 🎯 Project Objectives

The main objectives of this project are to:

* Understand software testing fundamentals.
* Understand SDLC and STLC.
* Analyze application requirements.
* Explore the Application Under Test (AUT).
* Identify test scenarios.
* Write detailed test cases.
* Apply Black Box Test Design Techniques.
* Prepare a Test Plan.
* Create an RTM.
* Execute test cases.
* Identify and report defects.
* Classify defects using Severity and Priority.
* Perform Smoke Testing.
* Perform Sanity Testing.
* Perform Re-testing.
* Perform Regression Testing.
* Document test results.
* Understand the complete testing life cycle.
* Perform Test Closure and Test Sign-off.

---

# 🔄 Software Testing Life Cycle

The project follows the major phases of the **Software Testing Life Cycle (STLC)**:

```text
┌──────────────────────────────┐
│     Requirement Analysis     │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│       Test Planning          │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│   Test Design / Development  │
│  Scenarios + Test Cases      │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│    Test Environment Setup    │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│       Test Execution         │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│   Defect Reporting & Tracking│
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│   Re-testing & Regression    │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│       Test Closure           │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│       Test Sign-off          │
└──────────────────────────────┘
```

---

# 📚 Manual Testing Concepts Covered

## 📅 Day 1 — Software Testing Fundamentals

### Topics

* What is Software?
* Types of Software
* What is Software Testing?
* What is Software Quality?
* Project vs Product
* Why do we need Software Testing?
* Error, Bug & Failure
* Why Software Has Bugs

---

## 📅 Day 2 — SDLC & Testing Methods

### Topics

* Software Development Life Cycle — SDLC
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

### Topics

* Static Testing
* Dynamic Testing
* Review
* Walkthrough
* Inspection
* Quality Assurance — QA
* Quality Control — QC
* Quality Engineering — QE
* Levels of Software Testing
* Unit Testing
* Integration Testing
* System Testing
* User Acceptance Testing — UAT

---

# 📅 Day 4 — Functional & Non-Functional Testing

## Functional Testing

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

## Non-Functional Testing

* Performance Testing
* Security Testing
* Recovery Testing
* Compatibility Testing
* Installation Testing
* Sanitation / Garbage Testing
* Functional vs Non-Functional Testing

---

# 📅 Day 5 — Testing Types

### Topics

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

## 1️⃣ Equivalence Class Partitioning

Dividing input data into valid and invalid classes to reduce redundant test cases while maintaining effective test coverage.

## 2️⃣ Boundary Value Analysis

Testing values at the boundaries and immediately around the boundaries of input conditions.

Example:

```text
Valid Range: 18 – 60

Test Values:
17 → Invalid
18 → Valid Boundary
19 → Valid
59 → Valid
60 → Valid Boundary
61 → Invalid
```

## 3️⃣ Decision Table Testing

Used to test combinations of conditions and their corresponding actions.

## 4️⃣ State Transition Testing

Used to validate system behavior when the application moves from one state to another based on events or conditions.

## 5️⃣ Error Guessing

Creating test cases based on tester experience and common areas where defects are likely to occur.

---

# 📅 Day 7 — Testing Activities

The project covers the following testing activities:

1. Test Planning
2. Test Design / Development
3. Test Execution
4. Defect Reporting
5. Defect Tracking
6. Re-testing
7. Regression Testing
8. Test Closure

---

# 📅 Day 8 — Test Documentation

## 📄 Test Plan

A Test Plan defines:

* Test Objectives
* Scope
* Testing Approach
* Testing Types
* Resources
* Test Environment
* Schedule
* Entry Criteria
* Exit Criteria
* Risks
* Assumptions

---

## 📝 Use Case vs Test Scenario vs Test Case

| Document          | Description                                            |
| ----------------- | ------------------------------------------------------ |
| **Use Case**      | Describes how a user interacts with the system         |
| **Test Scenario** | High-level functionality or condition to be tested     |
| **Test Case**     | Detailed steps used to verify a specific functionality |

---

# 🔗 Requirement Traceability Matrix — RTM

RTM is used to ensure that requirements are mapped to appropriate testing activities.

```text
Requirement
     ↓
Test Scenario
     ↓
Test Case
     ↓
Test Execution
     ↓
Test Result
     ↓
Defect
```

RTM helps ensure:

* Requirement coverage
* Test coverage
* Traceability
* Identification of missing test cases
* Better test management

---

# 🐞 Defect / Bug Management

The project covers the complete defect management process.

## Defect Report Contents

A defect report can include:

* Defect ID
* Defect Title
* Module
* Description
* Preconditions
* Steps to Reproduce
* Test Data
* Expected Result
* Actual Result
* Severity
* Priority
* Environment
* Screenshot / Evidence
* Reported By
* Assigned To
* Status

---

# 🚦 Severity vs Priority

| Severity     | Meaning                                            |
| ------------ | -------------------------------------------------- |
| **Critical** | Application or major functionality is unusable     |
| **High**     | Major functionality is significantly affected      |
| **Medium**   | Functionality is affected but workaround may exist |
| **Low**      | Minor issue with limited impact                    |

| Priority | Meaning                      |
| -------- | ---------------------------- |
| **P0**   | Immediate attention required |
| **P1**   | High priority                |
| **P2**   | Medium priority              |
| **P3**   | Low priority                 |

### Example

A spelling mistake on the homepage may have:

```text
Severity: Low
Priority: Medium
```

A payment failure may have:

```text
Severity: Critical
Priority: High
```

---

# 🔁 Defect Life Cycle

```text
       ┌───────┐
       │  New  │
       └───┬───┘
           ↓
      ┌──────────┐
      │ Assigned │
      └────┬─────┘
           ↓
       ┌──────┐
       │ Open │
       └───┬──┘
           ↓
       ┌───────┐
       │ Fixed │
       └───┬───┘
           ↓
      ┌────────┐
      │ Retest │
      └───┬────┘
          ↓
      ┌──────────┐
      │ Verified │
      └────┬─────┘
           ↓
      ┌────────┐
      │ Closed │
      └────────┘
```

Possible alternate flow:

```text
Fixed → Retest → Reopened → Assigned → Fixed
```

Other defect statuses may include:

* Duplicate
* Rejected
* Deferred
* Cannot Reproduce
* Not a Bug

---

# 🧪 Smoke, Sanity, Re-testing & Regression

| Testing                | Purpose                                                                          |
| ---------------------- | -------------------------------------------------------------------------------- |
| **Smoke Testing**      | Checks whether the build is stable enough for detailed testing                   |
| **Sanity Testing**     | Checks specific functionality after a minor change/fix                           |
| **Re-testing**         | Verifies that a previously failed test case now passes after the defect is fixed |
| **Regression Testing** | Ensures existing functionality has not been broken by changes                    |

### Testing Flow

```text
Build Received
      ↓
Smoke Testing
      ↓
Detailed Testing
      ↓
Defect Found
      ↓
Bug Fixed
      ↓
Re-testing
      ↓
Regression Testing
      ↓
Final Test Results
      ↓
Test Sign-off
```

---

# 📊 Project Artifacts

This repository contains practical testing documents and Excel-based testing artifacts.

## 🛒 Demo Web Shop Artifacts

### 📊 20 Test Scenarios + Detailed Test Cases

Contains **20 testing scenarios**, with multiple detailed test cases under each scenario.

➡️ [Open Demo Web Shop Test Scenarios & Test Cases](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/Demo_Web_Shop_20_Scenarios_5_to_20_Test_Cases%20%281%29.xlsx)

---

## 📋 Reusable Test Templates

### 📝 Test Scenario Template

A reusable template for documenting high-level testing scenarios.

➡️ [Open Test Scenario Template](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/Test_Scenario_Template.xlsx)

### 🧪 Test Case Template

A reusable template for writing structured test cases.

➡️ [Open Test Case Template](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/Test_Case_Template.xlsx)

### 🐞 Bug Report Template

A reusable template for documenting software defects.

➡️ [Open Bug Report Template](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/Bug_Report_Template.xlsx)

---

# 🛍️ OpenCart Testing Artifacts

The repository also contains a separate set of practical testing documents for an OpenCart e-commerce application.

## 📋 OpenCart Test Scenarios

Contains identified high-level test scenarios for OpenCart.

➡️ [Open OpenCart Test Scenarios](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/OpenCart-Test%20Scenarios.xlsx)

---

## 🧪 OpenCart Test Cases

Contains detailed test cases designed from the identified scenarios.

➡️ [Open OpenCart Test Cases](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/OpenCart-TestCases.xlsx)

---

## ▶️ OpenCart Test Execution Results

Contains test execution results showing the outcome of executed test cases.

➡️ [Open OpenCart Test Execution Results](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/OpenCart-TestExecution%20Results.xlsx)

---

## 🐞 OpenCart Bug Reports

Contains documented defects identified during testing.

➡️ [Open OpenCart Bug Reports](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/OpenCart%20-%20Bug%20Report.xlsx)

---

# 📚 Manual Testing Learning Notes

The repository also contains learning/reference material covering Manual Testing concepts.

### 📘 Manual Testing Introduction

➡️ [View Manual Testing Introduction](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/Manual%20Testing%20Intro.txt)

### 📘 Live Project Manual Testing Notes

➡️ [View Live Project Manual Testing Notes](https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta/blob/main/LIVE%20PROJECT%20%28MANUAL%20TESTING%29.txt)

---

# 🗂️ Repository Contents

```text
Manual-Testing-Project---1-By-DevPutta
│
├── 📄 README.md
│
├── 📊 Demo_Web_Shop_20_Scenarios_5_to_20_Test_Cases (1).xlsx
│
├── 🐞 Bug_Report_Template.xlsx
│
├── 🧪 Test_Case_Template.xlsx
│
├── 📋 Test_Scenario_Template.xlsx
│
├── 🛒 OpenCart-Test Scenarios.xlsx
│
├── 🧪 OpenCart-TestCases.xlsx
│
├── ▶️ OpenCart-TestExecution Results.xlsx
│
├── 🐞 OpenCart - Bug Report.xlsx
│
├── 📘 Manual Testing Intro.txt
│
└── 📘 LIVE PROJECT (MANUAL TESTING).txt
```

---

# 🧪 Example Test Case

### Test Case: Login with Valid Credentials

| Field               | Details                                       |
| ------------------- | --------------------------------------------- |
| **Test Case ID**    | TC_LOGIN_001                                  |
| **Module**          | Login                                         |
| **Test Scenario**   | Verify login using valid credentials          |
| **Precondition**    | User must have a registered account           |
| **Test Data**       | Valid username and password                   |
| **Steps**           | Enter username → Enter password → Click Login |
| **Expected Result** | User should successfully log in               |
| **Actual Result**   | As observed during execution                  |
| **Status**          | Pass / Fail                                   |

---

# ❌ Example Negative Test Cases

Negative testing was used to validate application behavior with invalid or unexpected inputs.

Examples:

* Login with invalid username
* Login with invalid password
* Login with blank username
* Login with blank password
* Submit forms with mandatory fields empty
* Enter invalid email format
* Enter invalid numeric values
* Enter special characters
* Use invalid search input
* Attempt invalid navigation

---

# 🔍 Example Test Scenario

### Scenario: Verify Shopping Cart

Possible test cases:

```text
TC_CART_001 → Add product to cart
TC_CART_002 → Add multiple products
TC_CART_003 → Update product quantity
TC_CART_004 → Remove product from cart
TC_CART_005 → Verify cart total
TC_CART_006 → Verify product price
TC_CART_007 → Verify empty cart
TC_CART_008 → Continue shopping
TC_CART_009 → Proceed to checkout
TC_CART_010 → Verify cart persistence
```

---

# 📈 Test Metrics

The project also covers common software testing metrics such as:

* Total Test Cases
* Executed Test Cases
* Passed Test Cases
* Failed Test Cases
* Blocked Test Cases
* Not Executed
* Defect Count
* Defect Density
* Pass Percentage
* Fail Percentage
* Test Coverage
* Requirement Coverage

### Example

```text
Pass Percentage =

Passed Test Cases
----------------------- × 100
Executed Test Cases
```

---

# 🧠 Software Testing Principles

The following fundamental testing principles were studied:

### 1. Testing Shows Presence of Defects

Testing can demonstrate that defects exist, but cannot prove that software is completely defect-free.

### 2. Exhaustive Testing is Impossible

Testing every possible combination of inputs and conditions is generally impractical.

### 3. Early Testing

Testing activities should begin as early as possible in the development life cycle.

### 4. Defect Clustering

A small number of modules often contain a large number of defects.

### 5. Pesticide Paradox

Repeatedly executing the same test cases may eventually stop finding new defects.

### 6. Testing is Context Dependent

Testing approaches depend on the application, business domain, risks and requirements.

### 7. Absence-of-Errors Fallacy

Finding and fixing defects does not automatically mean that the product meets user needs or business requirements.

---

# 🛠️ Tools & Technologies

<p align="center">

<img src="https://img.shields.io/badge/Manual%20Testing-0078D4?style=for-the-badge" />

<img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />

<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />

<img src="https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" />

</p>

### Tools Used

* Manual Testing
* Microsoft Excel
* Google Chrome
* Git
* GitHub
* Test Documentation
* Defect Reporting
* Test Execution

---

# 💼 Skills Demonstrated

Through this project, I developed practical experience in:

### Testing

* Manual Testing
* Functional Testing
* Non-Functional Testing
* System Testing
* GUI Testing
* Usability Testing
* End-to-End Testing
* Smoke Testing
* Sanity Testing
* Re-testing
* Regression Testing
* Exploratory Testing
* Ad-hoc Testing
* Positive Testing
* Negative Testing

### Test Design

* Equivalence Class Partitioning
* Boundary Value Analysis
* Decision Table Testing
* State Transition Testing
* Error Guessing

### QA Process

* Requirement Analysis
* Test Planning
* Test Scenario Design
* Test Case Design
* Test Execution
* Defect Reporting
* Defect Tracking
* Severity & Priority
* RTM
* Test Closure
* Test Sign-off

---

# 📌 Project Highlights

| Area                       | Details                                    |
| -------------------------- | ------------------------------------------ |
| 🧪 Testing Type            | Manual Testing                             |
| 🌐 Application             | Demo Web Shop                              |
| 🛍️ Additional Application | OpenCart                                   |
| 📋 Test Documentation      | Test Scenarios, Test Cases, RTM, Test Plan |
| 🐞 Defect Management       | Bug Reporting & Tracking                   |
| 🔄 Retesting               | Covered                                    |
| ♻️ Regression              | Covered                                    |
| 🚦 Smoke Testing           | Covered                                    |
| 🧪 Sanity Testing          | Covered                                    |
| 📊 Test Execution          | Covered                                    |
| 📁 Artifacts               | Excel & Text Documentation                 |
| 🎯 Approach                | End-to-End STLC                            |

---

# 🎓 Learning Outcome

This project provided hands-on understanding of how a QA/Manual Tester works through the complete testing lifecycle.

I gained practical experience in:

```text
Requirements
     ↓
Analysis
     ↓
Planning
     ↓
Scenario Design
     ↓
Test Case Design
     ↓
RTM
     ↓
Execution
     ↓
Defect Reporting
     ↓
Re-testing
     ↓
Regression
     ↓
Test Closure
     ↓
Sign-off
```

The project helped bridge the gap between **Manual Testing theory and practical project execution**.

---

# 👨‍💻 Author

## Mahadevu M P

**Software Engineer | Manual Testing & Data Enthusiast**

<p align="center">

<a href="https://github.com/Devputta">
<img src="https://img.shields.io/badge/GitHub-Devputta-181717?style=for-the-badge&logo=github" />
</a>

<a href="https://www.linkedin.com/in/mahadevu-m-p-58b51426/">
<img src="https://img.shields.io/badge/LinkedIn-Mahadevu%20M%20P-0A66C2?style=for-the-badge&logo=linkedin" />
</a>

<a href="mailto:mahadevump657@gmail.com">
<img src="https://img.shields.io/badge/Email-mahadevump657%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</p>

---

# ⭐ Repository

🔗 **GitHub Repository**

https://github.com/Devputta/Manual-Testing-Project---1-By-DevPutta

If you find this project useful for learning Manual Testing, **feel free to ⭐ star the repository**.

---

<p align="center">

### 🧪 Test • Find • Report • Retest • Regression • Deliver 🚀

**End-to-End Manual Testing Project**

</p>
