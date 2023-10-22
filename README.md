# Brandon Marrero - CS-305 Software Security

## Reflection

- Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial, a consulting company specializing in personalized financial plans, aimed to modernize their operations with advanced software security for their RESTful web application API. The objective was to detect security vulnerabilities, introduce file verification for secure communication, and implement data verification using checksums, all without compromising security.

- What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
A notable achievement was the thorough documentation of vulnerabilities and their corresponding mitigation steps. Coding securely is essential to protect company and user data, preventing unintended program exploitation. It enhances a company's reputation and overall well-being by reducing security threats.

- What part of the vulnerability assessment was challenging or helpful to you?
The challenging aspect of the vulnerability assessment involved creating suppression files for outdated dependency vulnerabilities discovered during static analysis.

- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Security measures were bolstered through the adoption of input validation, cryptography, secure API interactions, secure error handling, and adherence to secure coding best practices and patterns. In future assessments, secure coding practices and tools like the OWASP dependency check tool would be advantageous.

- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
The code and software application's functionality and security were confirmed through meticulous code review and rigorous testing. A pre-refactoring dependency vulnerability scan identified existing issues, and a post-refactoring scan ensured the absence of newly introduced vulnerabilities.

- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Valuable resources for future assignments include secure coding practices and tools like the OWASP dependency check tool.

- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
To showcase to prospective employers, you could present the Vulnerability Assessment Report, Practices for Secure Software Report, and the refactored application from project 2. These examples demonstrate your knowledge and skills, particularly in utilizing self-signed certificates with a RESTful API.
