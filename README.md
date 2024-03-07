# CyberProject

Demonstrating SQLi & XSS Vulnerabilities using Express & NodeJS

This project showcases security vulnerabilities related to Cross-Site Scripting (XSS) and SQL Injection. There are two main branches:

1. **Main Branch (Non-vulnerable project):**
   - This branch represents the main and secured version of the project, offering solutions to security vulnerabilities.
   
2. **Vulnerable Project Branch:**
   - This branch demonstrates the XSS and SQL Injection vulnerabilities.

## Technologies Used

- NodeJS
- Express
- NPM
- MySQL
- JWT (JSON Web Tokens)
- BCRYPT

## Local Setup

All applications run locally, and the database is hosted on AWS instances, allowing remote control and handling change requests to the database.

## Vulnerability Explanation

### XSS (Cross-Site Scripting)

Cross-Site Scripting (XSS) is a security vulnerability that enables the injection of client-side scripts into web pages. Attackers can use this to make the website execute undesired code. For example:

```html
<script>window.location.href="http://malicious.domain"</script> ```html
you are unwantedlly redirect to malicious domain.

### SQLi (SQL Injection)
SQL Injection is a code injection technique which executes malicious SQL statements against a relational database."

