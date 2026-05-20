# Smart Home IoT Risk Assessment

## Project Overview
A comprehensive risk assessment of a typical smart home IoT environment, focusing on **Governance, Risk, and Compliance (GRC)** aspects. This project identifies security risks associated with common IoT devices (smart cameras, lights, thermostats, voice assistants, etc.) and provides practical mitigation controls aligned with industry standards.

**Status:** Completed  
**Focus Area:** IoT Security, Risk Assessment, Security Controls

## Objectives
- Identify key security risks in a smart home IoT ecosystem
- Assess risks using a structured risk assessment methodology
- Recommend appropriate technical and governance controls
- Ensure compliance with relevant standards and best practices
- Demonstrate practical GRC skills in the IoT domain

## Scope
**In Scope:**
- Smart cameras, smart speakers, smart lighting, thermostats, and smart locks
- Network communication (Wi-Fi, Bluetooth, Zigbee)
- Cloud services and mobile applications
- User access and data privacy concerns

**Out of Scope:**
- Physical security of devices
- Firmware reverse engineering
- Advanced penetration testing

## Methodology
- Asset identification and inventory
- Threat modeling (STRIDE)
- Risk assessment using **Likelihood × Impact** matrix
- Control recommendations based on **NIST Cybersecurity Framework** and **ISO 27001**
- Gap analysis against GDPR data protection principles

## Key Risks Identified

### High Risk
- Weak default credentials and lack of strong authentication
- Insecure local network communication (unencrypted protocols)
- Excessive data collection and privacy leakage to cloud providers
- Insecure remote access and exposed device APIs

### Medium Risk
- Firmware update vulnerabilities
- Inadequate device segmentation on home networks
- Third-party vendor supply chain risks
- Account takeover via mobile app weaknesses

### Low Risk
- Physical tampering (if basic physical security is applied)

## Risk Assessment Summary
| Risk | Likelihood | Impact | Risk Level | Recommended Priority |
|------|------------|--------|------------|----------------------|
| Weak Authentication | High | High | Critical | Immediate |
| Data Privacy Leakage | High | Medium | High | High |
| Unencrypted Communications | Medium | High | High | High |
| Firmware Vulnerabilities | Medium | Medium | Medium | Medium |

## Recommended Controls
- Implement strong password policies and MFA where possible
- Network segmentation (separate IoT VLAN)
- Regular firmware updates and vulnerability management
- Disable unnecessary cloud features and review data sharing permissions
- Use of secure communication protocols (TLS 1.3, WPA3)
- Regular security audits and device inventory maintenance

## Standards & Frameworks Referenced
- ISO 27001:2013 (Annex A controls)
- NIST Cybersecurity Framework (Identify, Protect, Detect)
- OWASP IoT Security Guidance
- GDPR (data minimization and consent)

## Conclusion
This project highlights the significant security and privacy challenges posed by consumer IoT devices and demonstrates the importance of applying structured GRC practices even in home environments. The recommended controls provide a practical roadmap for improving smart home security posture.

---

**Files in this folder:**
- Smart-Home-Risk-Assessment-Report.pdf
- Threat-Model-Diagram.png
- Risk-Register.xlsx
- Control-Implementation-Guide.md
