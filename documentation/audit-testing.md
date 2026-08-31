# IT Audit Testing Plan

## Audit Objective

Determine whether endpoint notification controls, privileged access restrictions, and security awareness activities are implemented and operating effectively.

## Test 1 — Browser Configuration

**Control ID:** AUD-002.1

**Objective:** Verify centralized browser configurations through Active Directory/MDM.

**Evidence:**
- GPO exports
- MDM configuration reports
- Registry/configuration audit results
- Endpoint compliance reports

**Frequency:** Quarterly

**Target:** 100% of corporate endpoints enforce the browser notification restriction.

**Testing approach:**
1. Obtain the approved browser configuration baseline.
2. Select a representative endpoint sample.
3. Compare endpoint settings against the approved baseline.
4. Document exceptions.
5. Determine whether exceptions are authorized and remediated.

## Test 2 — Local Administrative Privileges

**Control ID:** AUD-002.2

**Objective:** Verify that standard users do not have unnecessary local administrator privileges.

**Evidence:**
- Active Directory group exports
- PAM reports
- Endpoint privilege reports

**Frequency:** Semi-annually

**Target:** 0% of standard customer service/administrative staff with local admin accounts.

**Testing approach:**
1. Obtain the population of standard users.
2. Identify users with local administrator privileges.
3. Validate business justification for exceptions.
4. Confirm remediation or documented approval.

## Test 3 — Security Awareness

**Control ID:** AUD-002.3

**Objective:** Evaluate completion and interaction rates from targeted security awareness activities.

**Evidence:**
- Training completion reports
- Simulated phishing/malvertising results
- Security awareness dashboards

**Frequency:** Monthly

**Target:**
- 95%+ training completion
- Less than 5% interaction with simulated popup risks

**Testing approach:**
1. Obtain the reporting period population.
2. Validate completion rates.
3. Review simulation interaction rates.
4. Identify repeat-risk users.
5. Confirm targeted remediation where appropriate.

## Audit Conclusion

The testing program is designed to provide evidence that preventive controls are configured, privileged access is appropriately restricted, and workforce awareness is being measured continuously.
