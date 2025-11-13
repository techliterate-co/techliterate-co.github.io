+++
date = '2025-10-29T10:01:51-06:00'
title = 'Security and Compliance'
weight = 5

[params]
  menuPre = '<i class="fa-solid fa-shield"></i> '
+++

{{< mermaid align="center" zoom="true" >}}
%%{init: {"flowchart": {"useMaxWidth": false, "nodeSpacing": 40, "rankSpacing": 70, "htmlLabels": true}} }%%
flowchart TB
SECHEAD["Director of Security /<br/>Head of InfoSec"]
SOCMGR["SOC Manager"]
SECENG["Security Engineers"]
APPSEC["Application Security<br/>Engineers"]
NETSEC["Network Security<br/>Engineers"]
COMP["Compliance & Risk<br/>Analysts"]

SECHEAD --> SOCMGR
SECHEAD --> SECENG
SECHEAD --> APPSEC
SECHEAD --> NETSEC
SECHEAD --> COMP

SOCMGR --> SOCAN["SOC Analysts<br/>(Tier 1, 2, 3)"]
SOCMGR --> THREAT["Threat Hunters"]

click SECHEAD "#executive-overview" "Back to Executive"
click NETSEC "#infrastructure--operations" "See related: Network Ops"
click APPSEC "#engineering" "See related: App Eng"
{{< /mermaid >}}

---

## Governance & Strategy

{{< mermaid align="center" zoom="true" >}}
%%{init: {"flowchart": {"useMaxWidth": false, "nodeSpacing": 40, "rankSpacing": 70, "htmlLabels": true}} }%%
flowchart TB
EARCH["Enterprise Architect"]
GOVAN["IT Governance Analyst"]
POLICY["Policy & Compliance<br/>Officer"]
BCDR["Business Continuity /<br/>Disaster Recovery Specialist"]

EARCH --> GOVAN
EARCH --> POLICY
EARCH --> BCDR

click EARCH "#executive-overview" "Back to Executive"
click POLICY "#security--compliance" "See related: Security"
{{< /mermaid >}}

## 🕵️ Security Analyst

| | Simple Outline | Extended Details |
| :--- | :--- | :--- |
| **Primary Role** | Implements and operates security controls, monitors for threats, and assists with **vulnerability management**. | A hands-on operational role within the CISO's team, focused on the daily defense of the network, systems, and data. |
| **Key Responsibilities** | **Security Information and Event Management (SIEM)** analysis, **penetration testing support**, vulnerability scanning, access control management. | * **Threat Detection:** Analyzing log data and security tool output to identify indicators of compromise (IOCs). * **Patch Management:** Ensuring operating systems and applications have the latest security patches applied. * **Security Awareness Support:** Assisting the CISO in training employees on best practices like phishing recognition. * **Incident Response:** Playing a tactical role during a security incident, helping to contain and eradicate the threat. |
| **Scope & Focus** | **Tactical defense** and ongoing maintenance of the security posture. | Focuses on reducing the attack surface and the timely detection of threats, supporting the strategic goals of the **CISO**. |
| **Key Metrics** | **Vulnerability count** reduction, **time to patch** critical flaws, number of resolved **security tickets**. | |

## ⚖️ Compliance & Risk Officer

| | Simple Outline | Extended Details |
| :--- | :--- | :--- |
| **Primary Role** | **Identifies, assesses, and manages all legal, regulatory, and operational risks** to the company. | A high-level, process-driven role focused on ensuring the organization meets all mandated external standards and internal risk tolerance policies. |
| **Key Responsibilities** | **Risk assessment** framework development, internal **audit management**, policy documentation, **regulatory reporting**. | * **Third-Party Risk Management:** Assessing the security and compliance posture of vendors before signing contracts. * **Policy Creation:** Drafting and updating official security and governance policies (e.g., data retention, acceptable use). * **Audit Response:** Acting as the primary liaison during external compliance audits (e.g., SOX, ISO). * **Training:** Developing and overseeing training to ensure employee adherence to compliance standards. |
| **Scope & Focus** | **Governance, Risk, and Compliance (GRC)** across the entire business. | Works closely with the CISO and CIO. Focuses on **proactive risk mitigation** and the legal/regulatory implications of technology decisions. |
| **Key Metrics** | **Audit pass rate**, number of outstanding **risk findings**, employee **policy awareness score**. | |
