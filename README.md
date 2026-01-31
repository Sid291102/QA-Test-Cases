# QA-Test-Cases
1️⃣ Project Overview
This project focuses on manual testing of an e-commerce web application.
The objective is to validate application functionality by preparing test cases and identifying bugs based on real user scenarios.

# Amazon Quality Assurance: Test Cases & Bug Reports

This repository contains comprehensive Quality Assurance documentation for the Amazon platform, focusing on end-to-end functional testing, performance evaluation, and defect tracking.

## 📁 Repository Structure

- `Amazon Testcase.xlsx`: Contains detailed test scenarios, procedures, and expected vs. actual results.
- `Sample Bug Report.xlsx`: A log of identified defects with severity, reproducibility, and environment details.

## 🛠️ Test Case Overview

The test suite covers several critical modules with a focus on both **Functional** and **Non-Functional** requirements.

### Key Modules
- **Checkout & Payments:** Validation of COD, UPI, and Card transactions.
- **Prime Membership:** Testing access control for Prime Video and Prime-eligible shipping.
- **Amazon Travel:** End-to-end testing of Flight, Bus, and Train booking engines.
- **Gift Cards:** Functional validation of card redemption, balance tracking, and personalization.

### Testing Methodologies
- **Positive Testing:** Successful path validation.
- **Negative Testing:** Error handling and unauthorized access checks.
- **Accessibility (A11y):** Keyboard navigation and screen-reader compatibility.
- **Equivalence Partitioning:** Testing product variants (size/color) to optimize test coverage.

## 🐞 Bug Report Summary

Defects were tracked using a standardized template to ensure clear communication between QA and Dev teams.

### Bug Classification
- **Critical/High Severity:** Homepage 503 errors, Search filter failures, Payment Gateway timeouts.
- **Medium Severity:** Slow page loads (Performance), Missing alt-text (Accessibility).
- **Low Severity:** UI alignment issues in mobile navigation, irrelevance in recommendation carousels.

### Tech Stack / Configuration
- **Browsers:** Chrome 143.0, Safari.
- **OS:** MacOS Catalina, iOS/Android (Mobile App).
- **Network:** Wi-Fi (50 Mbps), 4G/LTE.

## 🚀 How to Use These Files
1. **Analyze Coverage:** Use the "Module" column in the Test Case file to see which areas of the application are protected.
2. **Review Defect Trends:** Check the "Issue Type" in the Bug Report to identify recurring performance or functional bottlenecks.
3. **Execution Status:** Refer to the "Execution Status" column in the test cases to see current project progress.

---
**Tools Used:** Excel, Manual Testing.
