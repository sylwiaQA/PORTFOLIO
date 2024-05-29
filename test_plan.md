# Test Plan for an online Store

 Table of Contents:
1. [Purpose of Testing](#Purpose-of-Testing)
2. [Scope of Testing](#scope-of-testing)
3. [Subject of Testing](#subject-of-testing)
4. [Pass Criteria](#pass-criteria)
5. [Fail Criteria](#fail-criteria)
6. [Entry Criteria](#entry-criteria)
7. [Exit Criteria](#exit-criteria)
8. [List of Functionalities to be Tested](#list-of-functionalities-to-be-tested)
9. [Test Environment](#test-environment)
10. [Error Categories](#error-categories)
11. [Test Location](#test-location)
12. [Test Schedule](#test-schedule)
13. [Test Reports](#test-reports)
14. [List of Tools](#list-of-tools)
15. [Incident Management](#incident-management)
16. [Roles and Responsibilities](#roles-and-responsibilities)

## Purpose of Testing
The purpose of the created test plan is to thoroughly test the functionality of the store based on the provided requirements. 

The store's address is: https://rpstore.pl. 

All encountered defects will be fixed and handed over to testers for confirmation testing.

## Scope of Testing
Levels of Testing Covered in the Test Plan:

- **Unit Testing**
   - **Description**: These tests check the smallest units of code (functions, methods, classes) in isolation.
   - **Example**: Testing a function that calculates the total price of products in the cart after applying a discount.

- **Integration Testing**
   - **Description**: These tests ensure that different modules or services work together correctly.
   - **Example**: Checking if the payment module correctly communicates with the payment gateway and updates the order status.

- **System Testing**
   - **Description**: These tests verify if the entire system meets the functional and non-functional requirements.
   - **Example**: Testing the full purchase process, from adding a product to the cart, through the payment process, to order confirmation.

- **Acceptance Testing**
   - **Description**: These tests check if the system meets the acceptance criteria and is ready for deployment.
   - **Example**: Conducting end-user tests to ensure that the user registration process is intuitive and error-free.

Types of tests included in the test plan

- **Functional Testing** - The software will be verified based on provided specifications.
    
    1. **Navigation on the Website**
   - Testing the functionality of the main menu and subpages.
   - Checking links to product categories.
   - Testing the product search functionality.

    2. **Purchase Process**
   - Adding products to the cart.
   - Changing the quantity of products in the cart.
   - Removing products from the cart.
   - Navigating through the order process (filling in data, choosing delivery and payment methods).

    3. **Registration and Login**
   - Creating a new user account.
   - Logging in and logging out.
   - Password reminder.
   - Editing user account data.

    4. **Additional Functionalities**
   - Testing the operation of product filters and sorting.
   - Testing the newsletter functionality (sign up and unsubscribe).
   - Testing the contact form functionality.

- **Automated Testing** - Implementation of automated tests for key system functionalities according to provided test cases.

- **Usability Testing** - These tests assess how easy it is for users to interact with the system.
     1. **Accessibility and Readability**
       - Evaluation of text readability on various devices.
       - Checking the responsiveness of the website (whether the site is readable on mobile devices).
       - Testing accessibility for people with disabilities (e.g., screen reading).
     2. **Interface Intuitiveness**
       - Assessment of whether new users can intuitively navigate the site.
       - Testing whether messages and instructions are clear and understandable.

- **Compatibility Testing** - These tests check if the system works correctly on different devices, browsers, and operating systems.
    - Testing the website on different browsers (Chrome, Firefox, Safari, Edge).
    - Testing on different operating systems (Windows, macOS, Linux).
    - Checking the website's functionality on various screen resolutions.

- **Regression Testing** -  These tests aim to detect if new changes in the code have introduced errors in existing functionality.
   - After adding a new product filtering feature, testing the entire purchasing process to ensure it works correctly.

- **Performance Testing** - These tests evaluate how the system behaves under load.
    - Checking page loading times.
    - Testing the performance of the website under heavy load (e.g., simulating multiple users).

- **Security Testing** - These tests identify potential security vulnerabilities in the system.
     - Verifying if user data is securely transmitted (e.g., via HTTPS).
    - Testing for vulnerabilities to common attacks (e.g., SQL Injection, XSS).
    - Testing privacy policy and data security measures.

**Error Management**
- Checking how the website handles incorrect data entered by the user.
- Testing error messages and their clarity.


## Subject of Testing

The subject of the tests is an online store available at the following address:
https://rpstore.pl along with all its functionalities.

## Pass Criteria

1. **Performance Testing**
   - Server response time must not exceed 500 ms.
   - The software must withstand a load of 1000 users simultaneously.

2. **Functional Testing**
   - Acceptance criteria are aligned with the current implementation of the online store.

3. **Automated Testing**
   - All test cases have been automated.
   - Tests have been integrated with the CI/CD tool - Jenkins.

## Fail Criteria

Kryteria niezaliczenia

1. **Performance Testing**
   - Server response time exceeds 500 ms.

2. **Functional Testing**
   - Implemented functionalities are not compliant with requirements.

## Entry Criteria

- Running Test Environment
- The test environment must closely resemble the production environment.
- Access to a device with iOS system.

## Exit Criteria

- All test cases executed.
- All types and levels of tests included in the test plan have been completed.
- All defects have been rectified.

## List of Functionalities to be Tested
!!!!!!!!!ja to już opisałam / zastanowić się czy tu to potrzebuje???
- Order Placement Process - Test Case 001
- hjfjksdhfks Test Case 002 
- hfujdhfjd Test Case 003 

## Test Environment
Tests of the online store will be conducted on the dedicated server https://rpstore.pl. The test environment closely resembles the production environment in terms of parameters.

Server specification:
- Processor: 1.60 GHz
- RAM: 20 GB
- Disk: 240 GB
- System: Microsoft Windows 11 Home

Tests will be conducted using the following devices:
1. PC Computer
   - Processor: 13 3.6 GHz
   - RAM: 16 GB
2. Mobile devices with iOS system, iPhone 14 Pro
   - Processor: Apple A15 Bionic
   - RAM: 4 GB
   - iOS version: 16

## Error Categories
We distinguish different priorities in our test plan:
- Critical
- Blocker
- Major
- Medium
- Minor

## Test Location
Tests will be conducted at the headquarters of the software development company by the tester.

## Test Schedule 
!!!!!!tu muszę jeszcze sobie dopisać pozostałe testy jakie uwzględniłam w planie !!!!!!!!
1. **Static Testing**
   - Verification of prepared documentation
   - Verification of user stories
   Time: 15 h
   
2. **Functional Testing**
   - Verification of implemented functionalities according to prepared assumptions
   - Reporting defects
   - Execution of test cases
   Time: 40 h

3. **Performance Testing**
   - Verification of server response time
   - Verification of server load with users
   Time: 20 h

4. **Automated Testing**
   - Preparation of file structure
   - Implementation of automated tests based on provided test cases
   - Integration of tests with Jenkins tool
   - Integration of tests with Grafana tool
   Time: 60 h

## Test Reports (!!!tu mogłabym podpiąć swój plik z test cases!!!!!)
- Reports on detected defects
- Designed test cases
- Automated test scripts
- Metrics from performance tests

## List of Tools

1. **Defect Reporting Tools**
   - Jira

2. **Tools for Creating Test Cases**
   - TestLink
   - XRay

3. **Automation Tools**
   - WebdriverIO
   - SuperTest
   - Allure
   - Jenkins
   - Grafana

4. **Performance Testing Tools**
   - JMeter

5. **Tools for Creating Screenshots and Videos**
   - PickPick
   - ShareX

## Incident Management
After a defect is detected, it will be reported to the defect management system, which is Jira. Such a defect will have a priority specified in the test plan and a person responsible for fixing the issue.

Once the programmer fixes the defect, it will then be assigned back to the tester for confirmation testing.

Upon successful correction of the defect, the report will be closed and moved to the Done column.

In case the defect is not fixed correctly, the report will be reassigned to the programmer.

## Roles and Responsibilities

- Test Manager - supervising and organizing the work of the entire testing team.

- Test Analyst - analyzing the test basis, preparing test scenarios needed for testing, and supporting the Test Manager.

- Tester - executes tasks assigned by the Test Manager, performs tests, and reports defects.

- System Technical Administrator - prepares the test environment and supervises it during the testing process.





