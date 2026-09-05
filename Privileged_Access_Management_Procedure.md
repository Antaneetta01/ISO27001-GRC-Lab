# Privileged Access Management Procedure

## Purpose

The purpose of this Privileged Access Management (PAM) Procedure is to establish controls for managing privileged administrator accounts within the simulated smart IoT environment used in the ISO27001-GRC-Lab project.

The procedure supports the principle of least privilege and helps reduce the risk of unauthorized access, misuse of administrative privileges, and compromise of privileged accounts.

---

# Scope

This procedure applies to privileged accounts that provide administrative or elevated access to:

- IoT Gateway
- Network Infrastructure
- Cloud Services
- Security Log Server
- Building Management Dashboard
- Administrative Systems
- Other systems requiring elevated privileges

This procedure applies to simulated administrators, security personnel, and other users requiring privileged access.

---

# Privileged Account Definition

A privileged account is an account that has elevated permissions allowing a user to perform administrative, security, configuration, or system-level activities.

Examples include:

- System administrator accounts
- Network administrator accounts
- Cloud administrator accounts
- Security administrator accounts
- Database administrator accounts

---

# Privileged Access Principles

Privileged access should be managed according to the following principles:

### Least Privilege

Users should receive only the privileges required to perform their assigned responsibilities.

### Need-to-Know

Administrative access should be granted only when required for legitimate business or security activities.

### Individual Accountability

Privileged accounts should be uniquely assigned to individual administrators whenever technically feasible.

### Separation of Duties

Administrative responsibilities should be separated where appropriate to reduce the risk of unauthorized or conflicting activities.

### Time-Limited Access

Temporary privileged access should be granted for a defined period whenever practical.

---

# Privileged Account Provisioning

Privileged access should follow a documented approval process.

Before privileged access is granted:

1. The access requirement should be identified.
2. The business or operational justification should be documented.
3. The appropriate system or resource should be identified.
4. The access level required should be determined.
5. The request should be approved by the appropriate system or security owner.
6. Access should be configured according to least-privilege principles.
7. The privileged account should be documented in the access management records.

---

# Administrator Account Requirements

Where technically feasible:

- Administrators should use separate accounts for administrative activities and normal user activities.
- Shared administrator accounts should be avoided.
- Privileged accounts should be uniquely identifiable.
- Administrative credentials should not be shared between users.
- Default administrator credentials should be changed or disabled where applicable.
- Privileged accounts should be protected using strong authentication mechanisms.
- Multi-factor authentication (MFA) should be used for privileged access where supported.

---

# Privileged Access Review

Privileged access should be reviewed periodically to verify that access remains appropriate.

The review should verify:

- Current privileged users
- Assigned administrative privileges
- Business justification
- Account ownership
- Employment or role status
- Continued need for access
- Unused or unnecessary privileged accounts

Access that is no longer required should be removed or modified promptly.

---

# Privileged Account Changes

Changes to privileged access should be documented and approved.

Examples include:

- Granting administrative privileges
- Increasing privilege levels
- Removing administrative privileges
- Changing administrator responsibilities
- Transferring administrative responsibilities

Changes should follow the organization's access management and change management processes.

---

# Privileged Account Revocation

Privileged access should be revoked when:

- The user leaves the organization.
- The user's role changes.
- Administrative responsibilities are removed.
- Access is no longer required.
- A security incident requires immediate access restriction.
- An account is identified as unauthorized or compromised.

For high-risk situations, access should be disabled immediately and investigated according to the Incident Response Plan.

---

# Authentication and Credential Protection

Privileged accounts should use appropriate authentication controls.

Requirements include:

- Strong passwords or authentication mechanisms
- MFA where supported
- Protection of authentication information
- No sharing of administrator credentials
- Secure storage of credentials
- Immediate reporting of suspected credential compromise

Privileged credentials should not be stored in unsecured documents, scripts, or publicly accessible locations.

---

# Privileged Activity Logging and Monitoring

Administrative activities should be logged where technically feasible.

Monitoring should support the identification of:

- Successful privileged logins
- Failed authentication attempts
- Privilege changes
- Administrative configuration changes
- Account creation or deletion
- Suspicious administrative activity

Security logs should be protected from unauthorized modification and reviewed according to the organization's monitoring and incident management procedures.

---

# Emergency Privileged Access

Emergency privileged access may be granted when immediate administrative action is required to:

- Respond to a cybersecurity incident
- Restore critical services
- Address a critical system failure
- Prevent significant security or operational impact

Emergency access should:

1. Be limited to the required activity.
2. Be approved where practical.
3. Be documented.
4. Be reviewed after the emergency activity.
5. Be revoked when no longer required.

---

# Roles and Responsibilities

| Role | Responsibility |
|------|----------------|
| IT Manager | Approves and oversees privileged access requirements |
| System Owner | Approves access to systems under their responsibility |
| Security Manager | Reviews privileged access from a security perspective |
| System Administrator | Uses privileged access according to approved responsibilities |
| Security Analyst | Supports monitoring and investigation of privileged activity |
| Internal Auditor | Reviews privileged access controls and supporting evidence |

---

# Evidence and Records

The following records may be maintained to demonstrate privileged access governance:

- Privileged Account Register
- Access Request and Approval Records
- Periodic Privileged Access Review Records
- Administrator Account Inventory
- Access Revocation Records
- Authentication Logs
- Administrative Activity Logs
- Security Incident Records
- Access Change Records

These records support auditability and demonstrate that privileged access is governed throughout its lifecycle.

---

# Control Alignment

This procedure supports the following ISO 27001:2022 Annex A controls:

| Control | Description | Relevance |
|---------|-------------|-----------|
| A.5.15 | Access Control | Establishes access control principles and requirements |
| A.5.16 | Identity Management | Supports management of user and administrator identities |
| A.5.18 | Access Rights | Supports granting, reviewing, modifying, and revoking access rights |
| A.8.2 | Privileged Access Rights | Establishes controls for managing privileged administrative access |
| A.8.5 | Secure Authentication | Supports strong authentication for privileged accounts |
| A.8.15 | Logging | Supports recording of administrative and security activities |
| A.8.16 | Monitoring Activities | Supports monitoring of privileged account activity |

---

# Periodic Review

Privileged access should be reviewed periodically and following significant events, including:

- Role changes
- Organizational changes
- Security incidents
- Major system changes
- Identification of unauthorized access
- Changes to access requirements

Findings from access reviews should be documented and appropriate remediation actions should be tracked.

---

# Conclusion

This Privileged Access Management Procedure establishes a structured approach for controlling administrative and elevated access within the simulated smart IoT environment.

The procedure supports least privilege, access approval, periodic access review, authentication, logging, monitoring, and timely access revocation.

It complements the project's Information Security Policy, Password Policy, Incident Response Plan, Risk Register, and ISO 27001:2022 Control Mapping.

---

**Document Owner:** Information Security Team (Simulated)

**Document Version:** 1.0

**Classification:** Internal

**Review Frequency:** Annual

**Environment:** Simulated Smart IoT Infrastructure

**Project:** ISO27001-GRC-Lab
