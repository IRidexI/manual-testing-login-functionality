# Login Test Cases

---

### TC-01: Login with valid credentials
**Precondition:** User exists in the system

**Steps:**
1. Open the login page
2. Enter a valid username
3. Enter a valid password
4. Click the "Login" button

**Expected Result:**  
User is successfully logged in and redirected to the secure area.

---

### TC-02: Login with invalid password
**Precondition:** User exists in the system

**Steps:**
1. Open the login page
2. Enter a valid username
3. Enter an invalid password
4. Click the "Login" button

**Expected Result:**  
System prevents login and displays a validation error.

---

### TC-03: Login with password longer than 200 characters
**Expected Result:**  
System prevents login and displays a validation error.

---

### TC-04: Login with empty fields
**Steps:**
1. Open the login page
2. Leave all fields empty
3. Click the "Login" button

**Expected Result:**  
Validation error is displayed and user remains on the login page.

---

### TC-05: Login with special characters
**Expected Result:**  
System handles input correctly and prevents unauthorized login.

