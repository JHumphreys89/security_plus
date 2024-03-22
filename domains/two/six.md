---
layout: default
---

[Back to Home](../../index.html) \| [Back to Domain Two](../domain_two.html)

# Subdomain 2.6

_Explain the security implications of embedded and specialized systems._

_Terms_: 45

***

#### Embedded Systems

_A computer system with a dedicated function within a larger electrical or mechanical system such as traffic lights, smart watch, or medical systems._

##### Raspberry Pi

* Small form-factor embedded system that has an HDMI interface, USB interfaces on the side, and an RJ45 connector for Ethernet connectivity.
* Has built-in memory and very low power consumption.
* Uses System on a Chip (SoC).

##### Field-programmable Gate Array (FPGA)

* Integrated circuit that can be configured after manufacturing. Programmed in the field, array of logic blocks.
* Problems won't require a hardware replacement, can simple re-program the FPGA.
* Common in infrastructure such as Firewall logic and Routers.

#### Supervisory Control and Data Acquisition (SCADA)/Industrial Control System (ICS)

* SCADA:
      - System of software and hardware elements that allows industrial organizations to control industrial processes locally or at remote locations, monitor, gather, and process real-time data.
      - Directly interact with devices such as sensors, valves, pumps, motors, and more through human-machine interface (HMI) software.
      - Record events into a log file
* ICS
      - A form of computer-management device that controls industrial processes and machines.
      - Should be segmented from the internet.

##### Facilities

* Physical buildings, structures, and spaces where industrial processes take place, such as factories, warehouses, power plants, etc.
* Often have multiple SCADA and ICS systems that monitor and control different aspects of the facility.

##### Industrial

* This is a broad term that refers to any sector or activity that involves the production, processing, or distributing of goods or materials, such as manufacturing, mining, agriculture, mining, etc.
* Processes often rely on SCADA and ICS systems to automate and optimize the operations - robots, conveyor belts, etc.

##### Manufacturing

* Specific type of industrial activity involves the transformation of raw materials into finished products - cars, computers, furniture, etc.
* Processes often use SCADA and ICS systems to coordinate and control the various stages of production, such as assembly, quality control, packaging, etc.

##### Energy

* This is a sector that involves generation, transmission, and distribution of electricity, gas, oil, or other forms of energy such as solar, wind, nuclear, etc.
* Systems often use SCADA and ICS to monitor and regulate the flow and quality of energy, such as power grids, substations, pipelines, etc.

##### Logistics

* This is a sector that involves the planning, management, and execution of the transportation and storage of goods or materials, such as cargo, inventory, delivery, etc.
* Systems often use SCADA and ICS to track and optimize the movement and location of goods, such as GPS, RFID, barcode scanners, etc.

##### Internet of Things (IoT)

* Can communicate to SCADA and ICS systems, as well as with other IoT enabled devices, creating a vast network of interconnected devices that can exchange data and perform a variety of tasks autonomously.
* Can enhance the functionality and efficiency of SCADA and ICS, as well as introduce new security challenges and risks.

##### Sensors

* Devices that detect changes in the physical environment, such as temp, motion, light, sound, etc. and convert them into electrical signals that can be processed and transmitted by IoT devices.
* Are essential components of SCADA and ICS systems, as they provide the data that is used to monitor and control the industrial processes.
* Can also be vulnerable to tampering, spoofing, or jamming by malicious actors.

##### Smart Devices

* Devices that have some degree of intelligence, meaning that they can process data, make decisions, and execute actions without human intervention.
* Can be part of SCADA and ICS systems, such as smart meters, smart valves, smart cameras, etc., or they can interact with them, such as smart phones, smart watches, smart cars, etc.
* Can improve the performance and convenience of SCADA and ICS systems, but they can also pose security and privacy threats if they are compromised or hacked.

##### Wearables

* These are devices that are worn or attached to the human body such as smart glasses, smart bracelets, smart rings, etc.
* Can collect and transmit biometric data, such as heart rate, blood pressure, temp, etc. as well as environmental data such as location, speed, altitude, etc.
* Can be used by workers or operators of SCADA and ICS systems, to enhance their safety, productivity, or communication.
* Can also be used by attackers or intruders, to gain unauthorized access or information about SCADA and ICS systems.

##### Facility Automation

* This is the process of using technology to automate and optimize the operations and functions of a facility, such as lighting, heating, ventilation, security, fire alarms, etc.
* Can increase the comfort, efficiency, and safety of the facility, but it can also increase the complexity and vulnerability of the system.

##### Weak Defaults

* Refers to the use of insecure (default) or easily guessable settings for passwords, encryption keys, or network configurations, that are not changed by the users or administration.

#### Specialized

* 

##### Medical Systems

* Include pacemakers, insulin pumps, MRI machines, and other devices that monitor or treat patients' health conditions.
* They may store sensitive personal or medical data, or control critical functions of the human body. If they are compromised, they could cause physical harm, data breaches, or identity theft.

##### Vehicles

