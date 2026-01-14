# TJ Fields Cybersecurity Portfolio

# [Professional Statement](https://github.com/Tfields2/Professional-Statement/blob/main/TJ_Fields_Professional_Statement.pdf)
---
# [Project 1:  NIST CSF 2.0 Icident Response Plan - Cantaluope Inc](https://tfields2.github.io/Nist_CSF_2.0_Incident_Response_Cantaloupe-Inc./)

This was a group project I did in my final semester of undergrad at The University of Alabama. This project documents the design and formalization of a NIST Cybersecurity Framework (CSF) 2.0-aligned Incident response Plan for Cantaloupe Inc. The objective was to create a structured, regulatory-aware framework addressing detection, containment, eradcation, recovery, and post-incident improvement.

- Developed a NIST CSF 2.0 aligned incident response plan for Canatloupe Inc.
- Defined the end to end response lifecycle, including detection, containment, recovery, and post-incident improvement
- Established incident governance, roles, and escalation procedures
- Created scenerio based response playbook for common financial sector incident (Ransomeware attack)
- Mapped controls to NIST CSF 2.0 Respond and Recover functions
- Presented the finalized documentation to a cybersecurity governance board for review
---
# [Project 2: Applied Cybersecurity](https://tfields2.github.io/Applied-Cybersecurity/)

These projects demonstrate hands-on experience across **security operations, incidents response, risk and vulnerability assessment, and governance, risk, and compliance (GRC)**. The work applies practical security techniques and industry frameworks to investigate suspicious activity, analyze and respond to security incidents, assess organizational risk, and evaluate control effectiveness. Emphasis is placed on evidence based analysis, least-privilege enforcement, structured incident response, and clear technical documentation aligned with real world cybersecurity practices.
## Project Arees & Skills Demonstrated
- **Technical Security Labs**
- SQL-based investigation of suspicious login activity and authentication logs
  - Linux file and directory permission management enforcing least privilege

- **Incident Response & Analysis**
  - Ransomware incident documentation including detection, containment, and recovery planning
  - DDoS attack analysis with root cause identification and post-incident improvements
  - Incident analysis aligned with the NIST Cybersecurity Framework

- **Risk & Vulnerability Management**
  - Qualitative vulnerability and risk assessment using NIST SP 800-30 Rev. 1
  - Threat source identification, likelihood and impact scoring, and risk prioritization

- **Governance, Risk, & Compliance (GRC)**
  - Evaluation of administrative, technical, and physical security controls
  - Compliance gap analysis aligned with PCI DSS, GDPR, and SOC principles
  - Risk-based security recommendations to improve organizational security posture

---

# [Project 3: Secure Authentication & Password Manager (Python)](https://github.com/Tfields2/secure-password-manager-python)
This Python project demonstrates how a basic password manager can evolve into a secure authentication system through deliberate, security-focused design. I incrementally introduced protections such as cryptographic password hashing, account lockouts after repeated failures, audit logging for authentication events, administrative recovery workflows, and safe on-disk persistence.

The project reflects practical security engineering choices rather than theoretical examples, emphasizing how authentication systems defend against brute-force attacks, credential leaks, and data corruption.

## Note

This project is intentionally terminal-based to highlight authentication logic and security controls rather than user interface design. The same architecture and logic could be adapted to a web application, REST API, or enterprise identity platform.

---

# [Project 4: Caesar Cipher Encryption & Logging Tool (Python)](https://github.com/Tfields2/Python-Caeser-Cypher)

This project demonstrates hands-on experience in **secure software design, defensive programming, data handling, and security-focused workflow development**. Rather than focusing solely on cryptography, the project emphasizes how encryption tools are implemented in practice, including persistent logging, input validation, deduplication, and operational resilience.

The work applies fundamental security principles such as **data integrity, controlled input handling, auditability, and fault tolerance**, showcasing how even simple cryptographic algorithms must be supported by robust surrounding logic to be operationally useful. Emphasis is placed on maintainable code, structured logging, and real-world defensive considerations.

## Project Areas & Skills Demonstrated

- **Secure Application Development**
  - Implementation of a Caesar cipher supporting encryption and decryption of messages and files
  - Separation of cryptographic logic from input handling and file operations
  - Clear, well-documented code designed for readability and maintainability

- **Logging & Data Integrity**
  - Append-only JSONL logging of encryption events with unique monotonic IDs
  - Case-insensitive and whitespace-normalized deduplication to prevent duplicate log entries
  - Fault-tolerant parsing that safely handles malformed or corrupted log records

- **Operational Security Workflows**
  - Log-driven workflows enabling retrieval and analysis of encrypted data by ID
  - Brute-force decryption of stored ciphertext to simulate basic cryptanalysis techniques
  - CLI-based design reflecting real-world security tooling and analyst workflows

- **Defensive Programming & Error Handling**
  - Input validation for cryptographic parameters and user commands
  - Safe file I/O to prevent accidental overwrites and runtime crashes
  - Graceful handling of malformed input, missing files, and interrupted execution

## Note  
This project is intentionally terminal-based to emphasize encryption workflows, logging discipline, and defensive programming rather than user interface complexity. The architecture is designed to be extensible and could be adapted to a backend service, security training tool, or audit-focused encryption workflow.

---
