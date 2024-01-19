---
layout: default
---

[Back to Home](../../index.html) \| [Back to Domain One](../domain_one.html)

# Subdomain 1.7

_Summarize the techniques used in security assessments._

_Terms_: 26

***

#### Threat Hunting

_The constant game of cat and mouse; find the attacker before they find you._

_Cybersecurity technique designed to detect the presence of threats that have not been discovered by normal security monitoring._

##### Intelligence Fusion

* Combines threat data to create a big picture of threats and risks.
* Fuse the security data together with big data analytics; collect through logs and sensors, network information, internet events, and intrusion detection.

##### Threat Feeds

* Cybersecurity data feeds that provide information on the latest threats.

##### Advisories and Bulletins

* Sources of data such as the US Computer Emergency Readiness Team (US-CERT) that maintains the National Cyber Awareness System.

##### Maneuver

* Attackers getting around a network by using Tactics, Techniques and Procedures (TTPs). By analyzing TTPs, a security analyst can predict an attackers movements.

#### Vulnerability Scans

* Usually non-invasive unlike penetration tests.
* Can include port scans; poke around and see what is open.
* Tests from the outside as well as the inside.

##### False Positives

* A vulnerability is identified that doesn't actually exist.
* It is real, but may not be the highest priority issue.

##### False Negatives

* A vulnerability exists but you weren't able to detect it.
* Make sure to update the latest signatures.
* Work with the vulnerability detection manufacturer; they might need to update their signatures...

##### Log Reviews

* Admins must perform log reviews of scan outputs periodically.
* Check for lack of security controls such as no firewall, no anti-virus, no anti-spyware
* Misconfigurations such as guest access or open shares.

##### Credentialed vs. Non-Credentialed

* Credentialed: You are a normal user - emulates an insider attack.
* Non-Credentialed: The scanner cannot login to the remote device.

##### Intrusive vs. Non-Intrusive

* Non-intrusive: gather information, don't try to exploit a vulnerability.
* Intrusive: You'll try out the vulnerability to see if it works.

##### Application

* Scans for vulnerabilities on desktop and mobile applications.


##### Web Application

* Scans for vulnerabilities on web servers.


##### Network

* Gather information about hosts within a network.
* Misconfigured firewalls, open ports, vulnerable devices.
* May include
     - ARP ping scan
     - SYN stealth scan
     - Port scan
     - Service scan
     - OS detection

##### Common Vulnerabilities and Exposures (CVE)/Common Vulnerability Scoring System (CVSS)

* Maintained by MITRE Corp., CVE is a dictionary of known security vulnerabilities and exposures.
* CVSS assesses vulnerabilities and assigns severity scores, 0 to 10, with 10 being the most severe.

##### Configuration Review

* Validate the security of device configurations including workspaces, servers, security devices, and more.
* Configuration compliance scanners perform a configuration review of systems to verify they are configured correctly, by using a baseline file for configuration validation.

#### Syslog/Security Information and Event Management (SIEM)

_Provides centralized solutions for collecting, analyzing, and managing data from multiple sources._


##### Review Reports

* An alert or report from a trigger.
* SIEMs include built-in reports,grouped in different event categories such as network traffic, device, threat, logon/logoff, compliance with specific laws.

##### Packet Capture

* Captures packets (packet sniffers) to monitor network traffic that can alert the system and start an investigation.

##### Data Inputs

* Data that comes from web servers, proxy server, and database servers.

##### User Behavior Analysis

* Can follow the behavior of a user and report on anything suspicious.
* Detect insider threats, identify targeted attacks, and catches what the SIEM and DLP systems might miss.


##### Sentiment Analysis

* Analyzing text using AI to detect unwanted user opinion or emotion.
* Public discourse correlates to real-world behavior. If they hate you = they will hack you.
* Social media may be a gauge for this.

##### Security Monitoring

* SIEMs come with predefined alerts and continuously monitor systems.

##### Log Aggregation

* Combining logs together, even if they are in different formats to make search and analysis easier.

##### Log Collectors

* Collect log data from various sources such as firewalls, routes, NIDS/NIPS.

#### Security Orchestration, Automation, and Response (SOAR)

* Platform that combines tools that work together to response to low-level security events automatically to free up time from administrators so they can focus on other tasks.
* Firewalls, account management, email filters, etc.
* Automation - handle security tasks automatically.
* Response - make changes _immediately_.

***

# Demonstrate Your Understanding

[Back to Top](#top) \| [Study in a New Tab](../../resources/study_cards/sub_one_seven.html){:target="_blank"}

_Click or tap on 'Choose a Study Mode' to switch between flash cards, match, learn, test and more._

<iframe src="https://quizlet.com/844145758/flashcards/embed?i=35mna1&x=1jj1" height="500" width="100%" style="border:0"></iframe>