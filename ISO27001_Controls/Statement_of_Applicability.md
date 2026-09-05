# Statement of Applicability (SoA)

## Purpose

The Statement of Applicability (SoA) identifies the selected ISO 27001:2022 controls applicable to the ISO27001-GRC-Lab project.

It documents the applicability of selected controls, the justification for their inclusion, their documented implementation status within the simulated environment, and the supporting project documentation.

The SoA demonstrates how the simulated smart IoT environment aligns with selected ISO 27001:2022 information security controls and supports Governance, Risk, and Compliance (GRC) activities.

---

# Project Information

| Item | Details |
|------|---------|
| Project | ISO27001-GRC-Lab |
| Standard | ISO 27001:2022 |
| Environment | Simulated Smart IoT Infrastructure |
| Document Owner | Information Security Team (Simulated) |
| Version | 1.2 |

---

# Statement of Applicability

| ISO 27001 Control | Control Description | Applicable | Justification | Implementation Status | Supporting Documentation |
|-------------------|--------------------|------------|---------------|-----------------------|--------------------------|
| A.5.9 | Inventory of Information and Other Associated Assets | Yes | Asset inventory is required to identify and manage information assets within the simulated environment. | Documented / Simulated | Asset_Inventory.md |
| A.5.15 | Access Control | Yes | Access control ensures that only authorized users can access organizational resources and supports least-privilege principles. | Documented / Simulated | Information_Security_Policy.md; Privileged_Access_Management_Procedure.md |
| A.5.16 | Identity Management | Yes | User and administrator identities should be appropriately managed throughout their access lifecycle. | Documented / Simulated | Privileged_Access_Management_Procedure.md |
| A.5.17 | Authentication Information | Yes | Strong authentication and protection of authentication information help reduce unauthorized access to user and administrator accounts. | Documented / Simulated | Password_Policy.md; Privileged_Access_Management_Procedure.md |
| A.5.18 | Access Rights | Yes | Access rights should be granted, reviewed, modified, and revoked according to business and security requirements. | Documented / Simulated | Privileged_Access_Management_Procedure.md |
| A.5.24 | Information Security Incident Management Planning and Preparation | Yes | Incident response procedures support preparation for identifying, managing, containing, and recovering from information security incidents. | Documented / Simulated | Incident_Response_Plan.md |
| A.5.30 | ICT Readiness for Business Continuity | Yes | Business continuity planning supports the availability and recovery of critical business services during disruptive events. | Documented / Simulated | Business_Continuity_Plan.md |
| A.5.36 | Compliance with Policies, Rules and Standards for Information Security | Yes | Security policies establish governance requirements and support compliance with organizational security requirements. | Documented / Simulated | Information_Security_Policy.md |
| A.8.2 | Privileged Access Rights | Yes | Privileged access requires additional controls to reduce the risk of unauthorized, excessive, or inappropriate administrative privileges. | Documented / Simulated | Privileged_Access_Management_Procedure.md |
| A.8.5 | Secure Authentication | Yes | Secure authentication mechanisms help protect user and privileged administrator accounts from unauthorized access. | Documented / Simulated | Password_Policy.md; Privileged_Access_Management_Procedure.md |
| A.8.8 | Management of Technical Vulnerabilities | Yes | Technical vulnerabilities should be identified, assessed, prioritized, and treated to reduce cybersecurity risk. | Documented / Simulated | Risk_Register.md |
| A.8.15 | Logging | Yes | Security and administrative activity logging supports monitoring, investigation, incident response, and audit activities. | Documented / Simulated | Privileged_Access_Management_Procedure.md; Incident_Response_Plan.md |
| A.8.16 | Monitoring Activities | Yes | Monitoring activities support the detection and investigation of security events and suspicious privileged activity. | Documented / Simulated | Privileged_Access_Management_Procedure.md; Incident_Response_Plan.md |

---

# Control Applicability Summary

| Status | Count |
|--------|------:|
| Applicable Controls | 13 |
| Documented / Simulated Controls | 13 |
| Planned for Future Implementation | 0 |
| Non-Applicable Controls | 0 |

---

# Justification

The selected controls were identified based on the scope, architecture, security requirements, and governance activities of the simulated smart IoT environment.

The selected controls support:

