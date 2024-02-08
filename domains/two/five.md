---
layout: default
---

[Back to Home](../../index.html) \| [Back to Domain Two](../domain_two.html)

# Subdomain 2.5

_Given a scenario, implement cybersecurity resilience._

_Terms_: 47

***

#### Redundancy

* A technique used to ensure that a system remains operational even if one or more components fail. It involves having more than one of some functioning feature of a system or even another complete system.
* With regard to cybersecurity, redundancy means that there is no single point of failure in the infrastructure. If a single component fails, the system should continue to operate without any disruption.

##### Geographic Dispersal 

* Disperse technologies to different geographies (multiple data centers in different locations).

##### Disk

* This form of redundancy involves using multiple hard drives to store data.
* Most common disk redundancy technologies are RAID 0, RAID 1, RAID 5, and RAID 6.

###### Redundant array of inexpensive disks (RAID) levels

* RAID O:
     - Uses disk striping **without** parity of mirroring, which means that it does **NOT** provide any redundancy or fault tolerance.
* RAID 1:
     - Uses **disk mirroring**, which means that it duplicates data across two disks.
* RAID 5:
     - Uses **disk striping with parity**, which means that it distributes parity information across all disks in the array.
* RAID 6:
     - Similar to RAID 5, but uses **two parity blocks** instead of one.

| RAID Level                         | Description             | Details                                                               |
|:-----------------------------------|:------------------------|:----------------------------------------------------------------------|
| RAID 0                             | Striping without parity | High performance, no fault tolerance                                  |
| RAID 1                             | Mirroring               | Duplicates data for fault tolerance but requires twice the disk space |
| RAID 5                             | Striping with parity    | Fault tolerant, only requires an additional disk for redundancy       |
| RAID 0+1, RAID 1+0, RAID 5+1, etc. | Multiple RAID types     | Combine RAID methods to increase redundancy                           |

###### Multipath

* Multiple drives create redundancy - especially useful for network-based storage subsystems.

##### Network

* Involves using multiple network paths to ensure that data can be transmitted even if one path fails.

###### Load balancers

* Some servers are active, others are on standby. If an active server fails, the passive server takes its place.

###### Network Interface Card (NIC) teaming

* NIC teaming is the process of combining multiple network cards together for performance, load balancing, and redundancy reasons.
* Load Balancing / Fail Over (LBFO) - aggregate bandwidth, redundant paths.
* Looks like a single adapter - integrate with switches.
* NICs talk to each other and usually multicast instead of broadcast. Fails over when a NIC does not respond.

##### Power

* This form of redundancy involves using multiple power sources to ensure that power is always available even if one source fails.

###### Uninterrupted Power Supply (UPS)

* Short-term backup power. Used in blackouts, brownouts, and surges.
* There are multiple types: offline/standby, line-interactive, on-line/double-conversion.
* Include features such as auto shutdown, battery capacity, outlets, phone line suppression.

###### Generator

* Long-term backup power. Fuel storage required and can power an entire building.
* Some outlets may be marked as generator-powered (different color outlets, physically marked).
* This can take some time to start up - might use a battery UPS while the generator is starting up.

###### Dual supply

* Two power supplies in one device. Each power supply can handle 100% of the load, allowing you to replace a faulty power supply without powering down.
* Internal server power supplies, external power circuits.
* Hot-swappable - replace a faulty power supply without having to power down.

###### Managed Power Distribution Units (PDUs)

* Provides multiple power outlets (usually in a rack.) Often includes monitoring and control, the ability to manage power capacity and enable/disable individual outlets.

#### Replication

_The process of creating identical copies of a component to compensate for random hardware failures._

##### Storage Area Network (SAN)

* A specialized high-performance network of storage devices.
* Extremely fast recovery times compared to more traditional backups.
* SAN-to-SAN replication - Duplicate data from one data center to another.
* SAN snapshot - create a state of data based on a point in time. Copy that state to other SANs.

##### VM

* Allows you to recover a virtual machine from a replicated copy. Copying only replicated the data that has changed.
* The VM is really just one big file.
* Constant service offering - maintain copies anywhere in the world.
* Efficient copying - only replicates the data that has changed.

#### On-Prem Vs. Cloud

* **Speed**: Local devices connected over very fast networks, cloud connections are almost always slower.
* **Money**: Purchasing your own storage is expensive, cloud costs have a low entry point and can scale.
* **Security**: Local data is private, cloud data requires additional security controls.

#### Backup Types

* While implementing cybersecurity resilience, it is important to have a backup plan in place.
* There are several types of backups that can be used to ensure data is protected and available when needed.

