# Cybersecurity Expert - 5 Lives Skill

> **"Build fortresses, not fences. Defend what matters."**

## Overview

The **Cybersecurity Expert** persona channels 5 master defenders to build security systems that don't just check compliance boxes—they withstand real attacks from determined adversaries.

## The 5 Lives

| Life | Title | Identity | Superpower |
|:----:|-------|----------|------------|
| 🎯 | **The Pentester** | *The Ethical Hacker* | Offensive security, vulnerability discovery, red teaming |
| 🏰 | **The Security Architect** | *The Fortress Builder* | Defense in depth, zero trust, secure by design |
| 👔 | **The CISO** | *The Risk Commander* | Risk management, compliance, business alignment |
| 🚨 | **The Incident Responder** | *The Digital First Responder* | DFIR, breach containment, recovery |
| 🔎 | **The Threat Hunter** | *The Proactive Defender* | Behavioral analytics, APT detection, threat intel |

## Installation

Copy these files into your project root:

```bash
cp -r /path/to/cybersecurity-expert/* ./
```

## Usage

### Command Line

```bash
codex --yolo --system-prompt .agent/system-prompt.md \
  "Using an ExecPlan, build a secure authentication system"
```

### Example Prompts

```bash
# Secure architecture
codex --yolo -p "Using an ExecPlan, design a zero-trust architecture 
for a fintech application with threat modeling"

# Application security
codex --yolo -p "Using an ExecPlan, secure this API against OWASP Top 10 
with defense in depth strategy"

# Compliance
codex --yolo -p "Using an ExecPlan, implement SOC2-compliant security 
controls with monitoring and incident response"

# Cloud security
codex --yolo -p "Using an ExecPlan, harden AWS infrastructure 
with IAM policies, encryption, and network security"
```

## Key Capabilities

- **Offensive Security**: Pentesting, vulnerability assessment, exploit chains
- **Secure Architecture**: Zero trust, defense in depth, microsegmentation
- **Application Security**: OWASP Top 10, secure coding, SAST/DAST
- **Cloud Security**: AWS/Azure/GCP hardening, container security
- **Network Security**: Firewalls, IDS/IPS, VPNs, segmentation
- **Identity & Access**: IAM, MFA, PAM, RBAC, least privilege
- **Cryptography**: Encryption, PKI, key management, zero-knowledge
- **Compliance**: SOC2, ISO27001, GDPR, HIPAA, PCI-DSS
- **Incident Response**: DFIR, playbooks, tabletop exercises
- **Security Operations**: SIEM, threat hunting, vulnerability management

## What Makes This Different

| Standard Security Advice | 5 Lives Security |
|:-------------------------|:-----------------|
| "Use strong passwords" | "Implement MFA with TOTP/WebAuthn, enforce password policies, monitor for breaches, implement account lockout" |
| "Validate inputs" | "Threat model all inputs, whitelist validation, output encoding, parameterized queries, WAF rules, behavioral monitoring" |
| "Encrypt data" | "Encryption at rest with KMS, TLS 1.3 in transit, field-level encryption for PII, key rotation, HSM integration" |
| "We have a firewall" | "Defense in depth: WAF, API gateway, network segmentation, microsegmentation, IDS/IPS, behavioral analytics" |

## Go The Extra Mile

When you use keywords like "secure," "production," or "enterprise," the Cybersecurity Expert:

1. **Performs threat modeling** (STRIDE, Attack Trees)
2. **Implements defense in depth** (7+ overlapping controls)
3. **Adds comprehensive monitoring** (logging, detection, alerting)
4. **Documents incident response** (playbooks, communication)
5. **Ensures compliance** (SOC2, GDPR, ISO27001)

## Quality Triggers

Activate full security mode with: secure, production, enterprise, sensitive, compliant, hardened, zero trust

---

**Built with the 5 Lives framework**  
*A joint creation by [Kimi.com](https://kimi.com) × [LivingAI.blog](https://livingai.blog) & The Community*

**Trust no one. Verify everything. Defend always.**
