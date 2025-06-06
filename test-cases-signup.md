### 🧪 Test Case: User Registration Flow – automationexercise.com

| TC ID | Test Scenario                     | Steps                                                                 | Expected Result                                | Status |
|-------|-----------------------------------|-----------------------------------------------------------------------|------------------------------------------------|--------|
| TC01  | Valid user registration           | Go to Sign Up page → Enter valid name/email → Click Sign Up          | User is directed to next registration screen   | Pass   |
| TC02  | Registration with empty fields    | Go to Sign Up page → Leave fields empty → Click Sign Up              | Error message: "Email or Name is required"     | Pass   |
| TC03  | Registration with invalid email   | Go to Sign Up page → Enter "abc" as email → Click Sign Up            | Error message: "Invalid email format"          | Fail   |
| TC04  | Registration with existing email  | Enter email already used → Click Sign Up                             | Error message: "Email already exists"          | Pass   |
