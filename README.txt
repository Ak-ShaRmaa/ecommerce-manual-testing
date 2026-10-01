E-Commerce Website – Manual QA Testing

Project Overview

This project documents manual testing of an e-commerce web application. The goal of the project is to practice and demonstrate a structured software testing process by identifying application features, creating test cases, executing them, recording actual results, and documenting failed test cases.

Application Under Test

Website: https://shop.qaautomationlabs.com/

Testing Scope

The manual testing covered different parts of the shopping application, including:

Login

Home page and navigation

Men, Women, Kids, and Electronics sections

Product filtering by price, size, and color

Product search

Add to Cart functionality

Cart-related functionality

Billing and checkout-related fields

Order-related functionality

UI/UX checks such as the Dark Mode button

Test Documentation

The project contains an Excel workbook used to document the manual testing activity.

The workbook currently contains 40 documented test cases with the following execution results:

Passed: 38

Failed: 2

The test cases record information such as:

Scenario ID

Scenario description

Test Case ID

Preconditions

Steps to execute

Expected result

Actual result

Status

Defects Identified

Two test cases were recorded as failed during the current test execution.

TC004 – Dark Mode Button

Expected: Clicking the Dark Mode button should change the webpage from light mode to dark mode.

Actual: The webpage did not change to dark mode after clicking the button.

Status: FAIL

TC037 – State/City Field Validation

Expected: Invalid input such as numeric-only data should be rejected or show an appropriate validation message.

Actual: The field accepted numeric input instead of showing an error.

Status: FAIL

Tools Used

Microsoft Excel – Test case documentation and test execution tracking

Web browser – Manual execution of test cases

Repository Structure

E-commerce-Manual-QA/
│
├── README.md
├── Test-Cases.xlsx
├── Screenshots/
│   ├── Login/
│   ├── Products/
│   ├── Cart/
│   ├── Checkout/
│   └── Bugs/
└── Bug-Reports/

Project Purpose

This project is part of my QA/software testing learning portfolio. It demonstrates my practical exposure to manual testing, test case preparation, test execution, identifying application issues, and documenting test results.