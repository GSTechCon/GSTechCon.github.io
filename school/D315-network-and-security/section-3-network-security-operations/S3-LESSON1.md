# Lesson 1: Principles of Network Security Design

---

## Lesson 1.1: Security Policies

## Lesson 1.2: Design Principles

## Lesson 1.3: Least Privilege

This lesson provides an in-depth explanation of the principles of least prvilege in cybersecurity - focusing on granting minimal neccesary permission to users and applications, limiting access based on tasks and time, the importance of structuring security levels to minimize exposure and risk.

* start with no privileges
* time based
* only what's needed

Keeps data confidential and secret. Ensures users that don't require highers of information have access and inadvertantly provide said information.

---

## Lesson 1.4: Fail-Safe Defaults

Design principle of fail safe. When a system experiences a failure. It should fail to a safe state. In a way that does not compromise security.

* Exceptions
    + Exceptions are not errors
    + have specific handling requirements
* errors
    + mistakes or faults
    + human error
    + errors have specific handling requirements

Error/Exception handling are handled in a predictable and acceptable way. One failsafe principle

### Explicit Deny

* deny by default
* non-verbose
    + error codes
    + error IDs
    + more comprehensive that won't help an average user
    


## Lesson 1.5: Economy of Mechanism

## Lesson 1.6: Complete Mediation

## Lesson 1.7: Open Design

## Lesson 1.8: Sepeartion of Privilege

## Lesson 1.9: Least Common Mechanism

## Lesson 1.10: Psychological Acceptability

## Lesson 1.11: Trust

---

## Section 23 - Lesson 1: Summary

Take a moment to think about what you learned in this lesson:

* Human-centered design focuses on solving root issues (not just symptoms) with people as the central focus, adopting a systems view, and engaging in continuous prototyping and testing. 
* Least privilege involves granting minimal necessary permissions to users and applications, thus limiting access based on tasks and time to minimize exposure and risk. 
* Fail-safe design ensures that systems fail securely without compromising security, with errors and exceptions handled predictably and acceptably. This design also emphasizes the adoption of principles like "deny by default." 
* Separation of duties requires multiple parties for task completion to prevent misuse of permissions. It also involves the use of secret sharing in sensitive scenarios. 
* Least common mechanism minimizes unintentional information sharing by avoiding shared mechanisms among users and processes and instead favoring separate, isolated processes. 
* Psychological acceptability refers to the idea that security systems should be user-friendly and not impede users' tasks, as complex security measures might lead to bypassing and compromises. 
* The zero trust model emphasizes distrust by default—requiring strong authentication, least privilege, active monitoring, and rigorous authorization processes. 
* Security policy concepts include data handling, password policies, acceptable use, and BYOD policies. These policies emphasize the importance of clear guidelines and user compliance for security. 

## Next Steps

After exploring the foundational principles of cybersecurity in Lesson 1, you should now apply these concepts practically in Lesson 2, "Securing a Network." This next step includes understanding and implementing various network security measures, such as firewalls, cloud and wireless security, encryption, and network device hardening. You can leverage your knowledge of human-centered design, least privilege, and zero trust models to inform decisions on network security configurations and policies and ensure a robust and user-friendly security infrastructure. This transition from theoretical principles to practical applications is crucial for a comprehensive understanding of cybersecurity.  

---

---

[🔜 Next Section](./S3-LESSON2.md)

[🔙 Back to Main Page](../../README.md)
