<img width="2580" height="1664" alt="Attach Chain Summary" src="https://github.com/user-attachments/assets/d81a28ad-581d-4885-8e9e-5dd3dfd4b49c" />
# UnrealIRCd 3.2.8.1 Penetration Testing Case Study

## Overview

This repository contains a cybersecurity lab case study focused on penetration testing against UnrealIRCd 3.2.8.1 running on a Metasploitable3 laboratory environment.

The purpose of this project is to document the penetration testing process, including reconnaissance, vulnerability identification, initial access validation, post-exploitation analysis, privilege escalation validation, impact analysis, and mitigation recommendations.

## Scope

- Environment: Metasploitable3 Lab
- Target Service: UnrealIRCd 3.2.8.1
- Main Vulnerabilities:
  - CVE-2010-2075 - UnrealIRCd Backdoor Command Execution
  - CVE-2021-4034 - PwnKit Local Privilege Escalation
- Testing Type: Cybersecurity Lab Case Study / Penetration Testing Exercise

## Methodology

The testing process includes:

1. Reconnaissance
2. Service Enumeration
3. Vulnerability Identification
4. Initial Access Validation
5. Post-Exploitation
6. Privilege Escalation Analysis
7. Impact Analysis
8. Mitigation Recommendation

## Key Findings

- UnrealIRCd service was identified on the target system.
- CVE-2010-2075 was used to validate initial access in a controlled lab environment.
- Post-exploitation enumeration identified potential local privilege escalation paths.
- CVE-2021-4034 was validated as a local privilege escalation vulnerability in the lab environment.
- The case study demonstrates how multiple vulnerabilities can form an attack chain.

## Report

The full report is available in PDF format:

./Muhammad-Ganjar-Maulana-UnrealIRCd-Pentest-Case-Study.pdf

## Disclaimer

This project was conducted in a controlled laboratory environment using Metasploitable3. It is intended for educational, research, and cybersecurity awareness purposes only.

No testing was conducted against production systems, public networks, or third-party assets without authorization.


