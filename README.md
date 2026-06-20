# Secure Coding Review

## Overview
This project was completed as part of the CodeAlpha Cyber Security Internship Program.

The objective of this task is to perform a security review of a simple Python login application, identify vulnerabilities, analyze associated risks, and implement secure coding practices.

## Objectives
- Identify security vulnerabilities in source code.
- Analyze potential security risks.
- Implement secure coding techniques.
- Improve application security.

## Vulnerabilities Identified
### 1. Hardcoded Credentials
Sensitive credentials were directly stored in the source code.

### 2. Plain Text Password Storage
Passwords were stored in readable format, making them vulnerable if the source code is exposed.

### 3. No Brute Force Protection
The application allowed unlimited login attempts.

## Technologies Used
- Python 3
- hashlib Library

## Project Structure

```
CodeAlpha_SecureCodingReview/
│
├── vulnerable_login.py
├── secure_login.py
├── Secure_Coding_Review_Report.pdf
├── screenshots/
└── README.md
```

## Vulnerable Code

```python
users = {
    "admin": "admin123",
    "user": "password"
}
```

## Secure Features Implemented
- SHA-256 Password Hashing
- Limited Login Attempts
- Improved Authentication Logic

## Results
The secure implementation significantly improved the protection of user credentials and reduced the risk of unauthorized access.

## Conclusion
Secure coding practices are essential for developing safe and reliable applications. This project demonstrates how common vulnerabilities can be identified and mitigated effectively.

## Internship Information
CodeAlpha Cyber Security Internship

## Author
Awais Tariq