- Asset Management
- Identity Management
- Access Control
- Privileged Access Management
- Authentication
- Risk Management
- Incident Management
- Business Continuity
- Logging and Monitoring
- Information Security Governance
- Compliance Management

The inclusion of privileged access controls reflects the need to protect administrator accounts and elevated system privileges within the simulated environment.

---

# Control Implementation Approach

Within this portfolio project, control implementation refers to the development and documentation of simulated security policies, procedures, and governance artifacts that demonstrate how the selected controls are addressed within the simulated environment.

The project does not represent a live production environment.

Supporting documentation includes:

- Policies
- Procedures
- Risk management records
- Incident response documentation
- Business continuity documentation
- Control mapping
- Audit documentation

---

# Key Control Areas

## Access Management

Access management controls are supported through the Information Security Policy and Privileged Access Management Procedure.

The project addresses:

- Least privilege
- Need-to-know access
- Access approval
- Privileged account management
- Periodic access reviews
- Access modification
- Access revocation
- Separation of duties
- Multi-factor authentication where supported

## Privileged Access Management

The Privileged Access Management Procedure establishes documented requirements for managing administrator and other privileged accounts.

The procedure addresses:

- Privileged account provisioning
- Administrator account requirements
- Least privilege
- Privileged access approval
- Periodic privileged access review
- Privileged activity logging
- Monitoring
- Emergency privileged access
- Access revocation

## Incident Management

The Incident Response Plan and Incident Response Workflow support the management of information security incidents through:

- Identification
- Assessment
- Containment
- Eradication
- Recovery
- Lessons learned

## Business Continuity

The Business Continuity Plan supports continuity and recovery of critical services within the simulated environment.

It addresses:

- Critical business services
- Recovery priorities
- Backup strategy
- Recovery activities
- Roles and responsibilities
- Communication during disruptions
- Plan maintenance

## Vulnerability Management

The Risk Register supports the identification, assessment, prioritization, and treatment of cybersecurity risks associated with technical vulnerabilities.

---

# Benefits of the Statement of Applicability

The Statement of Applicability helps organizations to:

- Identify applicable ISO 27001:2022 controls.
- Document the justification for control applicability.
- Document the implementation status of security controls.
- Demonstrate governance and compliance alignment.
- Support internal and external audit activities.
- Improve traceability between controls and supporting documentation.
- Organize security evidence for audit readiness.
- Identify opportunities for continual improvement.

---

# Project Evidence

The following project documents provide supporting evidence for the selected controls:

- Asset Inventory
- Risk Assessment Methodology
- Risk Register
- Risk Treatment Plan
- Information Security Policy
- Password Policy
- Privileged Access Management Procedure
- Incident Response Plan
- Incident Response Workflow
- Business Continuity Plan
- ISO 27001:2022 Control Mapping
- Smart IoT Security Architecture
- Internal Audit Checklist
- Internal Audit Report

---

# Scope and Limitation

This Statement of Applicability represents selected ISO 27001:2022 Annex A controls relevant to the simulated smart IoT environment used in the ISO27001-GRC-Lab project.

It is a portfolio and learning artifact and does not represent a complete organizational Statement of Applicability, a complete ISO 27001 control assessment, or an ISO 27001 certification.

A complete organizational SoA would evaluate the full set of ISO 27001:2022 controls and document inclusion or exclusion decisions based on organizational context, applicable requirements, and risk.

The "Documented / Simulated" status reflects the development of policies, procedures, and governance artifacts within the portfolio project and does not represent evidence of live production control operation.

---

# Conclusion

This Statement of Applicability demonstrates how selected ISO 27001:2022 controls can be mapped to governance, risk management, and cybersecurity documentation within a simulated smart IoT environment.

The SoA provides traceability between selected controls and supporting project documentation covering asset management, access control, identity management, privileged access, authentication, risk management, incident response, business continuity, logging, monitoring, and compliance.

The document supports the project's audit readiness and demonstrates a structured approach to Governance, Risk, and Compliance (GRC) within a simulated ISMS.

---

**Document Version:** 1.2

**Classification:** Internal

**Review Frequency:** Annual

**Environment:** Simulated Smart IoT Infrastructure

**Project:** ISO27001-GRC-Lab
