# Risk Assessment

## Risk ID

**RSK-001 — Endpoint Malvertising & Phishing Risk**

## Asset / Process

Corporate endpoints and corporate network.

## Threat Description

Employees may interact with deceptive web browser push notifications disguised as legitimate endpoint antivirus or security alerts.

This creates a risk of unauthorized execution of malicious software through malvertising, drive-by downloads, and unsafe user interaction.

## Inherent Risk

- Likelihood: **4/5**
- Impact: **4/5**
- Risk Score: **16/25 — High**

## Proposed Mitigation

1. Centralize browser notification restrictions through GPO/MDM.
2. Restrict local administrative privileges.
3. Provide targeted security awareness training.
4. Monitor compliance through recurring audit testing.

## Residual Risk

- Likelihood: **2/5**
- Impact: **3/5**
- Risk Score: **6/25 — Moderate**

## GRC Perspective

The objective is not to claim that controls eliminate the risk. The objective is to reduce the likelihood and/or impact to an acceptable level and establish evidence that controls continue to operate effectively.
