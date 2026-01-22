# BUG-002 - Username field is highlighted as error when password is incorrect

Application: https://www.saucedemo.com/  
Environment: Desktop / Chrome  
Type: UI / Validation  
Severity: Low  

---

## Summary
When the username is correct and the password is incorrect, both fields are highlighted as invalid.

---

## Steps to Reproduce
1. Open the login page
2. Enter a valid username
3. Enter an invalid password
4. Click Login

---

## Actual Result
Both username and password fields are highlighted as error.

---

## Expected Result
Only the password field should be highlighted.

---

## Impact
This may confuse users about which field is incorrect.
