#Bug report-Login Fails With Valid Credentials
## Bug ID
BUG-001
## Title
User cannot log in using valid credentials
## Severity
High
## Priority
High
## Environment
-Device:Desktop
-OS Windows 11
-Browser:google Chrome version 136.x
-Website: Demo Login Page
-Network: Wi-Fi

---

## Description The system doesn not allow the user to log in when correct credentials are entered

---

## Preconditions
-User account already registered
-Internet connection active

---

## Steps to Reproduce
1. Open login page
2. Enter a valid email address (without special characters)
3. Enter a correct password
4. Click the "login" button

---

##Expected Result 
THe user should be successfully redirected to the dashboard/homepage

---

##Actual Result
The page refreshes but the user remains on the login screen without any error messages

---

## Frequency
Occurs every time

---

## Notes
Issue may be related to backend authentication validation or session handling.
