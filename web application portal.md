### What is a web application portal?

A portal is a web-based platform that collects information from different sources into a single user interface and presents users with the most relevant information for their context. Over time, simple web portals have evolved into portal platforms that support digital customer experience initiatives.


### Introduction:

Web application testing is an essential part of ensuring the security of web applications. It involves evaluating web applications against various security vulnerabilities to identify and mitigate potential risks. In this research paper, we will report on the findings of a web application security testing conducted on a sample web application. The testing covered various vulnerabilities and rated them based on their severity.

### Methodology:

The web application security testing was conducted using a combination of automated tools and manual testing techniques. The automated tools used for testing included Burp Suite, OWASP ZAP, and Nmap. The manual testing techniques included black-box and grey-box testing approaches. The testing was conducted in a controlled environment, and the results were validated by conducting multiple tests.

### Results:

The web application security testing identified a total of 107 vulnerabilities, out of which 3 were classified as high severity, 18 as medium severity, and 86 as low severity. The vulnerabilities were categorized based on their severity level, and the details of the high and medium severity vulnerabilities are provided below.

## High Severity Vulnerabilities:

SQL Injection - SQLite High 03: This vulnerability allows an attacker to execute arbitrary SQL commands in the backend database. The vulnerability was identified in the SQLite database used by the web application.

Cross-site request forgery High 02: This vulnerability allows an attacker to execute unauthorized actions on behalf of a logged-in user. The vulnerability was identified in the web application's authentication mechanism.

Open redirection (DOM-based) High 32: This vulnerability allows an attacker to redirect a user to a malicious website by exploiting the web application's DOM-based redirection mechanism.

## Medium Severity Vulnerabilities:

* Absence of Anti-CSRF Tokens Medium 06: This vulnerability allows an attacker to execute unauthorized actions on behalf of a logged-in user by bypassing the web application's CSRF protection mechanism.

* Cross-Domain Misconfiguration Medium 22: This vulnerability allows an attacker to access sensitive data across different domains by exploiting misconfigured cross-domain policies.

Missing Anti-clickjacking Header Medium 05: This vulnerability allows an attacker to execute clickjacking attacks by exploiting the web application's absence of anti-clickjacking headers.

Vulnerable JS Library Medium 02: This vulnerability allows an attacker to exploit known vulnerabilities in the web application's JavaScript libraries.

XSLT Injection Medium 05: This vulnerability allows an attacker to execute arbitrary code on the web application's server by exploiting the XSLT processor.

Sweet32 Vulnerability Medium 01: This vulnerability allows an attacker to decrypt encrypted data by exploiting the Sweet32 vulnerability in the web application's TLS implementation.

Beast Vulnerability Medium 01: This vulnerability allows an attacker to decrypt encrypted data by exploiting the Beast vulnerability in the web application's TLS implementation.

Lucky Thirteen Vulnerability Medium 01: This vulnerability allows an attacker to decrypt encrypted data by exploiting the Lucky Thirteen vulnerability in the web application's TLS implementation.

Conclusion:
Web application security testing is crucial for identifying and mitigating potential security risks in web applications. The testing results identified various vulnerabilities in the sample web application, including high and medium severity vulnerabilities. The findings of this research paper emphasize the need for web application developers to prioritize security and regularly conduct security testing to ensure the safety of their web applications.

We will prepare a comprehensive report that includes the Common Vulnerabilities and Exposures (CVE) of the identified vulnerabilities, which will be presented to our client to facilitate risk mitigation.
