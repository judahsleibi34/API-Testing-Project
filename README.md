# Contact List App - API Testing Report
## Overview
This repository contains the API testing report for the Contact List App. The testing focused on ensuring core API functionalities work correctly across multiple scenarios. Both manual and automation testing were performed using Postman to validate API responses, status codes, and data integrity. The primary goal of this report is to provide insights into the testing process and results for better understanding and review.

## Project Details
Project Title: Contact List App - API Testing Report

## Date of Testing:
13th December 2024

## Test Environment
The API testing was performed using the following tools and technologies:

## Testing Tool: 
Postman.

## Programming Language: 
JavaScript.

## API Endpoints: 
Tested against the Contact List App's backend services.

## Scope of Testing:
The testing focused on the following aspects of the Contact List App's API:

1. API Endpoints
Validation of all available API endpoints (e.g., GET, POST, PUT, DELETE).

Ensuring proper request and response structures.

2. Status Codes
Verifying that the API returns the correct HTTP status codes (e.g., 200, 201, 400, 404, 500).

3. Data Integrity
Ensuring accurate data submission and retrieval.

Validating error handling for invalid inputs.

4. Performance
Testing API response times under normal and peak loads.

## Test Results:
The API testing yielded the following results:

1. Add Contact: Passed.

2. Get Contact: Passed.

3. Update Contact: Passed.

4. Delete Contact: Passed.

5. Error Handling: Passed.

All core API functionalities were validated successfully, and the API performed as expected across all test scenarios.

## Tools and Technologies Used
1. Postman: For manual and automation testing of API endpoints.

2. JavaScript: For writing Postman test scripts.

## Repository Structure
Copy
contact-list-api-testing/
├── postman/                     
│   ├── ContactListApp.postman_collection.json  
│   └── ContactListApp.postman_environment.json 
├── test-scripts/                  
│   └── api-tests.js               
├── reports/                        
│   └── api-test-report.html        
├── README.md                       
└── requirements.txt               

## Conclusion
The API testing for the Contact List App was successfully completed, validating all core functionalities and ensuring proper error handling and performance. The test results confirm that the API performs as expected, providing a reliable backend for the application. This report serves as a reference for future testing and development efforts.

## Future Work
1. Expand test coverage to include additional edge cases.

2. Integrate API testing with CI/CD pipelines for automated testing during deployment.

3. Add performance testing using tools like JMeter or k6.