| Backup Type  | Data Selection                                     | Backup/Restore Time                     | Archive Attribute |
|:-------------|:---------------------------------------------------|:----------------------------------------|:------------------|
| Full         | All selected data                                  | High/low (one tape set)                 | Cleared           |
| Incremental  | New files and files modified since the last backup | Low/high (multiple tape sets)           | Cleared           |
| Differential | All data modified since the last full backup       | Moderate/moderate (no more than 2 sets) | Not Cleared       |

##### Full

* A complete backup of all data.

##### Incremental

* Full backup taken first.
* Then subsequent backups of only the data that has changed since the last full backup and last incremental backup (these are usually smaller than the full backup).
* To restore requires the full backup and all of the incremental backups.

##### Snapshot

* Can capture the current configuration and data.
* Preserves the complete state of a device or just the configuration.

##### Differential

* Full backup taken first.
* Includes all data modified since the last full backup.
* Subsequent backups contain data changed since the last full backup.
* A restoration requires the full backup and the last differential backup.

##### Tape

* Magnetic tape is a type of sequential storage.
* It is easy to ship and store and allows for 100GB - multiple TB per cartridge.

##### Disk

* Faster than a magnetic tape.
* Deduplicate and compress.

##### Copy

* May not include versioning, may need to keep offsite.

##### Network-Attached Storage (NAS)

* Connected to a shared storage device across the network. 
* File-level access.

##### Storage Area Network (SAN)

* Looks and feels like a local storage device.
* Block-level access.
* Very efficient reading a writing.

##### Cloud

* Backup to a remote device in the cloud.
* Supports many devices but may be limited by bandwidth.

##### Image

* Capture an exact replica of everything on a drive.
* Can be used to restore everything on a partition, including OS files and user documents.

##### Online vs. Offline

* Online backups: remote network-connected 3rd party, encrypted, accessible from anywhere; speed is limited by network bandwidth.
* Offline backups: Backup to local devices, fast and secure, must be protected and maintained, often requires offsite storage for disaster recover.

##### Offsite storage

* When selecting an offsite location for storage, it is important to consider the distance between the primary and secondary locations. 

###### Distance considerations

* The distance should be far enough to limit the likelihood of an event affecting both locations, but close enough to limit the constraints caused when in use.

#### Non-persistence

* A concept in cybersecurity that refers to the ability of a system to maintain its integrity despite multiple attempts of changes by users or attackers.

##### Revert to known state

* Refers to restoring a system to a previously saved state that is known to be secure and free of malware.
* Typically done by restoring a system image or snapshot that was taken when the system was in a last known-good state.

##### Last known-good configuration

* Is a feature in Windows OS that allows users to boot their systems using the most recent configuration that worked correctly.
* This feature can be used to recover from issues caused by incorrect configuration changes or malware infections.

##### Live boot media

* Is an OS that can be booted from removable media such as a USB drive or CD/DVD.
* Often used for troubleshooting and recovery purposes, as it allows users to boot into a clean environment that is not affected by malware or other issues on the host system.

#### High availability

* A design goal that results in a system with fault tolerance.
* Fault tolerance is the ability of a system to continue operating even when there is a disruption.
* So the system should continue to operate even when there is a disruption, and it is achieved by having devices that are always on and always available.
* If the primary system fails, you have immediate accessibility and can maintain the uptime and available of the application.

##### Scalability

* It is important because it allows organizations to respond effectively to new threats and vulnerabilities.
* A scalable system can be easily updated and modified to address new security concerns, without requiring significant changes to the underlying infrastructure.

#### Restoration order

* Databases should be restored before the application.
* Incremental backups restore the full backup, then all subsequent incremental backups.
* Differential backups restore the full backup, then the last differential backup

#### Diversity

* Refers to the use of a variety of technologies, vendors, crypto, and controls to ensure the system is resilient to cyber attacks.
* This approach is used in addition to redundancy, replication, and other measures.

##### Technologies

* Employ multiple security devices. A zero-day OS vulnerability can cause significant outages.

##### Vendors

* Having a single vendor can be a disadvantage.
* A bad support team may not be able to resolve problems quick enough.

##### Crypto

* All cryptography is temporary.
* Diverse certificate authorities can provide additional protection.

##### Controls

* Combine multiple controls together to have a robust security program (administrative, physical, technical, etc.)

***

# Demonstrate Your Understanding

[Back to Top](#top) \| [Study in a New Tab](../../resources/study_cards/sub_two_five.html){:target="_blank"}

_Click or tap on 'Choose a Study Mode' to switch between flash cards, match, learn, test and more._

<iframe src="https://quizlet.com/846227732/flashcards/embed?i=35mna1&x=1jj1" height="500" width="100%" style="border:0"></iframe>