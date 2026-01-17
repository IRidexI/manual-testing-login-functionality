# Login Test Cases

---

### TC-01: Login with valid credentials

**Precondition:**  
User exists in the system

**Environment:**  
Windows 10, Google Chrome 126.0

**Steps:**
1. Open the login page  
2. Enter a valid username  
3. Enter a valid password  
4. Click the "Login" button  

**Expected Result:**  
User is successfully logged in and redirected to the secure area.

---

### TC-02: Login with invalid password

**Precondition:**  
User exists in the system

**Environment:**  
Windows 10, Google Chrome 126.0

**Steps:**
1. Open the login page  
2. Enter a valid username  
3. Enter an invalid password  
4. Click the "Login" button  

**Expected Result:**  
System displays an error message and user remains on the login page.

---

### TC-03: Login with password longer than allowed length

**Precondition:**  
User exists in the system

**Environment:**  
Windows 10, Google Chrome 126.0

**Steps:**
1. Open the login page  
2. Enter a valid username  
3. Enter a password longer than the allowed limit  
4. Click the "Login" button  

**Expected Result:**  
System prevents login and displays a validation error.

---

### TC-04: Login with empty fields

**Precondition:**  
User exists in the system

**Environment:**  
Windows 10, Google Chrome 126.0

**Steps:**
1. Open the login page  
2. Leave all fields empty  
3. Click the "Login" button  

**Expected Result:**  
Validation error is displayed and user remains on the login page.

---

### TC-05: Login with special characters in password

**Precondition:**  
User exists in the system

**Environment:**  
Windows 10, Google Chrome 126.0

**Steps:**
1. Open the login page  
2. Enter a valid username  
3. Enter a password containing special characters (!@#$%^&)  
4. Click the "Login" button  

**Expected Result:**  
User is successfully logged in and redirected to the secure area.
