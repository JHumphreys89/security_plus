---
layout: default
---

[Back to Home](../../index.html) \| [Back to Domain One](../domain_one.html)

# Subdomain 1.8

_Explain the techniques used in penetration testing._

_Terms_: 22

***

#### Penetration testing

* Pentest: simulate an attack.
* Similar to vulnerability scanning except we actually try to exploit the vulnerabilities.
* Often a compliance mandate.

##### Known environment

* White box. Tester have full knowledge of the environment prior to testing.
* Full disclosure

##### Unknown environment

* Black box. The pentester knows nothing about the systems under attack.
* Otherwise known as a 'blind' test.

##### Partially known environment

* Gray box. A mix of known and unknown with a focus on certain systems or applications.

##### Rules of engagement

* An important document; written consent that outlines the boundaries of the test.
* Includes the type of testing as well as schedule.
* Includes the rules:
     - IP address ranges
     - Emergency contacts
     - How to handle sensitive information
     - In-scope and out-of-scope devices or applications.

##### Lateral movement

* Refers to the way a tester moves from system to system throughout the network from the initially targeted system.
* The inside of the system is relatively unprotected.

##### Privilege escalation

* Gain more privileges on the network.

##### Persistence

* The ability to maintain presence in a network for an extended period of time without being detected.
* Commonly achieved by creating backdoor, build user accounts, change or verify default passwords.

##### Cleanup

* Last step in a pen test, including removal of all traces of the pen test activities.
     - Leave the network in its original state.
     - Remove any binaries or temp files.
     - Remove any backdoors.
     - Delete user accounts created during the test.

##### Bug bounty

* A reward for discovering vulnerabilities.
* Earn money for hacking a system.
* Document the vulnerability to earn cash.

##### Pivoting

* Process of using various tools to gain additional information using the exploited system.

#### Passive and active reconnaissance

* Passive: a type of network recon technique used to collect information about a target system or network without directly interacting with the system or network.
* Active: involves actively probing a network with the intent of gathering information about the target.

##### Drones
 
 * An alternative to flying in plane to look for wireless networks.

##### War flying

* Same as driving, except performed while flying an aircraft.
* Combine Wi-Fi monitoring and a GPS.

##### War driving

* Practice of looking for a wireless network.
* Includes free tools such as:
     - Kismet, inSSIDer, Wireless Geographic, and Logging Engine.

##### Footprinting

* Recon. The tester attempts to learn as much about the network both actively and passively.

##### OSINT

* Open Source INTelligence.
* Gathering information from many open sources such as find information on anyone or anything, or if the name is not related to open-source software.
* [Data is everywhere](https://osintframework.com/).
* Automated gathering with many software tools available.

#### Exercise types

* Simulated cyber attack on a computer system to identify vulnerabilities and assess the security of the system.
* Usually conducted by a team of security professionals who are authorized to perform the exercise and can be divided into multiple groups.
* The teams:
     - Red team
     - Blue team
     - Purple team
     - White team

##### Red-team

* _Offense_ - hired attackers.
* Goal is to find as many vulnerabilities as possible and exploit them to gain access to sensitive data or systems:
     - Uses ethical hacking to find security holes.
     - Exploit vulnerabilities to gain access.
     - Use social engineering.
     - Web application scanning.

##### Blue-team

* _Defense_ - Protect the data.
* Use various techniques to detect and prevent the attack with the goal of identifying and fixing vulnerabilities before they can be exploited by the red team:
     - Ops - daily security tasks.
     - Incident response - damage control.
     - Threat hunting - find and fix the holes.
     - Digital forensics - find data everywhere.

##### White-team

* _Not on a side._
* Is similar to a referee:
     - Enforces rules.
     - Resolves any issues.
     - Determines the score.
     - Manages post-event assessments such as lessons learned and results.

##### Purple-team

* _Offense and defense_ - working together.
* Goal is to improve communication and collaboration between the two teams:
     - Deploy apps and data securely - everyone is on board.
     - Create a feedback loop where red informs blue and vice versa.
     - Cooperate instead of compete. Internal battles can stile org. security.

***

# Demonstrate Your Understanding

[Back to Top](#top) \| [Study in a New Tab](../../resources/study_cards/sub_one_eight.html){:target="_blank"}

_Click or tap on 'Choose a Study Mode' to switch between flash cards, match, learn, test and more._

<iframe src="https://quizlet.com/844437883/flashcards/embed?i=35mna1&x=1jj1" height="500" width="100%" style="border:0"></iframe>