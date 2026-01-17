# Login Bug Reports

---

### BG-01: System allows login with invalid password
**Severity:** Critical

**Environment:** Windows 10, Chrome 126.0

**Steps to Reproduce:**
1. Open the login page
2. Enter a valid username
3. Enter an invalid password
4. Click the "Login" button

**Expected Result:**  
System prevents login and displays an error message.

**Actual Result:**  
User is logged in and redirected to the secure area.

---

### BG-02: System prevents login with valid credentials
**Severity:** Critical
**Environment:** Windows 10, Chrome 126.0

**Steps to Reproduce:**
1. Open the login page
2. Enter a valid username
3. Enter a valid password
4. Click the "Login" button

**Expected Result:**  
User is successfully logged in.

**Actual Result:**  
System displays an error and prevents login.

