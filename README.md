# CS-305
Porfolio Submission for CS305 - Software Security 2025
# Project Overview
Artemis Financial is a client that requested help identifying vulnerabilities within their Spring-based financial web application. This application handles private user data, including account details and personal information. My object was to perform a security assessment and document existing vulnerabilities using industry best practices.

# What I Did Well
While reviewing the Java code and running an OWASP Dependency Check, I was able to spot several important issues. These included outdated libraries, missing input validations, and some function calls that could pose a risk. I focused mostly on logical flaws that specifically handled user input and expressions. This review helped me ensure the code followed secure practices giving the app a stronger defense against potential threats.

# Security Importance
Secure coding helps protect user data and prevents attacks. For Artemis, strong security builds customer trust, lowers future risks, and can increase the overall quality and reliability for the company.

# Challenges Faced
It was tricky reviewing dynamic expressions and seeing how they affected the program during testing. However, it helped me understand how injection issues can happen when input isn’t carefully validated.

# Vulnerability Assessment Process
I followed the standard vulnerability assessment flow:
1. **Identify vulnerable dependencies** using OWASP tools.
2. **Review source code** for poor input handling, insecure logic, or unsafe method calls.
3. **Document vulnerabilities**, explaining their nature, severity, and risk impact.
4. **Provide recommendations** on how to mitigate each identified issue.

# Tools and Practices Used
- **OWASP Dependency-Check**
- **Manual code review**
- Followed **NIST** and **OWASP** guidelines
- Analyzed use of **Spring Expression Language (SpEL)**

# Future Use
This assessment report is a strong example of my secure software analysis skills. I would showcase this to potential employers to demonstrate my aptitude and ability to find and document real-world vulnerabilities, review and maintain security, and follow a structured reporting format for any flaws. 
