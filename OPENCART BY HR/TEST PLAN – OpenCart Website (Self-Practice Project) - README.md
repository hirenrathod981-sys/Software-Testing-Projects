TEST PLAN – OpenCart Website (Self-Practice Project)
1. Test Plan Identifier

Project Name: OpenCart – E-Commerce Website
Test Plan ID: TP_OPENCART_01
Prepared By: Hiren Rathod (QA Manual Trainee)
Test Type: Manual Functional Testing
Version: 1.0


2. Overview

The purpose of this test plan is to validate the functional behavior, usability, and reliability of the OpenCart e-commerce website.
This testing activity ensures that key user workflows such as User Registration, Login, Logout , Add To Cart , Checkout , Forgot Password work as per business requirements.

This project is performed as a self-learning QA practice project to gain real-world testing exposure on an e-commerce application.


3. Application Under Test (AUT)

Website: https://www.opencart.com
Domain Type: E-Commerce Platform
Users: Guest users, Registered users, Admin (limited scope)


4. Objectives

Validate core e-commerce functionalities
Identify functional defects before release
Ensure smooth user experience
Practice real-time QA activities like:
Test case writing
Test execution
Bug reporting
RTM preparation


5. Scope of Testing
   In-Scope

The following modules are covered:

1.User Registration
  Valid registration
  Mandatory field validation
  Error messages

2.Login / Logout
  Valid & invalid credentials
  Session handling
  Logout functionality

3.Add to Cart
  Add product to cart
  Quantity update
  Remove product
 
4.Checkout Process
  Guest checkout
  Registered user checkout
  Address, shipping & payment flow

5.UI & Usability
  Button alignment
  Field labels
  Error messages clarity


#. Out of Scope

Performance testing
Security testing
Automation testing
Payment gateway real transactions
Admin backend deep testing


6. Test Approach (How Testing Is Done)

1. Testing Type
   Manual Functional Testing
   Black Box Testing
   Exploratory Testing (basic)

2. Test Design Technique
   Equivalence Partitioning
   Boundary Value Analysis
   Error Guessing

3. Test Execution
   Test cases written in Excel
   Test cases executed manually
   Actual Result vs Expected Result recorded
   Defects logged for failed cases


7. Test Deliverables

Test Plan Document
Test Scenarios
Detailed Test Cases (Excel)
Test Execution Report
Defect/Bug Reports
Requirement Traceability Matrix (RTM)


8.Tools Used

| Tool                         | Purpose                        |
| ---------------------------- | ------------------------------ |
| MS Excel / Google Sheets     | Test cases, execution & RTM    |
| JIRA                         | Bug reporting & tracking       |
| Postman (Basic)              | API validation (if applicable) |
| Browser (Chrome/Firefox)     | UI & functional testing        |



9. Test Environment

OS: Windows 10
Browser: Chrome, Firefox
Internet: Stable connection
Test Data: Dummy user details & sample products


10. Entry Criteria

Website accessible
Test cases prepared and reviewed
Test environment ready


11. Exit Criteria

All planned test cases executed
Critical and major defects reported
Test execution report prepared


12. Defect Management

Defects logged in JIRA
Defect fields include:
Summary
Steps to Reproduce
Expected Result
Actual Result
Severity & Priority
Status


13. Timeline


| Activity                  | Duration |
| ------------------------- | -------- |
| Requirement Understanding | 1 Day    |
| Test Scenario Creation    | 1 Day    |
| Test Case Writing         | 3 Days   |
| Test Execution            | 3 Days   |
| Bug Reporting             | 1 Day    |
| RTM & Final Report        | 1 Day    |


14. Risks & Mitigation

| Risk                     | Mitigation                 |
| ------------------------ | -------------------------- |
| Test data unavailability | Use dummy data             |
| Website changes          | Re-validate test cases     |
| Limited access           | Focus on user-side testing |


15. Approval

This test plan is created for learning and practice purposes to simulate real-time QA testing activities on an e-commerce application.

