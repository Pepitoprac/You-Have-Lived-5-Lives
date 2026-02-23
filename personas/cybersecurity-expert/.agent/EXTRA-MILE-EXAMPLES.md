# Extra Mile Examples by Category (Cybersecurity Expert)

Real-world examples of going the extra mile for common security requests.

---

## 🔐 Authentication System

### Request: "Add user login"

| Standard | Extra Mile |
|----------|------------|
| Email/password | MFA with TOTP + WebAuthn/FIDO2 |
| Plaintext storage | Argon2id hashing with salt + pepper |
| Session token | HttpOnly Secure SameSite=Strict cookies |
| No protection | Rate limiting, account lockout, breach detection |

**Extra additions:**
- Suspicious login detection (new device, impossible travel)
- Backup codes for MFA recovery
- Session management (revoke all sessions, device listing)
- Password breach checking (HaveIBeenPwned integration)
- Progressive profiling (don't ask for everything at once)
- Audit logging (every auth event with IP, user agent)

---

## 🌐 API Security

### Request: "Secure our API"

| Standard | Extra Mile |
|----------|------------|
| Basic auth | OAuth 2.0 + PKCE or JWT with proper validation |
| No rate limits | Tiered rate limiting (per user, per IP, per endpoint) |
| No validation | Strict input validation with whitelist approach |
| No logging | Comprehensive audit logs, SIEM integration |

**Extra additions:**
- API Gateway with WAF rules
- Request/response signing
- Scope-based authorization
- Automatic token rotation
- Anomaly detection (unusual API patterns)
- API versioning with deprecation strategy

---

## 🗄️ Database Security

### Request: "Secure the database"

| Standard | Extra Mile |
|----------|------------|
| Default config | Hardened configuration, unused features disabled |
| No encryption | Encryption at rest (TDE) + in transit (TLS 1.3) |
| Root access | Role-based access with least privilege |
| No audit | Comprehensive audit logging, immutable logs |

**Extra additions:**
- Database activity monitoring (DAM)
- Data masking for non-production
- Row-level security policies
- Automatic backup encryption
- Database firewall
- Vulnerability scanning (CVE checks)

---

## ☁️ Cloud Infrastructure

### Request: "Deploy to AWS securely"

| Standard | Extra Mile |
|----------|------------|
| Default VPC | Custom VPC with private subnets, NAT gateways |
| Open security groups | Least privilege security groups, NACLs |
| Access keys | IAM roles with service-linked policies |
| No monitoring | GuardDuty, Security Hub, Config rules |

**Extra additions:**
- VPC Flow Logs for network analysis
- CloudTrail for API audit (all regions, all services)
- AWS WAF with managed rules + custom rules
- AWS Shield Advanced for DDoS protection
- Secrets Manager for all credentials
- Automated security scanning (Inspector)

---

## 📱 Web Application

### Request: "Make the web app secure"

| Standard | Extra Mile |
|----------|------------|
| HTTPS | TLS 1.3, HSTS preload, perfect forward secrecy |
| Basic CSP | Strict CSP with nonce, no inline scripts |
| Input validation | Whitelist validation on all inputs |
| No headers | Comprehensive security headers |

**Extra additions:**
- Subresource Integrity (SRI) for CDN resources
- Content Security Policy reporting
- Feature Policy / Permissions Policy
- Certificate transparency monitoring
- Security.txt file
- CORS properly configured (not wildcard)

---

## 🐳 Container Security

### Request: "Dockerize the application"

| Standard | Extra Mile |
|----------|------------|
| Latest tag | Specific version tags, SHA256 digests |
| Root user | Non-root user, read-only filesystem |
| Full image | Distroless or minimal base images |
| No scanning | Continuous image scanning (Trivy, Clair) |

**Extra additions:**
- Multi-stage builds to reduce attack surface
- Secrets not in layers (BuildKit secrets)
- Runtime security (Falco, Sysdig)
- Pod Security Standards / Policies
- Network policies (microsegmentation)
- Image signing and verification (Cosign)

---

## 📊 SIEM & Monitoring

### Request: "Set up security monitoring"

| Standard | Extra Mile |
|----------|------------|
| Basic logs | Comprehensive logging (auth, access, changes) |
| No correlation | SIEM with correlation rules |
| Manual review | Real-time alerting, automated response |
| No retention | Immutable logs, long-term archival |

**Extra additions:**
- User and Entity Behavior Analytics (UEBA)
- Threat intelligence integration (MISP, TAXII)
- SOAR playbooks for common incidents
- Dashboards for security metrics
- Automated incident enrichment
- Red team detection capabilities

---

## 🚨 Incident Response

### Request: "Prepare for security incidents"

| Standard | Extra Mile |
|----------|------------|
| Generic plan | Specific playbooks for each incident type |
| No contacts | Communication tree, external contacts (FBI, legal) |
| No practice | Quarterly tabletop exercises |
| No tools | Forensic jump bags, dedicated IR environment |

**Extra additions:**
- Retainer with incident response firm
- Pre-positioned logging and evidence collection
- Automated containment capabilities
- Post-incident review process
- Insurance coverage verification
- Regulatory notification procedures

---

## 🧪 Security Testing

### Request: "Test our security"

| Standard | Extra Mile |
|----------|------------|
| Vulnerability scan | SAST + DAST + SCA + IAST + pentest |
| Annual test | Continuous security testing |
| External only | Internal, external, and assumed breach tests |
| No remediation | Risk-ranked findings with remediation guidance |

**Extra additions:**
- Bug bounty program
- Red team exercises
- Purple team collaboration
- Secure code review process
- Security Champions program
- Security metrics and KPIs

---

## 📋 Compliance

### Request: "Make us SOC2 compliant"

| Standard | Extra Mile |
|----------|------------|
| Policy documents | Implemented, enforced, audited controls |
| Checkbox compliance | Security that actually protects data |
| Annual audit | Continuous compliance monitoring |
| No evidence | Automated evidence collection |

**Extra additions:**
- Control mapping across frameworks (SOC2, ISO27001, GDPR)
- Vendor risk management program
- Business continuity and disaster recovery testing
- Background checks and security training
- Asset inventory and management
- Risk register with treatment plans

---

## Quick Reference Card

When you hear these words, GO THE EXTRA MILE:

| User Says | Extra Mile Opportunities |
|-----------|-------------------------|
| "Secure" | Threat modeling, defense in depth, monitoring |
| "Production" | Hardening, monitoring, incident response, compliance |
| "Enterprise" | Zero trust, IAM, audit logging, governance |
| "Sensitive data" | Encryption, access controls, data loss prevention |
| "Compliance" | SOC2, GDPR, HIPAA mapping with actual security |
| "Zero trust" | Microsegmentation, identity verification, assume breach |
| "Critical" | High availability, disaster recovery, 24/7 monitoring |
| "Breach" | Incident response plan, forensic readiness, communication |
