# Login Test Cases - SauceDemo

Application: https://www.saucedemo.com/  
Test Type: Manual Functional Testing  

---

## TC-001 - Valid login

Precondition: User is on login page

Steps:
1. Enter username: standard_user
2. Enter password: secret_sauce
3. Click Login

Expected Result:
User is redirected to Products page

---

## TC-002 - Invalid password

Precondition: User is on login page

Steps:
1. Enter username: standard_user
2. Enter password: wrong_password
3. Click Login

Expected Result:
Error message is displayed

---

## TC-003 - Empty fields

Precondition: User is on login page

Steps:
1. Leave username empty
2. Leave password empty
3. Click Login

Expected Result:
Validation error message is displayed
