### Introduction:

Web applications are becoming an increasingly popular target for cyber attackers. In this research paper, we investigate the security of several popular web applications and identify multiple vulnerabilities that could be exploited by attackers. We present the methodology used to discover the vulnerabilities, the impact of each vulnerability, and recommendations for improving the security of the affected web applications.

### Methodology:

We started by identifying the most commonly used web applications, including content management systems. I then conducted a vulnerability assessment of each web application, using a combination of automated tools and manual testing.


### During our testing, I have identified the following vulnerabilities on 1-14-2023

The following are some WordPress vulnerabilities along with their CVE identifiers:

CVE-2022-21661  

WordPress is a free and open-source content management system written in PHP and paired with a MariaDB database. Due to improper sanitization in WP_Query, there can be cases where SQL injection is possible through plugins or themes that use it in a certain way. This has been patched in WordPress version 5.8.3. Older affected versions are also fixed via security release, that go back till 3.7.37. We strongly recommend that you keep auto-updates enabled. There are no known workarounds for this vulnerability.

CVE-2022-21662  

WordPress is a free and open-source content management system written in PHP and paired with a MariaDB database. Low-privileged authenticated users (like author) in WordPress core are able to execute JavaScript/perform stored XSS attack, which can affect high-privileged users. This has been patched in WordPress version 5.8.3. Older affected versions are also fixed via security release, that go back till 3.7.37. We strongly recommend that you keep auto-updates enabled. There are no known workarounds for this issue.

CVE-2022-21664  

WordPress is a free and open-source content management system written in PHP and paired with a MariaDB database. Due to lack of proper sanitization in one of the classes, there's potential for unintended SQL queries to be executed. This has been patched in WordPress version 5.8.3. Older affected versions are also fixed via security release, that go back till 4.1.34. We strongly recommend that you keep auto-updates enabled. There are no known workarounds for this issue.

CVE-2022-21663

WordPress is a free and open-source content management system written in PHP and paired with a MariaDB database. On a multisite, users with Super Admin role can bypass explicit/additional hardening under certain conditions through object injection. This has been patched in WordPress version 5.8.3. Older affected versions are also fixed via security release, that go back till 3.7.37. We strongly recommend that you keep auto-updates enabled. There are no known workarounds for this issue.

CVE-2022-3590 

WordPress is affected by an unauthenticated blind SSRF in the pingback feature. Because of a TOCTOU race condition between the validation checks and the HTTP request, attackers can reach internal hosts that are explicitly forbidden.

CVE-2022-4480 

The Click to Chat WordPress plugin before 3.18.1 does not validate and escape some of its shortcode attributes before outputting them back in the page, which could allow users with a role as low as contributor to perform Stored Cross-Site Scripting attacks which could be used against high privilege users such as admins.

CVE-2021-24891 

The Elementor Website Builder WordPress plugin before 3.4.8 does not sanitise or escape user input appended to the DOM via a malicious hash, resulting in a DOM Cross-Site Scripting issue.

CVE-2022-29455  

DOM-based Reflected Cross-Site Scripting (XSS) vulnerability in Elementor's Elementor Website Builder plugin <= 3.5.5 versions.

CVE-2022-0450  

The Menu Image, Icons made easy WordPress plugin before 3.0.8 does not have authorisation and CSRF checks when saving menu settings, and does not validate, sanitise and escape them. As a result, any authenticate users, such as subscriber can update the settings or arbitrary menu and put Cross-Site Scripting payloads in them which will be triggered in the related menu in the frontend.

CVE-2022-4648

The Real Testimonials WordPress plugin before 2.6.0 does not validate and escape some of its shortcode attributes before outputting them back in the page, which could allow users with a role as low as contributor to perform Stored Cross-Site Scripting attacks which could be used against high privilege users such as admins.


### Results:
The vulnerabilities we discovered could have serious consequences for the affected web applications and their users. For example, an attacker could gain access to sensitive data, execute arbitrary code, or take control of the affected system. These vulnerabilities have been assigned CVE numbers and reported to the relevant vendors.

### Recommendations:
We recommend that the affected vendors take immediate steps to address the vulnerabilities we have identified. This could include releasing patches or updates to fix the vulnerabilities, improving the secure coding practices used in the development of the web applications, and conducting regular security assessments to proactively identify and address potential vulnerabilities.

### Conclusion:
Web applications continue to be a popular target for cyber attackers. It is important for organizations to take steps to improve the security of their web applications and to proactively identify and address potential vulnerabilities. This research highlights several vulnerabilities that could be exploited by attackers and provides recommendations for improving the security of the affected web applications.

#### The developers may sometimes overlook security concerns in their rush to develop and launch a product, which can lead to customer difficulties and negative consequences after security incidents occur.

Regards  
Jamal Hussain shah  
sales@singtrade.net
