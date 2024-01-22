---
layout: default
---

[Back to Home](../../index.html) \| [Back to Domain One](../domain_two.html)

# Subdomain 2.1

_Explain the importance of security concepts in an enterprise environment._

_Terms_: 30

***

#### Configuration Management

* Only constant is change - OS, patches, app updates, network modifications, etc.
* Identify and document hardware and software changes. Manage the security when changes occur.
* Rebuild systems in the event a disaster occurs; documentation and processes will be critical.

##### Diagrams

* Includes network diagrams to document the physical wire and device.
* Physical data center layout which can include physical rack locations.
* Device diagrams such as individual cabling.

##### Baseline Configuration

* Provide known, secure starting points for systems.
* Security for an app environment should be well defined:
     - All instances must follow this baseline.
     - Firewall settings, patch levels, OS file versions.
     - May require constant updates.
* Integrity measurements check for secure baseline, should be performed often, check against well-documented baselines and failures require immediate correction.

##### Standard Naming Conventions

* Create a standard which needs to be easily understood by everyone.
* For devices:
     - Asset tag names and numbers.
     - Computer names including location or region.
     - Serial numbers.
* Networks - use port labeling.
* For domain configs have user account names and standard email addresses.

##### Internet Protocol (IP) Schema

* An IP address plan or model which helps avoid duplicate IP addressing and provides consistent addressing for network devices.
* Locations: number of subnets, hosts per subnet.
* IP ranges: different sites have a different subnet - 10.1.x.x/24, 10.2.x.x/24, 10.3.x.x/24.
* Reserved addresses for things such as users, printers, routers/default gateways.

#### Data Sovereignty

* Data that resides in a country is subject to the laws of said country. i.e. legal monitoring, court orders, etc.
* Laws may prohibit where data is stored such as data collected on EU citizens must be stored in the EU. GDPR (General Protection Regulation).
* Where is your data stored? Your compliance laws may prohibit moving data out of the country.

#### Data Protection

_Refers to the measures taken to safeguard data from unauthorized access, theft, corruption, or loss._

##### Data Loss Prevention (DLP)

* Controls use of removable media. 
* Examines outgoing data and detects unauthorized data transfers.

##### Masking

* Data obfuscation - hide some of the original data.
* Protects PII and other sensitive data.
* The data may still be intact in storage and may only be hidden from view. Control the view based on permissions.
* Can include many different techniques such as substituting, shuffling, encrypting, masking out, etc.

##### Encryption

* Encode info into unreadable data. Original information is plaintext, encrypted form is ciphertext.
* This is a two way street; convert between one and the other if you have the proper key.
* Confusion - the encrypted data is drastically different than the plaintext.
* Diffusion - Change one character of the input, and many characters change of the output.

##### At Rest

* The data is on a storage device such as a hard drive, SSD, flash drive, etc.
* Encrypt the data with whole disk encryption, database encryption, or file- or folder-level encryption.
* Apply permissions with access control lists. Only authorized users can access the data.

##### In Transit/Motion

* Data transmitted over the network - also called data in-motion.
* Not much protection **_as it travels_**... many different switches, routers, devices.
* Network based protection such as firewall and IPS.
* Provide transport encryption with TLS (Transport Layer Security) and IPsec (Internet Protocol Security.)

##### In Processing

* Data in-use. Data is actively processing in memory - system RAM, CPU registers and cache.
* The data is almost always decrypted otherwise you couldn't do anything with it.
* The attackers can pick the decrypted information out of RAM - a very attractive option.

##### Tokenization

* Replace sensitive data with a non-sensitive placeholder - SSN 123-45-6789 is now 652-46-7742.
* Common with credit card processing (chip).
* This is **not** encryption or hashing. The original data and token are not mathematically related and no encryption overhead.

##### Rights Management

* Information Rights Management (IRM). Control how data is used - Microsoft Office documents, email messages, PDFs.
* Restrict data access to unauthorized persons. Prevent copy and paste, control screenshots, manage printing, restrict editing, etc.
* Each user has their own set of rights. Attackers have limited options.

#### Geographical Considerations

*  

#### Response and Recovery Controls

* 

#### Secure Sockets Layer (SSL)/Transport Layer Security (TLS) Inspection

* 

#### Hashing

* 

#### API Considerations

* 

#### Site Resiliency

__

##### Hot Site

* 

##### Cold Site

* 

##### Warm Site

* 

#### Deception and Disruption

__

##### Honeypots

* 

##### Honeyfiles

* 

##### Honeynets

* 

##### Fake Telemetry

* 

##### DNS Sinkhole

* 

***

# Demonstrate Your Understanding

[Back to Top](#top) \| [Study in a New Tab](../../resources/study_cards/sub_two_one.html){:target="_blank"}

_Click or tap on 'Choose a Study Mode' to switch between flash cards, match, learn, test and more._

<iframe src="https://quizlet.com/845023754/flashcards/embed?i=35mna1&x=1jj1" height="500" width="100%" style="border:0"></iframe>