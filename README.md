# Open Threat Intelligence Repository 🛡️

Welcome to my public threat intelligence repository. This space is dedicated to sharing actionable insights, indicators of compromise (IOCs), threat actor profiling, and defensive countermeasures derived from ongoing threat intelligence research and incident analysis.

---

## 📌 Repository Overview

The objective of this repository is to contribute to the collective defense of the cybersecurity community by publishing timely, high-fidelity threat data. Whether you are a security analyst, incident responder, or threat hunter, you can leverage these artifacts to harden your defenses and improve detection capabilities.

```
├── analysis/           # Deep-dive reports, TTP mappings, and threat actor profiles
├── iocs/               # Structured Indicators of Compromise (JSON, CSV, STIX/TAXII)
├── sigma/              # Sigma rules for SIEM log correlation and threat detection
├── yara/               # YARA detection rules for malware and threat actors
```

---

## 📂 Directory Structure & Usage

### 1. Threat Analysis Reports (`/analysis`)
In-depth write-ups covering recent campaigns, malware families, and threat actor (APT/financially motivated) TTPs mapped to the **MITRE ATT&CK® Framework**.

### 2. Detection Rules (`/yara` & `/sigma`) - Comming Soon
Ready-to-use detection signatures to help identify malicious activity within your environment.
*   **YARA Rules:** Located in `/yara`. Designed for file scanning and memory forensics.
*   **Sigma Rules:** Located in `/sigma`. Generic signature format for SIEM platforms (Splunk, Elastic, Microsoft Sentinel, etc.).

### 3. Indicators of Compromise (`/iocs`) - Comming Soon
This directory contains raw and structured IOCs categorized by campaign or incident date.
*   **Format:** CSV, JSON, and STIX 2.1 compatible formats.
*   **Data Types:** IP addresses, domains, URLs, file hashes (SHA256/MD5), and email addresses.
*   *Note:* All IOCs undergo a validation process to minimize false positives before publication.

---

## ⚠️ Disclaimer & Terms of Use

*   **For Defensive Purposes Only:** The materials provided in this repository are intended solely for defensive security, threat hunting, incident response, and educational purposes.
*   **No Warranty:** Intelligence is provided "as is" without warranty of any kind. Always validate IOCs and test detection rules in a non-production environment before deploying them enterprise-wide.
*   **Attribution:** If you reference or utilize data from this repository in your own research, public reports, or tooling, please provide appropriate attribution and link back to this repository.