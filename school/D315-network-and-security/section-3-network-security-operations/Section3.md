# Section 3: Network Security Operations


* Lesson 1: Principles of Network Security Design: Diving into the core principles that form the backbone of network security, this lesson lays the groundwork for understanding the broader context of network defense strategies. 
* Lesson 2: Securing a Network: This lesson shifts focus to practical measures and techniques in securing a network, covering critical areas, such as firewalls, intrusion detection systems, and network segmentation. 
* Lesson 3: Cloud and Wireless Security: Recognizing the shift toward cloud and wireless technologies, this lesson addresses the unique security challenges and solutions in these environments. 
* Lesson 4: User Authentication and Access Control: Delving into identity management, this lesson explores the mechanisms and policies for effective user authentication and access control. 
* Lesson 5: Security Governance: Concluding the section, this lesson emphasizes the importance of security governance policies and the role they play in maintaining a secure network infrastructure. 

## Prepare for Assessment

* Can I identify the principles used to guide network security design? 
* Can I choose the context-appropriate solution to mitigate an attack? 
* Can I identify how to secure data and applications in specific contexts? 
* Can I identify which authentication, authorization, and accounting (AAA) category is affected and preventative in different situations? 
* Can I select an appropriate security governance solution for specific needs? 

---

## Lesson 1:  Princples of Network Security Design

### Objective

Identify the principles used to guide network security design.

"OWASP Top 10: A09:2021-Security Logging & Monitoring Failures"

## Detecting Intrusions

* data ingestion and analysis
    + network traffic
    + host and app logs
* filter out noise
    + reduce false positives

### host-based

* phishing/malware
* removable media
* physical access
* software vulnerabilites

### network-based

* unauthorized network access
* scanning
* rogue wireless APs

## IDS Intrusion Detection System

* host-base (file integrity monitoring/app behavior analytics)
* network-based (sensors, network traffic analysis, wireless intrusion detection system (WIDS))
* detect, log, alert, notify

## Intrusion Prevention System (IPS)

* Same capabilities as HIDS and NIDS
* Takes steps to block attacks
* Block IP, DNS, domain names, blackhole routing

### Sample Snort IDS Rule Config

``` /etc/snort/rules/local.rules
---------------
LOCAL RULES
---------------
# This file intentionally does not come with signatures. Put your local 
# additions here.
alert icmp any any -> $HOME_NET any (msg:"testing ICMP";sid:100001; rev:1; classtype:icmp-event;)
```

SNORT community has thousands of rule templates

---

## Lesson 1.1: Security Policies

Watch the video fo an in-depth exploration of various security policies - including data handling, password polocies, acceptable use, and BYOD.

"Common security Policies" (7:14) Certified in Cybersecurity (CC): Security Best Practices & Security Awareness"

### Knowledge Check

Question 1

In network security design, which principle advocates for the use of cryptographic techniques to secure sensitive data and communications?

- [ ] Defense in Depth
- [ ] Complete mediation
- [ ] Separation of Privilege
- [x] Security

---

## Lesson 1.2: Design Principles

Watch the video on this page, which offers a comprehensive over of human-centered design, focusing on its four main principles: solving core root issues rather than superficial problems, prioritizing people in the design proces, adopting a systems view to understand interdependencies, and enaging in continuous prototyping and testing to ensure designs truly meet user needs.

### Human-centered design principles

* Ensure the root problem is solved and not the symptom.
* The people need to be the main focus of the design proccess
* focus on the system interactions and not just on one part
* perform prototyping and testing iteratively and quickly

### Root Problem Identification

* focus on the cause of the problem and not the symptoms
* needs to be a integral part of the design process
    + importnat because you could end up attempting to solve the **wrong** problem
* solving fundamental problems will assist with **root** problems

## People-Centered Approach

* focus should be on people and not technology


---

[🔜 Next Section]()

[🔙 Back to Main Page](../../README.md)
