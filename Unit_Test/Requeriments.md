# Test Request – Login Functionality

## Requested by
QA Lead / Project Manager

## Objective
To validate the login functionality of the web application using manual testing with https://www.saucedemo.com/.  
The goal is to confirm that users can log in with valid credentials and receive proper feedback when credentials are invalid or missing.

## Scope
- Login page
- Input fields: email and password
- Submit button
- Error messages
- Redirection after login

## Test Scenarios
1. Login with valid credentials
2. Login with invalid password
3. Login with empty fields
4. Login with invalid email format
5. Login with SQL injection attempt

## Acceptance Criteria
- Valid users are redirected to the homepage
- Invalid credentials show error message
- Empty fields are not accepted
- Email format is validated
- No security vulnerabilities are exposed

## Notes
> This test request is part of the basic QA Manual suite.  
> Evidence and results will be documented in separate test case files.