# CS305
# Artemis Financial Vulnerability Assessment Report

This repository contains my completed Vulnerability Assessment Report for Artemis Financial, submitted for CS 305 Project One. This report demonstrates my ability to identify, evaluate, and mitigate real-world software vulnerabilities using manual inspection and static analysis tools.

## Journal Reflection

### Who was the client? What issue did the company want you to address?
The client was Artemis Financial, a company that provides financial services. They needed help securing their software, identifying vulnerabilities, and making their application safer from threats like data breaches and injection attacks. I was asked to find problems in the code and recommend how to fix them.

### What did you do well when you found your client’s software security vulnerabilities?
I was able to use the OWASP Dependency-Check tool to identify outdated and unsafe libraries, like log4j and jackson-databind. I also pointed out hardcoded database credentials and unvalidated user input in the source code. Secure coding is important because it prevents hackers from breaking in and helps keep data safe.

### Which part of the vulnerability assessment was challenging or helpful to you?
Figuring out which issues were real threats and which were just warnings was a little challenging. But running the scan and learning how to interpret CVEs was very helpful and taught me how real tools are used in professional settings.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I suggested updating all vulnerable libraries, using safe storage for credentials, and checking user inputs. In the future, So I would continue using tools like OWASP scanners, along with reviewing logs and error-handling mechanisms, to help choose the best ways to fix issues.

### How did you make certain the code and software application were functional and secure?
So I checked that the code could still build and run after removing or changing risky parts. I also re-scanned it after updates to confirm that the most dangerous CVEs were resolved.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
- **OWASP Dependency-Check** to scan dependencies
- **Manual code review** to find logic flaws and unsafe practices
- **Secure coding practices** from *Iron-Clad Java*


### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
So I would show them this report to highlight my ability to evaluate software security, work with real vulnerability scanners, and offer practical solutions. It shows I can build and improve secure applications using modern tools and best practices.
