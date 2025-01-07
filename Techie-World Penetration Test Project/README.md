# Techie-World Penetration Test Project

Welcome to my **Techie-World Penetration Test Project** repository! This project demonstrates a structured approach to identifying and exploiting vulnerabilities in a simulated server environment. The goal was to gain unauthorized access, escalate privileges, and retrieve a target flag stored on the system.

---

## 📂 What's Inside?

This folder contains all the key files and resources used in this project. Here's a breakdown of each file and what it includes:

- **README.md:** You're reading it now! This file provides an overview of the project, the file structure, and guidance on navigating the repository.  
- **report.txt:** A detailed penetration testing report summarizing the vulnerabilities identified, tools used, and recommendations for improving security.  
---

## 🚀 Getting Started

To understand the approach taken during this penetration test, start with the **report.txt** file. It includes:
- The findings from reconnaissance and enumeration.
- Exploitation steps, including cookie manipulation and reverse shell setup.
- Details of the privilege escalation and flag retrieval process.

For visual evidence, browse the **screenshots/** folder to see key moments in the exploitation process.

---

## 🔍 Project Highlights

1. **Weak Cookie-Based Authentication:**  
   - Modified a cookie parameter (`user`) to gain unauthorized admin access to sensitive parts of the system.  

2. **Command Injection Exploitation:**  
   - Exploited the `mpdf.php` file to execute system commands and access sensitive files.

3. **Privilege Escalation:**  
   - Used Python to elevate privileges from `www-data` to `root`, gaining full control over the system.  

4. **Flag Retrieval:**  
   - Successfully accessed `/root/.flag.txt` and retrieved the target flag.

---

## 🛑 Ethical Disclaimer

All testing in this project was conducted ethically and in a simulated environment designed for learning purposes. This project aims to promote security awareness and ethical hacking practices.

---

Thank you for visiting this repository! If you have any questions or are interested in collaboration, feel free to reach out. 😊
