# 📄 Test Plan – UserAuth API Test Suite

## 1. Objective
To validate the functionality, reliability, and edge case handling of user authentication APIs including registration, login, profile retrieval, and update using Postman.

## 2. Scope
This test suite covers the following:
- Register new user
- Login user with valid/invalid credentials
- Get user profile
- Update user details
- Negative testing and error handling

## 3. Tools Used
- Postman
- Newman CLI
- Reqres API
- GitHub (for version control)
- Markdown (for documentation)

## 4. Test Types
- Functional Testing
- API Testing
- Regression Testing
- Negative Testing

## 5. Test Environment
- API URL: `https://reqres.in`
- Testing via local Postman environment

## 6. Test Data
- Sample user credentials
- Missing field scenarios
- Invalid token handling

## 7. Entry & Exit Criteria
**Entry:** API is accessible, endpoints are defined  
**Exit:** All test cases executed and passed or known defects documented

## 8. Reporting
- HTML reports generated via Newman
- Bug reports maintained in markdown format

## 9. Status
✅ Initial phase completed with base endpoints  
⏳ Selenium-based UI test suite planned
