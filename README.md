# DVWA-SQL-Injection-Analysis

Overview-
This project documents my hands-on analysis of SQL Injection vulnerabilities using DVWA (Damn Vulnerable Web Application).

The objective of this project was to understand how SQL Injection vulnerabilities occur, analyze source code across different security levels, and learn how secure coding proctices mitigate these vulnerabilities.

Lab Environment:
•	Kali Linux.
•	DVWA (Damn Vulnerable Web Application).
•	PHP.
•	MySQL.

Security Levels Analyzed:
Low Security
•	No input validation.
•	User input is directly included in SQL queries.
•	Highly vulnerable to SQL Injection.

Medium Security

•	Uses input escaping techniques.
•	Basic protection is implemented.
•	Dynamic SQL queries are still present.


High Security
•	Additional security controls are implemented.
•	Session-based handling and query restrictions are used.
•	Attack surface is reduced.


Impossible Security
•	Uses prepared statements and parameterized queries.
•	Input validation is performed.
•	CSRF protection is enabled.
•	Strong protection against SQL Injection attacks.


Key Learnings
•	Never trust user-supplied input.
•	SQL Injection vulnerabilities often result from insecure query construction.
•	Input validation and sanitization improve security but are not always sufficient.
•	Prepared statements are one of the most effective defenses against SQL Injection.
•	Secure coding practices significantly reduce application risk.

Personal Reflection
During this project, I reviewed the PHP source code for each security level and observed how security controls evolved from vulnerable query construction to secure parameterized queries. This hands-on experience improved my understanding of both offensive and defensive web application security concepts.

Skills Demonstrated
•	Web Application Security
•	SQL Injection Analysis
•	Source Code Review
•	Secure Coding Principles
•	Vulnerability Assessment

Disclaimer
All testing and analysis were performed in a local DVWA lab environment for educational purposes only.
