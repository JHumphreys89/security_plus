---
layout: default
---

[Back to Home](../../index.html) \| [Back to Domain Two](../domain_two.html)

# Subdomain 2.3

_Summarize secure application development, deployment, and automation concepts._

_Terms_: 32

***

#### Environment

_The different stages of the application lifecycle, such as development, test, staging, production and quality assurance. Each environment has its own security requirements and challenges._

##### Development

* Developers will begin writing code in a secure environment, usually a sandbox.
* Sandboxing is an isolated test environment, usually with no connection to the internet or other computers. Used during the development process to try code, break code without any repercussions to the production environment as the sandboxing environment is segregated.

##### Test

* Still in the development stage.
* Functional testing to make sure it all works together.

##### Staging

* Close to rollout and works and feels exactly like the production environment.
* Working with a copy of production data.
* Run performance testing and test usability and features.

##### Production

* Application is now live and rolled out to the user community.
* There can be logistical challenges in this environment such as new servers, new software, and restart or interruption of service during implementation process.

##### Quality Assurance (QA)

* Verifies that features are working as expected and validates new functionality as well as making sure old errors do not appear.

#### Provisioning and Deprovisioning

* Provisioning:
     - Deploy an application - web server, database server, middleware server, user workstation configurations, certificate updates, etc.
     - Application software security - operating system, application.
     - Network security - secure VLAN, internal access, external access.
     - Software deployed to workstations - check executables for malicious code, verify security posture of the workstation.
* Deprovisioning:
     - Dismantling and removing an app instance.
     - Security deprovisioning is important - don't leave open holes, don't close important ones.
     - Firewall policies must be reverted. If the application is gone, so is the access.

#### Integrity Measurement

* Check for the secure baseline.
* These should be performed often.
* Check against well-documented baselines.
* Failure requires an immediate correction.

#### Secure Coding Techniques

_Are a set of practices that developers use to keep their code secure. By using these techniques, developers can create applications that are less vulnerable to attacks and more secure for users._

##### Normalization

* Checking and correcting all input.
* For instance, a zip code should only be 5 characters long, phone numbers should be 10 characters long, etc.

##### Stored Procedures

* SQL databases - client sends detailed requests for data. `Select * FROM wp_options WHERE option_id = 1`.
* Client requests can be complex and sometimes modified by the user.
* Stored procedures limit the client interactions. `CALL get_options`. That is it. No modifications to the query are possible.
* To be more secure, use only stored procedures. The application does not use any SQL queries.

##### Obfuscation/Camouflage

* Obfuscate: to Make something normally understandable very difficult to understand. Take perfectly readable code and turn it into nonsense. The developer keeps the readable code and gives you the chicken scratch. Both sets of code perform exactly the same way.
* Helps prevent the search for security holes. Makes it more difficult to figure out what is happening - but not _impossible_.

##### Code Reuse/Dead Code

* Code reuse:
     - Use old code to build new applications. Copy + paste.
     - If the old code has security vulnerabilities, reusing the code spreads it to other apps. You are making this much more difficult for everyone.
* Dead code:
     - Calculations are made, code is executed, results are tallied.
     - The results are not used anywhere else in the app.
     - All code is an opportunity for a security problem. Make sure that your code is as alive as possible.

##### Server-Side vs. Client-Side Execution + Validation

* Server-side validation:
     - All checks occur on the server.
     - Helps protect against malicious users.
     - Attackers may not even be using your interface.
* Client-side validation:
     - The end-user's app makes the validation decisions.
     - Can filter legitimate input from genuine users.
     - May provide additional speed to the user.
* Use both - but especially server-side validation.

##### Memory Management

* Never trust data input as malicious users can attempt to circumvent your code.
* Buffer overflows are a huge security risk - make sure your data matches your buffer sizes.
* Some built-in functions are insecure. Use best practices when designing your code.

##### Use of Third-Party Libraries and Software Development Kits (SDKs)

* Extend the functionality of a programming language.
* Security risk:
     - App code is written by someone else.
     - May not always be secure.
     - Extensive testing would be required in this scenario.
* This is a balancing act - app features vs. unknown code base.

##### Data Exposure

* Sensitive data - credit card numbers, social security numbers, medical information, address details, email information.
* How is the app handling the data?
     - No encryption when stored.
     - No encryption across the network.
     - Displaying information on the screen.
* All input and output process are important - check them all for data exposure.

#### Open Web Application Security Project (OWASP)

* A not-for-profit foundation dedicated to fighting an finding web application vulnerabilities.

#### Software Diversity

* When computers run unique binaries that are functionally identical - alternate compiler paths result in a different binary each time, making each compiled application slightly different (but functionally the same).
* An attack against different binaries would only be successful on a fraction of the users (an attacker would not know what exploit to use).

##### Compiler

* A computer program created to read an entire program and convert it into a lower-level language and ultimately assembly language used by the processor.

##### Binary

* Software in executable form (compiled).

#### Automation/Scripting

* Automation - the process of creating and publishing application updates using continuous integration, continuous delivery, and continuous deployment.
* Scripting - can be used to create automation around the deployment of applications and automation based on how we react to problems that might occur when that application is executing.

##### Automated Courses of Action

* Many problems can be predicted - have a set of automated responses.

##### Continuous Monitoring

* Check for a particular event and then react.

##### Continuous Validation

* Cloud-based technologies allow for constant change - automatically validate a configuration before going live.
* Perform ongoing automated checks.

##### Continuous Integration

* Code is constantly written and merged into the central repository many times a day allowing for many chances for security problems.
* Have a basic set of security checks during development and a large scale security analysis during the testing phase.

##### Continuous Delivery

* Automate the testing process.
* Automate the release process.
* Click a button or enter a command and deploy the application

##### Continuous Deployment

* Automate further.
* Automatically deploy to production.
* No human integration or manual checks.

#### Elasticity

* Increase or decrease available resources as the workload changes - deploy multiple application instances to handle changes.

#### Scalability 

* The ability to increase the workload in a given infrastructure - build an application that handles the workload.

#### Version Control

* Tracking changes to allow you to revert back to a previous version.
* Useful for security to compare versions over time, identify modifications to important files.

***

# Demonstrate Your Understanding

[Back to Top](#top) \| [Study in a New Tab](../../resources/study_cards/sub_two_three.html){:target="_blank"}

_Click or tap on 'Choose a Study Mode' to switch between flash cards, match, learn, test and more._

<iframe src="https://quizlet.com/845363458/flashcards/embed?i=35mna1&x=1jj1" height="500" width="100%" style="border:0"></iframe>