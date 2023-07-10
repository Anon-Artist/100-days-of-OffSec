# 100-days-of-OffSec
## Summary

1. Day 1
  - [Introduction to Red Teaming](#introduction-to-red-teaming)
    - [What is Red Teaming](#what-is-red-teaming)
    - [Why Red Teaming](#why-red-teaming)
    - [Red Teaming x Penetration Testing](#red-teaming-x-penetration-testing)
    - [Red Team Methodologies](#red-team-methodologies)
    - [Red Team Report Template](#red-team-report-template)
    - [References](#references)
2. Day 2
  - [Introduction to Active Directory](#introduction-to-active-directory)
    - [What is Active Directory](#what-is-active-directory)
    - [Components of Active Directory](#components-of-active-directory)
    - [Structure of Active Directory](#structre-of-active-directory)
    - [References](#references)

## Introduction to Red Teaming

### What is Red Teaming

In fact there is no proper definition is available for Red teaming for example Red teaming is often used interchangeably with penetration testing even there is key difference in between them.\
As I said the term is not standardized but in some reference the term Red Teaming is defined as the process of using Tactics, Techniques, and Procedures (TTPs) to emulate a real-world threat with the goals of training and measuring the effectiveness of the people, processes, and technology used to defend an environment or it is the practice of looking at a problem or situation from the perspective of an adversary.

### Why Red Teaming

Red Teaming can be used to:
    
     1.  Measure the effectiveness of the people, processes, and technology used to defend a network.
     2.  Train and/or measure Blue teams ability to impact a threat.
     3.  Test and understand specific threats or threat scenarios Red team engagements can be designed to exercise custom scenarios. Scenarios can include zero-days, ransom-ware attacks, or other unique attacks.


### Red Teaming x Penetration Testing

Some of the key difference between Red Teaming and Penetration testing are:

<table style="width:100%">
  <tr>
    <th>Red Teaming</th>
    <th>Penetration Testing</th>
  </tr>
  <tr>
    <td>Focussed on acheiving goals or an attack path to acheive the goal</td>
    <td>Focussed on Identifying maximum number of vulnerabilities</td>
  </tr>
  <tr>
    <td>Assess people, processes and technologies</td>
    <td>Assess vulnerabilities in the specified scope</td>
  </tr>
  <tr>
    <td>Broad Scope</td>
    <td>Pre-Defined Scope</td>
  </tr>
    <tr>
    <td>Focus on stealth</td>
    <td>Stealth is not a factor</td>
  </tr>
</table>

### Red Team Methodologies

One of the famous and most used framework is "Cyber Kill Chain" developed by Lockheed Martin.\
<img src="https://github.com/Anon-Artist/100-days-of-OffSec/blob/main/images/THE-CYBER-KILL-CHAIN.png" width=75% alt="Image of Cyber Kill Chain">

There are other methodologies and framework such as
  1. MITRE ATT & CK [https://attack.mitre.org/]
  2. CBEST Intelligence Led Testing [https://www.crest-approved.org/membership/cbest/]
  3. Adversial Attack Simulation Exercise [https://abs.org.sg/docs/library/abs-red-team-adversarial-attack-simulation-exercises-guidelines-v1-06766a69f299c69658b7dff00006ed795.pdf]
  4. TIBER-EU [https://www.ecb.europa.eu/paym/cyber-resilience/tiber-eu/html/index.en.html]

### Red Team Report Template

You can find a good sample report of red team from here.
  1. https://redteam.guide/docs/Templates/report_template

### References

References for Day-1
  1. https://redteamjournal.com/
  2. https://redteam.guide/
  3. https://www.lockheedmartin.com/

## Introduction to Active Directory

### What is Active Directory

Active Directory stores information about objects on the network and makes this information easy for administrators and users to find and use. Active Directory uses a structured data store as the basis for a logical, hierarchical organization of directory information.This data store, also known as the directory, contains information about Active Directory objects. These objects typically include shared resources such as servers, volumes, printers, and the network user and computer accounts. Simply, Active Directory (AD) is a Microsoft technology used to manage computers and other shared resources on a network and it can be used for centralized management of authentication and authorization.

As I said Everything is considered as an object in Active Directory. Below is a diagram of an Active Directory objects:
<img src="https://github.com/Anon-Artist/100-days-of-OffSec/blob/main/images/Computers-and-Networks-Design_Elements-Active-Directory.png" width=75% alt="Image of Active Directory Objects">

### Components of Active Directory

Active Directory also includes:

	1. A set of rules, the schema, that defines the classes of objects and attributes contained in the directory, the constraints and limits on instances of these objects, and the format of their names.
	2. A global catalog that contains information about every object in the directory. This allows users and administrators to find directory information regardless of which domain in the directory actually contains the data.
	3. A query and index mechanism, so that objects and their properties can be published and found by network users or applications.
	4. A replication service that distributes directory data across a network. All domain controllers in a domain participate in replication and contain a complete copy of all directory information for their domain. Any change to directory data is replicated to all domain controllers in the domain.

### Structure of Active Directory

Active Directory has three main tiers:

	1. Organizational Units: Organizational Unit is used to manage users, groups, workstations, and other functional units.
	2. Domain: Domain is a group of users, computers and other Active Directory objects that share the same AD database.
	3. Tree: Domain tree is a collection of one or multiple domains grouped together in a hierarchical parent-child structure.
	4. Forest: Forest is a group of multiple trees with shared directory schemas, catalogs, application information and domain configurations.

<img src="https://github.com/Anon-Artist/100-days-of-OffSec/blob/main/images/image002.gif" width=75% alt="Image of Active Directory Structure">

### References

References for Day-2
  1. https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview
