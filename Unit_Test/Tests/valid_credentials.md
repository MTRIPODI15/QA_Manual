# Test Suite – SauceDemo Login

## Test Case 1: Successful Login Validation

### 🔹 Steps

1. Open the browser and go to [https://www.saucedemo.com/](https://www.saucedemo.com/)
2. Enter the following credentials:
   - **Username**: `standard_user`
   - **Password**: `secret_sauce`
3. Take a screenshot before login → `Evidence/TST1_PreLogin.png`
4. Click the **Login** button
5. Expected Result: User is successfully logged in and redirected to the inventory page
6. Take a screenshot after login → `Evidence/TST1_PostLogin.png`
7. Actual Result:  Login successful

### 📸 Screenshots
- `TST1_PreLogin.png` – Login form filled
- `TST1_PostLogin.png` – Inventory page loaded

###  Status
**Passed**

### 📝 Notes
> The login flow worked as expected using valid credentials.  
> No errors were displayed and the user was redirected correctly.

## Test Case 2: Successful Login Validation

### 🔹 Steps

1. Open the browser and go to [https://www.saucedemo.com/](https://www.saucedemo.com/)
2. Enter the following credentials:
   - **Username**: `standard_user`
   - **Password**: `123456`
3. Take a screenshot before login → `Evidence/TST2_PreLogin.png`
4. Click the **Login** button
5. Expected Result: Login failed as expected
6. Take a screenshot after login → `Evidence/TST2_PostLogin.png`
7. Actual Result:  Login successful

### 📸 Screenshots
- `TST2_PreLogin.png` – Login form filled
- `TST2_PostLogin.png` – Inventory page loaded

###  Status
**Passed**

### 📝 Notes
> The system correctly blocked access with invalid credentials.  
> The error message was clear and matched the expected result.
