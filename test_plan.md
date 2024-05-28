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

## Test Environment

## Error Categories

## Test Location

## Test Schedule

## Test Reports

## List of Tools

## Incident Management

## Roles and Responsibilities






