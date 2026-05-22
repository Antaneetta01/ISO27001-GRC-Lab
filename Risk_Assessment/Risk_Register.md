# Risk Register

| Risk ID | Asset                  | Threat                   | Vulnerability                       | Impact | Likelihood | Risk Score | Risk Level | Mitigation                                |
| ------- | ---------------------- | ------------------------ | ----------------------------------- | ------ | ---------- | ---------- | ---------- | ----------------------------------------- |
| R001    | IoT Gateway            | Unauthorized Access      | Weak Password Policy                | 4      | 4          | 16         | Critical   | Implement MFA and strong password policy  |
| R002    | Smart Sensors          | Malware Infection        | Unpatched Firmware                  | 5      | 3          | 15         | High       | Establish firmware update process         |
| R003    | Administrator Accounts | Credential Theft         | Lack of Multi-Factor Authentication | 5      | 4          | 20         | Critical   | Enforce MFA for privileged accounts       |
| R004    | Network Infrastructure | Denial of Service Attack | Insufficient Traffic Filtering      | 4      | 3          | 12         | High       | Deploy network monitoring and filtering   |
| R005    | Security Log Server    | Log Tampering            | Inadequate Log Protection           | 3      | 2          | 6          | Medium     | Restrict log access and enable monitoring |

---

## Risk Scoring Method

Risk Score = Impact × Likelihood

| Score Range | Risk Level |
| ----------- | ---------- |
| 1–5         | Low        |
| 6–10        | Medium     |
| 11–15       | High       |
| 16–25       | Critical   |

---

## Purpose

This risk register documents identified cybersecurity risks associated with the simulated smart IoT infrastructure environment used within the ISO27001-GRC-Lab project.

The register supports:

* cybersecurity governance
* risk monitoring
* mitigation planning
* ISO 27001 risk management alignment
* organizational security improvement
