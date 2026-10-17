# SauceDemo - Manual QA Testing Portfolio

## Project Overview

This project demonstrates manual software quality assurance testing on [SauceDemo](https://www.saucedemo.com/), a demonstration e-commerce web application.

The objective was to validate core application functionality, identify potential defects, and document test results with supporting evidence.

**Project Type:** Independent QA Portfolio Project  
**Testing Method:** Manual Functional & Exploratory Testing  
**Test Cases Executed:** 8  
**Test Cases Passed:** 8  
**Confirmed UI Defects:** 1  
**Additional Observations:** 1

## Testing Scope

- User authentication and invalid login handling
- Shopping cart functionality
- Checkout form validation
- Successful order completion
- Pricing and total calculation verification
- Product sorting functionality
- UI observation and defect reproduction

## Test Execution Summary

| Test ID | Test Scenario | Status |
|---|---|---|
| TC-001 | Valid Login | PASS |
| TC-002 | Invalid Login | PASS |
| TC-003 | Add Product to Cart | PASS |
| TC-004 | Remove Product from Cart | PASS |
| TC-005 | Checkout Form Validation | PASS |
| TC-006 | Successful Checkout | PASS |
| TC-007 | Pricing Calculation | PASS |
| TC-008 | Product Sorting | PASS |

## Confirmed Defect - BUG-001

**Title:** Login Error Message Overflows Its Container

**Category:** UI / Layout  
**Severity:** Low  
**Reproducibility:** 3/3 initial attempts, plus successful retest

**Environment:**
- Windows 10 Home
- Google Chrome 155.0.8059.39
- Browser Zoom: 100%
- Viewport: 1440 × 783

**Expected:** The login error message should remain readable within its notification container.

**Actual:** The error message overflows its container and appears clipped or overlapping surrounding elements.

The issue was reproducible at the tested viewport. The same overlap was not observed at a narrower 661 × 783 viewport.

## Additional Observation — OBS-001

The Sauce Labs Backpack product description includes the code-like phrase `carry.allTheThings()`.

This was documented as a content observation rather than a confirmed defect because the wording may be intentional.

## QA Report

The complete PDF report contains test results, screenshots, findings, and conclusions.

[View Complete QA Report](./SauceDemo_QA_Report_Final.pdf)

## Testing Limitations

This project was performed independently using a publicly available demonstration application. Testing was limited to selected scenarios and environments. It was not commissioned by or affiliated with Sauce Labs.

Passing test cases does not guarantee that the application is free from defects.

## Skills Demonstrated

Manual QA Testing · Functional Testing · Exploratory Testing · Test Case Documentation · Bug Reporting · Defect Reproduction · UI Testing · E-commerce Workflow Validation
