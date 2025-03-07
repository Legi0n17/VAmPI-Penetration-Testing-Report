# **VAmPI - Vulnerable API Penetration Testing**

## 📌 **Overview**
This project documents my penetration testing approach on **VAmPI**, a deliberately vulnerable API designed to simulate real-world API security flaws. The goal was to identify, exploit, and understand vulnerabilities based on the **OWASP API Security Top 10**.

## 🎯 **Scope of Testing**
- **Target:** [VAmPI (Vulnerable API)](https://github.com/erev0s/VAmPI)
- **Focus Areas:**
  - SQL Injection
  - Unauthorized Password Change
  - Broken Object Level Authorization (BOLA)
  - Mass Assignment
  - Excessive Data Exposure through debug endpoint
  - User and Password Enumeration
  - Lack of Resources & Rate Limiting
  - Security Misconfiguration
  - Authentication & Authorization Flaws
  - Information Disclosure


## 🛠 **Tools Used**
- **SQLmap** – Automated SQL Injection testing
- **Burp Suite** – Intercepting and modifying API requests
- **Postman** – Testing API endpoints and authentication
- **FFuf** – Fuzzing API endpoints for hidden resources
- **JWT Toolkit** – Manipulating JSON Web Tokens
- **cURL** – Sending API requests manually

## 📌 **How to Set Up the Testing Environment**
Refer to the [VAmPI GitHub Repository](https://github.com/erev0s/VAmPI) for test reproduction details.

## 📢 **Disclaimer**
This project is for **educational purposes only**. Do not use these techniques on live applications without permission.
