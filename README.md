# OWASP Juice Shop – Web Application Security

## About

This was a group project where we used OWASP Juice Shop, a deliberately vulnerable web application, to identify and exploit different security vulnerabilities.

My individual contribution focused on broken authentication and broken access control. I completed five challenges using manual testing, Burp Suite and OSINT techniques.

## My Individual Contributions

### 1. Password Strength – Broken Authentication

Tested weak and commonly used passwords against the administrator login to demonstrate weaknesses in password security.

### 2. Forged Feedback – Broken Access Control

Used Burp Suite to intercept and modify a feedback request, changing the user ID to submit feedback under another user's account.

### 3. Bjoern's Favourite Pet – Broken Authentication

Used OSINT techniques to investigate publicly available information and identify the answer to a password recovery security question.

### 4. Easter Egg – Broken Access Control

Explored hidden application resources and used null-byte injection to bypass file extension filtering and access a restricted file.

### 5. GDPR Data Erasure – Broken Authentication

Used SQL injection to access a previously deleted user account, demonstrating weaknesses in authentication and data deletion.

## Tools and Techniques Used

- OWASP Juice Shop
- Burp Suite
- SQL Injection
- OSINT
- HTTP request interception and modification
- Null-byte injection
- Web application vulnerability testing

## What I Learned

This project helped me understand how web application vulnerabilities can be identified and exploited. I gained practical experience using Burp Suite to intercept and modify requests, investigating authentication weaknesses and understanding how broken access controls can affect users.

It also helped me understand the importance of secure password policies, input validation and proper access control.

---

**Module:** COMP H2704 – Web Application Security