* Include cars, trucks, buses, trains, and other modes of transportation that use embedded systems to control various functions, such as navigation, braking, steering, entertainment, and communication.
* They may communicate with other vehicles, infrastructure, or networks, creating potential attack vectors. If they are hacked, they could cause accidents, theft, or sabotage.

##### Aircraft

* Include airplanes, helicopters, and other flying machines that use embedded systems to control flight, navigation, communication, and surveillance.
* They may rely on GPS, radar, or other signals which could be spoofed or jammed.
* If they are hijacked, they could cause crashes, terrorism, or espionage.

##### Smart Meters

* Are devices that measure and report the consumption of electricity, gas, water, or other utilities. 
* They may communicate with the utility provider, the smart grid, or the customer's devices, creating potential attack vectors.
* If they are tampered with, they could cause billing errors, service disruptions, or power outages.

#### Voice over IP (VoIP)

* Embedded devices using voice over the internet which replaced POTS (plain old telephone) phones.
* Relatively complex device with many capabilities and functions.

#### Heating, Ventilation, Air Conditioning (HVAC)

* PC embedded systems will run this environment system which will make heating and cooling decisions for data centers.

#### Drones

* Flying vehicles used via remote control.
* They can pose a security risk if they are not properly secured or if they are used for malicious purposes - as an example, they can be used to conduct unauthorized surveillance or to deliver an explosive payload.

#### Multifunction Printer (MFP)

* Everything you need in one single device.
* No longer a simple printer - very sophisticated hardware.
* Some images are stored locally on the device (can be retrieved externally).
* Logs are stored on the device (contain communication and fax details.)

#### Real-Time Operating System (RTOS)

* Embedded systems that take over control from the primary OS when needed but does not replace it such as car brakes.

#### Surveillance Systems

* Embedded systems in cameras. May secure sensitive areas.

#### System on a Chip (SoC)

* Multiple components running on a single chip which is common with embedded systems.
* Small form-factor:
     - External interface support, cache memory, flash memory, usually lower power consumption.
* Security considerations are important such as difficult to upgrade hardware, and limited off-the-shelf security options.

#### Communication Considerations

_Are crucial to ensure confidentiality, integrity, and availability of data. Embedded systems can use many different methods for communication, such as 5G, narrowband, baseband, and Zigbee networks._

##### 5G

* 5th generation wireless broadband technology based on the 802.11ac standard.
* Engineered to greatly increase the speed and responsiveness of wireless networks.
* Up to 10Gbps.
* Significant IoT impact:
      - Bandwidth now less of a constraint.
      - Larger data transfers than before.
      - Faster monitoring and notification functionality.
      - Additional cloud processing than before.

##### Narrow-Band

* Communicates analog signals over a range of frequencies for a very long distance.
* Many IoT devices can communicate over long distances - SCADA equipment such as sensors in oil fields.

##### Baseband Radio

* Single cable with a digital signal such as fiber or copper.
* Communication signal uses all of the bandwidth - either 0% or 100%.
* Bidirectional communication, but not at the same time using the same wire/fiber.
* Ethernet standard - 100BASE-TX, 1000BASE-T, 10GBASE-T

##### Subscriber Identity Module (SIM) Cards

* Integrated circuit that is universally compatible.
* Provides information to cellular network line IMSI (International Mobile Subscriber Identity), authentication info, contact info.

##### Zigbee

* IoT networking - open standard - IEEE 802.15.4 PAN.
* An alternative to Wi-Fi and Bluetooth. Longer distances than Bluetooth and less power consumption than Wi-Fi.
* Mesh network of all Zigbee devices in your home. Light switch communicates to lightbulbs. Tell Amazon Echo to lock the door.
* Uses the ISM band (Industrial, Scientific, and Medical). 900 MHz and 2.4GHz frequencies in the US.

#### Constraints

_Embedded systems have several constraints that limit their functionality and security. Constraints include power, networking, upgradeability, patching, and cost to name a few._

##### Power

* May need batteries or may not have direct access to power.

##### Compute

* Weak low power CPU.
* Cost and heat considerations.

##### Network

* Limited I/O may be only wired or only wireless.
* Low cost parts that won't have great range.

##### Crypto

* Limited cryptography capabilities. Usually no options for additional crypto hardware.

##### Inability to Patch

* May not have field-upgradeable options.
* May have limited upgrade options or is difficult to install.

##### Authentication

* May not have authentication or limited authentication. No MFD.

##### Range

* Specific purpose - no upgradeability.

##### Cost

* Low-cost, low-cost components may reduce lifespan.
* Low-cost may affect product quality.

##### Implied Trust

* May not have access to OS. 
* No path to hardware or software to audit.

***

# Demonstrate Your Understanding

[Back to Top](#top) \| [Study in a New Tab](../../resources/study_cards/sub_two_six.html){:target="_blank"}

_Click or tap on 'Choose a Study Mode' to switch between flash cards, match, learn, test and more._

<iframe src="https://quizlet.com/846606004/flashcards/embed?i=35mna1&x=1jj1" height="500" width="100%" style="border:0"></iframe>