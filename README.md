# OrangeHRM Manual Testing Project

## 📌 Project Overview

This project demonstrates manual QA testing of the OrangeHRM web application.

The objective was to validate key application modules using functional test cases, execute the tests, document defects, and analyze test coverage.

## 🧪 Modules Tested

- Login
- Dashboard
- Employee
- Leave

## 📊 Testing Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 20 |
| Executed | 20 |
| Passed | 19 |
| Failed | 1 |
| Pass Rate | 95% |
| Test Coverage | 100% |

## 📋 Test Artifacts

- Test Plan
- Test Scenarios
- Test Cases
- Test Execution Report
- Bug Log
- Risk Matrix
- Test Coverage Report
- Test Evidence / Screenshots

## 🐞 Defects

One defect was identified during testing:

**BUG-001:** Apply Leave page does not provide leave application fields when no leave balance is available.

The defect is documented in the Bug Log with reproduction steps, expected result, actual result, severity, priority, and evidence.

## 🛠️ Testing Approach

Testing was performed manually using:

- Functional testing
- Positive testing
- Negative testing
- UI validation
- Form validation
- Search functionality
- Basic defect reporting

## 🌐 Test Environment

**Application:** OrangeHRM Demo  
**Testing Type:** Manual Testing  
**Browser:** Web browser  
**Environment:** Demo environment

## 📁 Project Structure

```text
orangehrm-manual-testing/
│
├── README.md
│
├── Test_Plan/
│   └── Test_Plan.xlsx
│
├── Test_Scenarios/
│   └── Test_Scenarios.xlsx
│
├── Test_Cases/
│   └── Test_Cases.xlsx
│
├── Test_Execution/
│   └── Test_Execution.xlsx
│
├── Bug_Reports/
│   ├── Bug_Log.xlsx
│   ├── Risk_Matrix.xlsx
│   └── Test_Coverage.xlsx
│
└── Screenshots/
    └── Test evidence screenshots