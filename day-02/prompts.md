\# Day 02 - Prompt Library



\## Objective



This document contains the prompts created during Day 02 of the AI Testing Challenge.



\---



\# Prompt 1 - Test Case Generation



\## Goal



Generate comprehensive test cases for the Sign In functionality.



\### Prompt



```text

Act as a Senior Quality Analyst with 10+ years of experience in Web Application Testing.



Generate comprehensive test cases for the "Sign In" functionality of an e-commerce web application.



Feature Details:

\- User can sign in using a registered email address and password.

\- Email must be in a valid format.

\- Password is case-sensitive.

\- "Remember Me" checkbox is available.

\- "Forgot Password" link is available.

\- User account can be Active, Locked, or Disabled.

\- Maximum 5 failed login attempts should lock the account.

\- Successful login redirects the user to the Dashboard.



Test Coverage:

\- Positive

\- Negative

\- Boundary Value

\- Edge Cases

\- Validation

\- Security

\- UI

\- Usability



Output Format:

Markdown table including:

\- Test Case ID

\- Scenario

\- Steps

\- Expected Result

\- Priority

\- Test Type



Generate at least 40 test cases.

```



\---



\# Prompt 2 - Playwright Automation



\## Goal



Generate Playwright automation scripts.



\### Prompt



```text

Act as a Senior SDET with expertise in Playwright and JavaScript.



Generate Playwright automation scripts for the Sign In functionality.



Requirements:

\- JavaScript

\- Playwright Test

\- Page Object Model (POM)

\- Reusable Components

\- Avoid XPath

\- Use Playwright Locators

\- Use expect() assertions

\- Use beforeEach()



Generate:



1\. Folder Structure

2\. LoginPage.js

3\. Login.spec.js

4\. Test Data

5\. Execution Command

```



\---



\# Prompt 3 - REST API Testing



\## Goal



Generate Login API test cases.



\### Prompt



```text

Act as a Senior API Test Engineer.



Generate REST API test cases for the Login endpoint.



Cover:



\- Positive

\- Negative

\- Authorization

\- Authentication

\- Security

\- Boundary Values

\- Invalid Requests

\- Error Handling



Output:

Markdown table.

```



\---



\# Prompt 4 - SQL Query Generation



\## Goal



Generate SQL validation queries.



\### Prompt



```text

Act as a Database Testing Expert.



Generate SQL queries to validate:



\- Duplicate Email

\- NULL Values

\- Invalid Records

\- Active Users

\- Locked Accounts



Database:

MySQL



Output:

Optimized SQL queries with explanations.

```



\---



\# Key Learning



A good prompt contains:



\- Role

\- Objective

\- Context

\- Requirements

\- Constraints

\- Output Format



Better prompts produce better AI responses.

