# Payment-Security-Audit
Simulated ITGC security assessment with PCI DSS and NIST CSF mappings, audit evidence, findings, and remediation documentation.

# Payment Security Audit — ITGC Assessment

## Project Overview

This project is a simulated IT General Controls (ITGC) security assessment of ClearPay Systems, which is a fictional payment-processing company. The assessment focuses on user access management, privileged permissions, multi factor authentication (MFA), authentication log monitoring, and access review remediation.

With the use of Microsoft Excel and fictional datasets, I reviewed security controls and later documented findings, and evaluated potential risks. I also mapped the findings to PCI DSS requirements that were relevant and NIST Cybersecurity Framework categories.

## The Project Scope

- **25 employee accounts** were reviewed
- **25 access review records** were examined
- **150 authentication events** were analyzed
- **5 ITGC controls** were evaluated
- **5 audit findings** were documented

## Audit Findings

| Finding | Observation | Status |

| F-01 | One terminated employee account was still enabled | Simulated correction documented |
| F-02 | Two employees had excessive administrative privileges | Simulated correction documented |
| F-03 | Four accounts didn't have MFA enabled | Simulated correction documented |
| F-04 | Three required access changes were not complete | Simulated correction documented |
| F-05 | Five successful login events were associated with a disabled account | Investigation required |

## The Audit Methodology Used

1. Reviewed employee employment status and account access.
2. Compared assigned permissions with approved job roles.
3. Examined authentication settings to identify missing MFA.
4. Analyzed login events for unusual patterns and inconsistencies.
5. Reviewed access review records for incomplete corrective actions.
6. Documented findings with supporting screenshots.
7. Mapped findings to relevant PCI DSS and NIST CSF categories.
8. Documented simulated corrections using separate copies of the original datasets.

Formal remediation retesting was not performed.

## Framework Alignment

- **PCI DSS:** Requirements 7, 8, and 10 were most relevant
- **NIST CSF:** PR.AA (Identity Management, Authentication, and Access Control) and DE.CM (Continuous Monitoring) were most relevant


## The Tools Used

- Microsoft Excel
- Microsoft Word
- CSV datasets

## Project Structure

```text
Payment-Security-Audit/
├── 01_Source_Data/
├── 02_Audit_Evidence/
├── 03_Audit_Workbook/
├── 04_Remediation/
├── 05_Final_Report/
└── README.md
```

## Key Takeaways

This project shows how IT auditors test security controls and evaluate audit evidence, document findings, and recommend corrective actions.

Four findings received simulated corrections, while one finding still remains open for investigation.

## Disclaimer

This is an EDUCATIONAL portfolio project using fictional data. No real payment systems were audited, and no formal PCI DSS compliance assessment was performed.
