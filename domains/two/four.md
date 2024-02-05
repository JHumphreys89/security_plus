---
layout: default
---

[Back to Home](../../index.html) \| [Back to Domain Two](../domain_two.html)

# Subdomain 2.4

_Summarize authentication and authorization design concepts._

_Terms_: 35

***

#### Authentication Methods

_The process of verifying the identity of a user, device, or system. It is a crucial component of information security that helps prevent unauthorized access to sensitive data and resources._

##### Directory Services

<img class="subdo-img" src="../../assets/images/2.4/img1.png" width="250" height="auto">

* Keeps all of an organization's usernames and passwords into a single database - also contains computers, printers, and other devices.
* Think [Active Directory](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview).
* Large distributed database that is constantly replicated.
* All authentication requests reference this directory. Each user only needs one set of credentials. One username and password for all services.
* Access via Kerberos or LDAP.

##### Federation

<img class="subdo-img" src="../../assets/images/2.4/img2.png" width="250" height="auto">

* Provide network access to others. Not just employees - Partners, suppliers, customers, etc. Provides SSO and more.
* [Third-parties](https://auth0.com/) are able to establish a federated network. Authenticate and authorize between the two organizations.
* Login with your [Facebook](https://learn.microsoft.com/en-us/entra/external-id/facebook-federation) credentials.
* The third-parties must establish a trust relationship and the degree of the trust.

##### Attestation

* 

##### Technologies

* 

###### Time-Based One-Time Password (TOTP)

* 

###### HMAC-Based One-Time Password (HOTP)

* 

###### Short Message Service (SMS)

* 

###### Token Key

* 

###### Static Codes

* 

###### Authentication Applications

* 

###### Push Notifications

* 

###### Phone Call

* 

##### Smart Card Authentication

* 

#### Biometrics

* 

##### Fingerprint

* 

##### Retina

* 

##### Iris

* 

##### Facial

* 

##### Voice

* 

##### Vein

* 

##### Gait Analysis

* 

##### Efficacy Rates

* 

##### False Acceptance

* 

##### False Rejection

* 

##### Crossover Error Rate

* 

#### Multifactor Authentication (MFA) Factors and Attributes

* 

##### Factors

* 

###### Something You Know

* 

###### Something You Have

* 

###### Something You Are

* 

##### Attributes

* 

###### Somewhere You Are

* 

###### Something You Can Do

* 

###### Something You Exhibit

* 

###### Someone You Know

* 

#### Authentication, Authorization, and Accounting (AAA)

* 

#### Cloud Vs. On-Premises Requirements

* 

***

# Demonstrate Your Understanding

[Back to Top](#top) \| [Study in a New Tab](../../resources/study_cards/sub_two_four.html){:target="_blank"}

_Click or tap on 'Choose a Study Mode' to switch between flash cards, match, learn, test and more._

<iframe src="https://quizlet.com/845859226/flashcards/embed?i=35mna1&x=1jj1" height="500" width="100%" style="border:0"></iframe>