# Risk Register

| Risk ID | Asset                  | Threat                   | Vulnerability                       | Impact | Likelihood | Risk Score | Risk Level | Risk Owner            | Treatment Strategy                                       | Residual Risk |
| ------- | ---------------------- | ------------------------ | ----------------------------------- | ------ | ---------- | ---------- | ---------- | --------------------- | -------------------------------------------------------- | ------------- |
| R001    | IoT Gateway            | Unauthorized Access      | Weak Password Policy                | 4      | 4          | 16         | Critical   | IT Manager            | Implement MFA and enforce strong password policy         | Medium        |
| R002    | Smart Sensors          | Malware Infection        | Unpatched Firmware                  | 5      | 3          | 15         | High       | Operations Manager    | Establish firmware update and patch management process   | Medium        |
| R003    | Administrator Accounts | Credential Theft         | Lack of Multi-Factor Authentication | 5      | 4          | 20         | Critical   | Security Manager      | Enforce MFA for privileged accounts                      | Low           |
| R004    | Network Infrastructure | Denial of Service Attack | Insufficient Traffic Filtering      | 4      | 3          | 12         | High       | Network Administrator | Deploy network monitoring and traffic filtering controls | Medium        |
| R005    | Security Log Server    | Log Tampering            | Inadequate Log Protection           | 3      | 2          | 6          | Medium     | Security Analyst      | Restrict log access and enable integrity monitoring      | Low           |


## Risk Register Fields

Risk Owner:
The individual responsible for managing and monitoring the risk.

Treatment Strategy:
The planned action used to reduce, transfer, avoid, or accept the risk.

Residual Risk:
The level of risk remaining after security controls have been implemented.

## Risk Scoring Method

Risk Score = Impact × Likelihood

| Score Range | Risk Level |
| ----------- | ---------- |
| 1–5         | Low        |
| 6–10        | Medium     |
| 11–15       | High       |
| 16–25       | Critical   |

## Purpose

This risk register documents identified cybersecurity risks associated with the simulated smart IoT infrastructure environment used within the ISO27001-GRC-Lab project.

The register supports:

* cybersecurity governance
* risk monitoring
* mitigation planning
* ISO 27001 risk management alignment
* organizational security improvement
