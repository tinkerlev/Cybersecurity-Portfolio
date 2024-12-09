# SQL Injection

## 🌟 Room Overview
- **Platform:** TryHackMe
- **Focus Area:** Offensive Security > Web Security
- **Key Tools/Concepts Learned:** SQL Injection techniques, database enumeration, and bypassing login forms.

---

## 🛠 Key Objectives
1. Understand how SQL Injection works and its impact on web applications.
2. Practice exploiting login forms vulnerable to SQL Injection.
3. Learn how to enumerate databases and extract data using UNION-based SQL Injection.
4. Identify effective mitigation techniques for SQL Injection.

---

## 📘 What I Learned
- SQL Injection is one of the most critical web vulnerabilities (OWASP Top 10).
- How to identify and exploit vulnerabilities in SQL-based applications.
- UNION-based SQL Injection techniques to enumerate databases and tables.
- Exploiting login forms by bypassing authentication using crafted SQL payloads.
- The importance of parameterized queries and input validation to prevent SQL Injection attacks.

---

## 🛠 Tools Used
- **Burp Suite:** To intercept and modify HTTP requests.
- **SQLMap:** To automate the exploitation of SQL Injection vulnerabilities.
- **Browser Developer Tools:** To inspect and manipulate form submissions.

---

## 🧠 Challenges Faced
1. Understanding how to construct SQL queries manually to extract database information.
2. Dealing with error-based SQL Injection when error messages are suppressed.
3. Identifying the database type and adjusting payloads accordingly.

---

## 📈 Key Takeaways
- SQL Injection can lead to significant data breaches, unauthorized access, and data manipulation.
- Proper sanitization of user inputs and the use of parameterized queries can effectively mitigate this vulnerability.
- Security controls like Web Application Firewalls (WAFs) can help prevent exploitation but must be combined with secure coding practices.

---

## 🔗 Additional Resources
- [Link to TryHackMe Room](https://tryhackme.com/room/sqlinjection)
- [OWASP SQL Injection Prevention Cheat Sheet](https://owasp.org/www-project-cheat-sheets/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)

---

Thank you for exploring my documentation on the SQL Injection room! 😊
