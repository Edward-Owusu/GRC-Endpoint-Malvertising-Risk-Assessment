# GRC Endpoint Malvertising & Phishing Risk Assessment

A practical Governance, Risk, and Compliance (GRC) / IT Audit case study focused on endpoint malvertising and malicious browser notification risks.

## Project Overview

This project demonstrates an end-to-end GRC approach for a scenario where employees may interact with deceptive browser push notifications disguised as legitimate endpoint security alerts.

The project connects:

**Risk Identification → Risk Assessment → Framework Mapping → Control Design → Audit Testing → Evidence → Metrics**

## Objectives

- Identify and assess endpoint malvertising and phishing-related risk.
- Evaluate inherent and residual risk.
- Map risks and controls to recognized security frameworks.
- Design preventive and detective controls.
- Develop practical IT audit testing procedures.
- Define evidence requirements and measurable KPIs.

## Frameworks Referenced

- NIST Cybersecurity Framework (CSF) 2.0
- ISO/IEC 27001:2022
- CIS Controls v8

## Key Risk

**Risk ID:** RSK-001

Employees may interact with deceptive web browser push notifications that appear to be legitimate antivirus or security alerts. This can result in unauthorized execution of malicious software, particularly where security awareness is insufficient or users have excessive privileges.

### Risk Scoring

| Measure | Score |
|---|---:|
| Inherent Likelihood | 4/5 |
| Inherent Impact | 4/5 |
| Inherent Risk | 16/25 |
| Residual Likelihood | 2/5 |
| Residual Impact | 3/5 |
| Residual Risk | 6/25 |

The proposed controls reduce the assessed risk from **16/25 to 6/25**.

## Proposed Controls

### 1. Centralized Browser Notification Controls
Standardize endpoint browser configurations through centralized Google Chrome and Microsoft Edge GPO/MDM policies to restrict unauthorized web notification prompts.

### 2. Least Privilege
Restrict local administrative privileges so standard users cannot independently install unauthorized executable software.

### 3. Security Awareness
Deploy targeted security awareness and simulated phishing/malvertising exercises focused on recognizing deceptive browser notifications.

## IT Audit Testing

The project includes three audit procedures:

| Control ID | Audit Focus | Frequency | Target |
|---|---|---|---|
| AUD-002.1 | Validate centralized browser notification configuration | Quarterly | 100% endpoint enforcement |
| AUD-002.2 | Review local administrative privileges | Semi-annually | 0% of standard users with local admin access |
| AUD-002.3 | Review security awareness completion and simulation results | Monthly | 95%+ completion; <5% interaction |

## Evidence Examples

Potential audit evidence includes:

- GPO configuration exports
- Registry/configuration audit results
- Active Directory group exports
- Privileged Access Management reports
- Security awareness platform reports
- Simulated phishing/malvertising campaign metrics

## Policy Component

The workbook also contains a sanitized endpoint notification hygiene policy covering:

- Centralized endpoint security notifications
- Browser notification restrictions
- Software installation boundaries
- Escalation of observed non-compliance

## Repository Contents

```text
GRC-Endpoint-Malvertising-Risk-Assessment/
├── README.md
├── data/
│   └── GRC_Endpoint_Notification_Project.xlsx
└── documentation/
    ├── risk-assessment.md
    ├── control-mapping.md
    ├── audit-testing.md
    └── endpoint-notification-policy.md
```

## Disclaimer

This is a **sanitized portfolio case study** created for educational and professional demonstration purposes. It does not contain confidential organizational information, credentials, production configurations, or real security event data.

## Skills Demonstrated

**GRC | IT Audit | IT Risk | Risk Assessment | Control Design | Compliance | NIST CSF | ISO 27001 | CIS Controls | Audit Testing | Security Metrics | Endpoint Security**
