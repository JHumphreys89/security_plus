---
layout: default
---

# Domain One

**Attacks, Threats, and Vulnerabilities**

_Percentage of Examination_: 24%

***

##### Subdomains

| Subdomain | Description                                                                         |
|:----------|:------------------------------------------------------------------------------------|
| 1.1       | [Compare and contrast different types of social engineering techniques.](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#subdomain-11)              |
| 1.2       | [Given a scenario, analyze potential indicators to determine the type of attack.](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#subdomain-12)     |
| 1.3       | [Given a scenario, analyze potential indicators associated with application attacks.](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#subdomain-13) |
| 1.4       | [Given a scenario, analyze potential indicators associated with network attacks.](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#subdomain-14)     |
| 1.5       | [Explain different threat actors, vectors, and intelligence sources.](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#subdomain-15)                 |
| 1.6       | [Explain the security concerns associated with various types of vulnerabilities.](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#subdomain-16)     |
| 1.7       | [Summarize the techniques used in security assessments.](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#subdomain-17)                              |
| 1.8       | [Explain the technigues used in penetration testing.](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#subdomain-18)                                 |

_Note:_ Terms below marked with an asterisk (*) may not be explicitly included in the SY0-601 exam objectives, but are still important and relative to the course material.

***

## Subdomain 1.1
###### [Top ^](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#top)

_Compare and contrast different types of social engineering techniques._

**The act of gathering info on an attack by taking advantage of the weakest part of security: _people_.**

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/043b34ed-662b-45a2-8509-96599f955597" width="250" height="auto">

#### Phishing

* A form of social engineering where attackers deceive people into revealing senstive information or installing malware such as ransomware.
* Often delivered through email, text, etc.
* Often noticable issues with spelling, fonts, graphics.

#### Smishing

* Phishing via SMS, mass text messages sent to users asking for sensitive information or encouraging them to visit a fake website.
* Spoofing is generally an issue.
* Will receive SMS with unsuspecting link or asks for personal information from the victim.

#### Vishing

* A special type of phishing that uses Voice over IP (VoIP).
* Caller ID spoofing is common in this scenario.
* Calls received can include fake security checks or ask the victim to update personal information for a business or service.

#### Spam

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/0f3713e1-1d52-4ddd-af5f-523d0cccad0f" width="250" height="auto">

* A form of unsolicited messages in the form of email, forums, etc. with various content including commercial advertising, non-commercial proselytizing, and phishing attempts.

#### Spam over instant messaging (SPIM)

* Spam that is delivered through instant messaging.

#### Spear phishing

* A phishing expedition in which the emails are carefully designed to target specific groups or organizations.

#### Dumpster diving

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/a8603975-d235-4c77-990f-49af36e90909" width="250" height="auto">

* Searching the garbage collection area or dustbin to look for non-shredded confidential documents
* Timing can be important - End of month, end of quarter. Based on pickup schedule.
* Protect trash - locks on dumpsters, shred confidential documents. Governments burn documents.

#### Shoulder surfing

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/573f5ac8-6cbf-4d03-a21c-98111429edde" width="250" height="auto">

* This is a social engineering attack in which the attackers obtain confidential information by looking over someone's shoulder to read what is on their computer screen or phone or to observe what they are typing.
* Can be in public areas such as airports and coffee shops.
* Can be done from afar using binoculars or through monitoring webcams.
* Prevent by using privacy filters, keep monitor out of sight, and be aware of your surroundings.

#### Pharming

* Traffic redirection to a Web site that looks identical to the intended website in order to capture the victim's PII/login credentials.
* Difficult for anti-malware to stop as everything seems legit for the unsuspecting users.
* Can use poisoned DNS server or client vulnerabilities.

#### Tailgating

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/74c34cac-7349-4f53-81e2-65a09553c2da" width="250" height="auto">

* Gaining unauthorized access to restricted areas by following another person.
* Most security stops at the border so once inside, there is generally not much to stop the perpetrator.

#### Eliciting information

* The act of extracting information from the victim.
* "Hacking the human,"
* Well-documented psychological techniques.

#### Whaling

* A type of phishing targeted at high-level personnel such as senior executives.
* CFO or other executives targetted through phishing or other methods.
* Executives generally have direct access to corporate banking.

#### Prepending

* An attacker adds a term or phrase to the header of an email to enhance its effectiveness as a social engineering attack.
* Example: https://mmicrosoft.com.

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/1b75a220-bf01-4db7-8634-c05b97a49a9b" width="250" height="auto">

#### Identity fraud

* The use of one person of another person's personal information, without authorization, to commit a crime or to deceive or defraud that other person or a third person.
* Credit fraud - open an account under your name or take your credit card information.
* Bank fraud - opens an account under your name or gains access to your bank acount.
* Loan fraud - Your personal information is used for a loan/lease.
* Government benefits fraud - Attacker claims benefits using your identity.
* Always verify before giving away information to another individual or oragnization. Don't give out passwords or disclose personal details.

#### Invoice scams

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/cc48c948-0d8b-43ad-af83-4c74ed78fd3b" width="250" height="auto">

* When an attacker sends a fake invoice to a business for something such as a domain renewal, toner cartridges, etc., and states the invoice is from the CEO. The business may pay the invoice since it looks like it is coming from a legitimate source.
* Invoice looks like a legitimate one requesting printing services, lawn work, etc.
* Might also include a link to make the payment which the attacker can use to gain payment details.

#### Credential harvesting

* The process of collecting login credentials. May deploy malware on unsuspecting users to achieve goals.
* Macros may download credential-harvesting software through emails containing attachments.
* Victim generally clueless as harvesting happens in the background.

#### Reconnaissance

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/a65c3398-2ff3-42c6-98c3-51954f57f366" width="250" height="auto">

* Gathering information on a victim. Gathers background information to build a believable pretext.

#### Hoax

* A threat that does not actually exist, is often in the form of an email, and still often consumes excessive resources.
* Hoax is often spread through email or social media.
* Some will take your money or waste as much time investigating it as if it were a legitmate issue.
* Spam filters can help
* Cross reference with others de-hoax sources such as hoax-slayer.net.

#### Impersonation

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/9c9df5fb-6eb1-4465-a840-aad465653870" width="250" height="auto">

* An attacker who pretends to be someone else in the hopes of eliciting Personally Identifiable Information (PII).
* May use details gathered from reconnaissance - they know your place of work, bank, etc.
* Attacker may try and be chummy to lower the victim's guard.
* Attacker may also try to act like a superior and pull rank.

#### Watering hole attack

* A malicious attack that is directed toward a small group of specific individuals who visit the same website.
* Site determination may be educated guess such as local eateries or industry related websites.
* Watch the watering hole by using defense-in-depth, deploy firewalls and IPS, ensure anti-malware signature updates are continuously deployed.

#### Typosquating

* A type of URL hijacking where there is a site with URLs that are slightly different from a legitimate source.
* Example: https://microsoftt.com

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/cb4d0ad0-771e-4ca9-afb5-2040ae42af70" width="250" height="auto">

#### Pretexting

* A form of social engineering in which one dividual lies to obtain confidential data about another individual.
* Actor is a character in a scenario they create - "Hello, this is account service with xyz. We want to confirm your banking information..."

#### Influence Campaigns
_Usually nation-state actors that divide, distract, persuade and sway public opinion on policial and social issues._

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/4ac69754-2f73-4c76-93e4-80e6cde15a0a" width="250" height="auto">


##### Hybrid Warfare

* Originally a military strategy - a broad description of techniques to wage war non-traditionally.
* With the dawn of the internet and cyberwarfare, it includes instilling fake news to complete goals such as influencing foreign elections.

##### Social Media

* When a threat actor creates fake accounts, creates content on those fake accounts to seem legitimate, post on social media using these fake accounts, amplify message, real users share the message, and then mass media picks up the story.

#### Principles -reasons for effectiveness
_Principles of Social Engineering and their reasons for effectiveness._

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/436dc6f9-cd28-41f1-962e-02deaeb4f868" width="250" height="auto">

##### Authority

* To impersonate or imply a positon of authority.
* Attacker will impersonate someone such as a police officer or Help Desk employee to try and spoof you into giving away information.

##### Intimidation

* To frighten by threat.
* "If you don't get me the credentials for that server, the whole thing will go down..."

##### Concensus

* Influence a victim by what others do; everyone else does it!
* "Well Bill who works with you did this for me before..."

##### Scarcity

* To describe a lack of something.
* Limited resources or time to act.
* "We need to act before we run out..."

##### Familiarity

* To imply a closer relationship or someone who is well known.
* "Common friends" or someone you know. "Hey it's me, Bill's third cousin Franklin..."

##### Trust

* To assure reliance on their honesty and integrity.
* Gain their confidence, become their friend.
* "I'm from the Help Desk and I'm here to assist..."

##### Urgency

* To call for immediate action.
* Rush the victim, cause them not to think.

***

## Subdomain 1.2
###### [Top ^](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#top)

_Given a scenario, analyze potential indicators to determine the type of attack._

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/58661a85-a298-496b-917d-162071021c9d" width="250" height="auto">

#### Malware
_Malicious software. Intended to damage or disable computers and computer systems._

##### Ransomware

* Type of malware that is designed to block access to a computer system until a sum of money is paid.
* Can spread through phishing email or unknowingly/knowingly infected website.
* May or may not be able to be removed by a security professional without paying the sum of money to the attacker.
* Protect against this threat by keeping backups of your computer, keeping your OS and software patched and up-to-date, and keeping anti-malware signatures up to date.

##### Trojans

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/e204e3fc-effd-4d61-9888-0a14c8e11dc5" width="250" height="auto">

* A type of malware that pretends to be a useful program while secretly performing another function.
* Users may download and install what they believe to be legitimate software without realizing that a Trojan horse will also be installed.
* Circumvents existing security - some may even be built to disable anti-virus software.
* To protect against this threat, don't run unknown software, keep anti-malware signatures up-to-date, and keep backups!

##### Worms

* A self-replicating program or algorithm that consumes system resources and can spread through networks, emails, and messages.
* This form of malware can take over many systems quickly.
* Firewalls and IDS/IPOS can mitigate infestations but can't help much once the worm is on the inside.

1. Infected computer searches for a vulnerable system.
2. Vulnerable computer is exploited.
3. Backdoor is installed and downloads worm.

##### Potentially unwanted Programs (PUPs)

* A form of software that is often unsuspectingly installed with other software and is normally undesirable.
* Examples of this would be an overly agressive browser toolbar, a backup utility that displays ads, or a browser earch engine hijacker.

##### Fileless virus

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/aae6a596-179a-4b81-a76d-b91ff9f3a14e" width="250" height="auto">

* A virus that does not save as a file ont he computer directly; instead, it operates in memory and is never installed.

Example:
1. User clicks on malicious website link.
2. Website exploits a flash/Java/Windows vulnerability.
3. Launches PowerShell and downloads payload in RAM.
4. Runs scripts and executables in memory, exfiltrates data, damages files.
5. Adds an auto-start to registry.

##### Command and control

* A server or computer controlled by an attacker or cybercriminal which is used to send commands to systems compromised by malware and receive stolen data from a target network.
* Many campaigns have been found using cloud-based services, such as webmail and file-sharing service - allows C&C servers to blend in with normal traffic and avoid detection.
* Also serve as the headquarters for compromised machines in a botnet.

##### Bots

* A bot, short for robot, is a type of software application or script that performs automated tasks on command.
* Bots generally perform malicious tasks that allow an attacker to remotely take control over an affected computer.
* Are generally part of a larger entity called a botnet and controlled through a Command and Control server or C&C.

##### Botnet*

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/db1545f2-cdc5-435b-84bb-bac2398ef28d" width="250" height="auto">

* A botnet, short for robot network, is a group of compromised computers or mobile devices connected to a network and managed using a C&C server.
* As they infect newer technologies such as Internet of Things (IoT) devices in homes, public spaces, and secure areas, even more unsuspecting users can be put at risk. This is due to the lack of security on these open-source and generally unprotected devices.
* Compromised devices within a botnet can be controlled to perform a variety of actions, not limited to Distributed Denial of Service (DDoS) attacks, relay spam, proxy network traffic, and other distributed computing tasks.

##### Cryptomalware

* A newer generation of ransomware.
* Where malware encrypts your data files (pictures, documents, movies, music, etc.) Your OS remains available as they want you running, but not working.
* Pay a ransom and your data will be returned.

##### Logic bombs

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/4ea5bffd-d153-49af-a922-56baa42a022f" width="250" height="auto">

* Malicious code objects that infect a system and lie dormant until they are triggered by the occurrence of one or more conditions such as time, program launch, website logon, and so on.
* Difficult to identify and difficult to recover if it goes off.

##### Spyware

* A software application that is secretly placed on a user's system to gather informatin and relay it to outside parties (host machine).
* They are generally difficult to recognize as each is unique and does not have a predefined signature.
* Can be prevented through process and procedures, electronic monitoring such as host-based intrusion detection, and constant monitoring from administrators.

##### Keyloggers

* Malware that capture keystrokes from keyboards.
* Keylogger applications may also capture other input like mouse movement, touchscreen inputs, or credit card swipes from attached devices.

##### Remote Access Trojan (RAT)

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/02570e36-da89-4388-8795-7c651c0bbed9" width="250" height="auto"><br>

* Provides the attacker with remote control of a victim computer and is the most commonly used type of Trojan.
* A remote administration tool; the ultimate backdoor.
* Attacker connects with client software and and then controls the device for keylogging, screen recording or collecting screenshots, copy files, or embed even more malware.
* Don't install unknown software, keep anti-malware signatures updated, and always backup!

##### Rootkit

* A set of software tools that enable an unauthorized user to gain control of a computer without being detected.
* Modifies the core system files; invisible to the OS and traditional anti-virus utilities.
* Make sure to look for the unusual and perform anti-malware scans. Use a remover specific to the rootkit which are normally built after the rootkit is discovered. Secure boot with UEFI which is additional security embeded in the BIOS.

##### Backdoor

* Gives access to a computer, program, or service that circumvents normal security to give program access.
* Often placed on a computer through malware.
* Some software include a backdoor; bad software can have a backdoor as part of the app.

#### Password attacks

_Malicious ways hackers attempt to gain access to an account. A common attack vector used to bypass or exploit authentication of user accounts. Include several different techniques._

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/5dcb6a72-4331-4285-8a59-6d77a7dc20f9" width="250" height="auto">

##### Spraying

* Attack an account with the top three (or more) common passwords - if they don't work, move on to the next account.
* No lockouts, no alarms, no alerts.
* Can be found commonly where the application or admin sets a defaut password for new users.

##### Dictionary

* An attack that compares passwords against common words in a dictionary of words - usually from wordlists that can be found on the internet.
* They can take quite a bit of time but can go on to find the hashes associated with the cracked passwords using this attack.
* Password crackers can substitute letters for numbers or symbols (i.e. pa$$w0rd.)
* Example software: [Cain and Abel](https://en.wikipedia.org/wiki/Cain_and_Abel_(software))

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/84a41f09-3a6f-4a59-ae48-87444151c03e" width="600" height="auto">

##### Brute force

* This type of attack sees the threat actor try every possible password combination until a hash is matched.
* This might take some time - a strong hashing algorithm can slow things down.
* Online: keep trying the login process; very slow as most accounts will lockout after a number of failed attempts.
* Offline: Obtain a list of users and hashes; calculate a password hash, compare to a stored hash. Large computational resource requirement.

##### Rainbow table

* Lists of common passwords and the value they hash to.
* An optimized, pre-built set of hashes that saves time and storage space and contains pre-calculated hash chains.
* Has a remarkable speed increase, especiailly with longer password lengths.

_Example of a rainbow table using MD5 hash._

  | hash_hash                        | hash_id | hash_word |
  |:---------------------------------|:--------|:----------|
  | 0cc175b9c0f1b6a831c399e269772661 | 1       | a         |
  | 92eb5ffee6ae2fec3ad71c777531578f | 2       | b         |
  | 4a8a08f09d37b73795649038408b5f33 | 3       | c         |
  | ...                              | ...     | ...       |
  | 02129bb861061d1a052c592e2dc6b383 | 50      | X         |
  | 57cec4137b614c87cb4e24a3d003a3e0 | 51      | Y         |
  | 21c2e59531c8710156d34a3c30ac81d5 | 52      | Z         |
  

##### Plaintext/unencrypted

* A rare scenario when a threat actor is able to locate passwords stored "in the clear" - no encryption.
* If an application is seen storing passwords as plaintext - get rid of this application!

##### _Note: Regarding Hash and Salt_

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/f6aec42c-fcf0-4d11-9f24-4dde2144a630" width="250" height="auto">

See [subdomain 2.8](https://jhumphreys.github.io/security_plus/domains/domain_two.html)

#### Physical attacks

_A type of security attack that involves the use of physical devices to gain authorized access to a system or network. Can be in many forms, including malicious USB cables, flash drives, skimming, and card cloning._

##### Malicious Universal Serial Bus (USB) cable

* Physical attack where a seemingly harmless USB cable has additional electronics inside to pose as a keyboard/mouse or other Human Interface Device (HID)
* Once connected, the cable takes over and installs malicious software.
* Can be prevented by only using trusted hardware.

##### Malicious flash drive

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/d6532ee6-cd4a-4f79-83b0-13c9790dbe0c" width="250" height="auto">

* Physical attack where a flash drive is loaded with malicious files (MS Office docs, PDF files) and documents or acts as a HID (Human Interface Device) or another device such as an Ethernet adapter in order to hijack information.
* Older operating systems would just run the drive automatically - this is no longer the case.
* Can be prevented by only using trusted flash drives.

##### Card cloning

* Physical attack where card details are compromised and placed on a duplicate card, often included with the printed CVC (Card Validation Code).
* The card magnetic stripe is duplicated but the chip cannot be cloned.
* Card details are generalling cloned by a skimmer.
* Cloning gift cards are common as they use magnetic stripe technology.

##### Skimming

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/6a2104b9-7aa0-4333-9c40-4b8e2e2d6d3c" width="250" height="auto">

* Physical attack where a device is installed over hardware that reads credit or debit cards and captures the information from the cards magnetic swipe - card number, expiration date, card holder's name.
* May also be used in conjunction with a camera to record PIN information.
* Always physically check before using card readers or ATM terminals.

#### Adversarial artificial intelligence (AI)

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/68b3bc93-9555-47c9-8e31-f0a0830af538" width="250" height="auto">

* Machine learing: Computers identify patterns in data which in turn further improve their predictions. This requires an ample and continuous quantity of training data. It's in use everyday in a variety of products including email (anti-spam), websites (recommend products), and prevent car accidents (automatic breaks, self-driving).
* Poisoning of the training data: Confuse AI. Attackers can feed the AI mofidied training data to cause it to behave incorrectly.
* Evasion attacks: AI only as good as training data and attackers will find holes and limitations. AI that may be trained to fight spam may have an attacker try words that the AI does not treat as bad and allow through.
* Secure: Check and crosscheck training data. Constantly retrain the AI with new data, more data. Train the AI with the poisoned data - let the AI know what it is up against.

##### Tainted training data for machine learning (ML)

* When attackers send modifying training data that cuases the AI to behave incorrectly - confuse the artificial intelligence.

##### Security of machine learning algorithms

* Actions to take to constantly retrain, cross check, and verify AI training data with new data, more data, and better data to prevent AI poisoning.
* It may also be plausible to train the AI with possible poisoning data so the AI knows what to look out for.

#### Supply-chain attacks

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/3ed4e5e4-91d8-46a0-8b27-11379c25bdb5" width="250" height="auto">

* Attacks that focus on weaker links in an organization's supply chain.
* An attacker will find an exploit to infect the entire chain through a third-party supplier.
* People trust their suppliers...

#### Cloud-based vs. on-premises attacks

* Attackers want data no matter where it is.
* When it comes to cloud-based security, it is centalized and can cost less as it requires no dedicated hardware or data center to secure - a third-party handles that.
* With on-premises, the security burden is placed on the client and requires data center securty and infrastructure costs.

#### Cryptographic attacks

_You now have encrypted the data and sent it to another person - is it secure? These attacks focus on finding ways to undo security and locate cryptographic shortcomings._

##### Birthday

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/df441d29-269c-481b-9b28-3002f88c8271" width="250" height="auto">

* This attack will generate multiple versions of plaintext to match the hashes and find collision through bruteforce.
* Exploits the mathematics behind the [birthday problem in probability theory](https://en.wikipedia.org/wiki/Birthday_attack). This problem asks for the probability that, in a set of _n_ randomly chosen people, at least two will share a birthday.
* You can help protect yourself by using a large hash output size. 🧂

##### Collision

* Hash digests are _supposed_ to be unique, and different input data should never create the same hash.
* However, with previous hashing algorithms there is a cryptographic attack that exploits collisions in these hashes.
* Example: [SHAttered attack](https://debugpointer.com/security/collision-attack#:~:text=Perhaps%20one%20of%20the%20most%20well-known%20examples%20of,expedited%20the%20move%20towards%20more%20secure%20hash%20functions.). Researchers were able to find a collision in the SHA-1 hash function. This quickly led to an expedited move towards more secure hash functions.

##### Downgrade

* An attack that forces a system to rollback it's security in order to carry out an exploit.
* An [example of this flaw was](https://en.wikipedia.org/wiki/Downgrade_attack) found in OpenSSL that allowed the attacker to negotiate down to a lower version of TLS between the client and server. This is the is on of the most common types of downgrade attacks.

***

## Subdomain 1.3
###### [Top ^](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#top)

_Given a scenario, analyze potential indicators associated with application attacks._

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/3172a855-ee3f-46b5-b63d-7e02f536698b" width="250" height="auto">

#### Privilege escalation

* Gaining access to files you should not have permission to on a valid account via exploition of a vulnerability.
* Usually access is of highest level and is of great concern.
* Can include horizontal privilege escalation where an attacker gets access to another credential on the network with higher privileges than the initial one used to gain their foothold.
* Make sure to patch software and OS as well as ensure anti-malware signatures are up to date. Also practice Data execution prevention.

#### Cross-site scripting (XSS)

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/ce8cfb58-9f90-487c-9c52-3ee2f3d1f5a2" width="250" height="auto">

* XSS is an injection vulnerability that occurs when an attacker can insert unauthorized JavaScript, VBScript, HTML, or other active content into a webpage.
* When other users view the page, the malicious code executes and affects or attacks the user.
* Malicious script can hijack the user's session, submit unauthorized transactions on the user's behalf, steal confidential information, or deface the page.
* Example:
  1. https://fakewebsite.com/status?message=All+is+well.
  2. Application receives data in an HTTP request that includes data within the immediate response in an unsafe way. Response contains the following HTML code:
     
     ```html
     <p>Status: All is well.</p>
     ```
     
  3. An attack can craft a URL that includes malicious JavaScript code in the message parameter, which will be executed by the victim's broswer when they visit the URL

#### Injections

_A process where an attacker supplies untrusted input to a program, which gets processed by an interpreter as part of a command or query._

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/78d99c83-636c-475e-a845-b8dcc829ee84" width="250" height="auto">

##### Structured query language (SQL)

* Web security vulerability that allows an attacker to interfere with the queries that an application makes to its database.
* Attacker injects malicious SQL code into the applications input fields, which can then be executed by the database.
* Can lead to unauthorized access to sensitive data, data loss, or even complete system compromise.
* Example:
  1. Suppose a web app uses an SQL database to store user info. The application has a login page that accepts a username and password. SQL query to authenticate the user might look like this:
     
     ```sql
     SELECT * FROM users WHERE username = 'username' AND password = 'password'
     ```
     
  2. An attacker can exploit this by entering the following string as the username:
     
     ```sql
     ' OR 1=1 --
     ```
  3. This will modify the SQL query to look like this:

     ```sql
     SELECT * FROM users WHERE username = ' ' OR 1=1 --' AND password = 'password'
     ```
     
  4. The `--` at the end of the string is used to comment out the rest of the original query. The modified query will return all rows from the `users` table, effectively bypassing authentication.
  
##### Dynamic-link library (DLL)

* A techique used for running code withi the address space of another process by forcing it to load a dynamic-link library.
* DLL injection is often used by external programs to influence the behavior of another program in a way it's authors did not anticipate or intend.
* Example of a simple injection in C++:

  ```c++
  #include <windows.h>
  #include <stdio.h>

  int main(int argc, char **argv) {
    if (argc != 3) {
        printf("Usage: %s <PID> <DLL_PATH>\n", argv[0]);
        return 1; }

    DWORD pid = atoi(argv[1]);
    HANDLE hProcess = OpenProcess(PROCESS_ALL_ACCESS, FALSE, pid);
    if (!hProcess) {
        printf("Failed to open process %d\n", pid);
        return 1;
    }

    LPVOID lpRemoteString = VirtualAllocEx(hProcess, NULL, strlen(argv[2]) + 1, MEM_COMMIT, PAGE_READWRITE);
    if (!lpRemoteString) {
        printf("Failed to allocate memory in remote process\n");
        return 1;
    }

    if (!WriteProcessMemory(hProcess, lpRemoteString, argv[2], strlen(argv[2]) + 1, NULL)) {
        printf("Failed to write memory in remote process\n");
        return 1;
    }

    HMODULE hKernel32 = GetModuleHandle("kernel32.dll");
    FARPROC pLoadLibraryA = GetProcAddress(hKernel32, "LoadLibraryA");

    HANDLE hThread = CreateRemoteThread(hProcess, NULL, 0,
                                         (LPTHREAD_START_ROUTINE)pLoadLibraryA,
                                         lpRemoteString,
                                         0,
                                         NULL);
    if (!hThread) {
        printf("Failed to create remote thread\n");
        return 1;
    }

    WaitForSingleObject(hThread, INFINITE);

    VirtualFreeEx(hProcess, lpRemoteString, strlen(argv[2]) + 1, MEM_RELEASE);
    CloseHandle(hThread);
    CloseHandle(hProcess);

    return 0; }
  ```

##### Lightweight Directory Access Protocol (LDAP)

* A technique used to exploit web applications which could reveal senstive information or modify information represented in the LDAP data stores.
* It exploits a vulnerability in an application by manipulating input parameters passed to internal search, add or modify functions.
* When an application fails to properly sanitize user input, it is possible for an attacker to modify a statement.
* Example:
  1. Suppose an application uses the fllowing LDAP query to authenticate a user:

  ```ldap
  (&(uid=admin)(userPassword=pass))
  ```

  2. An attacker could inject malicious code into the query by entering the following string as the username:
 
  ```ldap
  *)(uid=*))(|(uid=*
  ```

  3. This would result in the folowing LDAP query:
 
  ```ldap
  (&(uid=*)(uid=*))(|(uid=*)(userPassword=pass))
  ```

  4. An attacker could then use this query to bypass authentication and gain access to sensitive data.

##### Extensible Markup Language (XML)



#### Pointer/object deference



#### Directory traversal



#### Buffer overflows



#### Race conditions



##### Time of check/time of use



#### Error handling



#### Improper input handling



#### Replay attack



##### Session replays



#### Integer overflow



#### Request forgeries



##### Server-side



##### Cross-site



#### Application programming interface (API) attacks



##### Resource exhaustion



#### Memory leak



#### Secure Socks Layer (SSL) stripping



#### Driver manipulation



##### Shimming



##### Refactoring



#### Pass the hash

***

## Subdomain 1.4
###### [Top ^](https://jhumphreys89.github.io/security_plus/domains/domain_one.html#top)

_Given a scenario, analyze potential indicators associated with network attacks_

<img src="https://github.com/JHumphreys89/security_plus/assets/115595085/add4d9a2-9e4d-4816-b017-c32774f780ad" width="250" height="auto">

***

# Study Cards

* [Subdomain 1.1](../resources/study_cards/sub_one_one.html)
* [Subdomain 1.2](../resources/study_cards/sub_one_two.html)
* [Subdomain 1.3](../resources/study_cards/sub_one_three.html)
* [Subdomain 1.4](../resources/study_cards/sub_one_four.html)
* [Subdomain 1.5](../resources/study_cards/sub_one_five.html)
* [Subdomain 1.6](../resources/study_cards/sub_one_six.html)
* [Subdomain 1.7](../resources/study_cards/sub_one_seven.html)
* [Subdomain 1.8](../resources/study_cards/sub_one_eight.html)
