# Client and Software Requirements
Artemis Financial is a consulting firm that creates individualized financial plans. They needed a secure and modernized web-based RESTful API to protect sensitive customer data. Their concerns included preventing external threats like SQL injection and API abuse, handling international transactions securely, and modernizing operations while managing risks tied to open-source libraries​.

# Finding Vulnerabilities
I effectively identified vulnerabilities by manually reviewing the code and performing static testing. I found issues like hardcoded database credentials, missing input validation, and lack of HTTPS enforcement. It was important to find these early and link them to clear, actionable fixes​.

# Importance of Secure Coding:
Coding securely prevents data breaches, protects customer trust, and ensures compliance with legal regulations. Secure coding adds value by reducing the risk of financial loss, reputational harm, and operational disruptions.

# Challenges and Helpful Aspects
One challenge was making sure new vulnerabilities were not introduced during refactoring. Static analysis using the OWASP Dependency-Check tool was very helpful for quickly identifying risks related to outdated libraries​.

# Increasing Layers of Security:
I increased security by adding SHA-256 cryptographic hashing, enforcing HTTPS through a self-signed certificate, updating all outdated libraries, and eliminating hardcoded secrets. These layers protect data both at rest and in transit​.

# Future Vulnerability Assessments:
In the future, I would use tools like OWASP Dependency-Check, SonarQube, and OWASP ZAP for a combination of static and dynamic testing. I would prioritize vulnerabilities based on impact and likelihood and apply mitigation strategies accordingly.

# Ensuring Functionality and Security
After refactoring, I tested the code in Eclipse with Maven builds, executed the application to ensure proper behavior, and reran dependency checks to confirm no new security issues were introduced​.

# Helpful Resources and Practices:
I used the OWASP Dependency-Check tool, applied SHA-256 hashing, configured HTTPS with a self-signed certificate, and followed secure coding practices like input validation and avoiding hardcoded secrets​.

Work to Show Future Employers:
I would present the vulnerability assessment report, the secure refactored code, screenshots of successful dependency scans and functional tests, and documented mitigation strategies. These showcase my secure coding skills and problem-solving abilities.

