# Security Policy

## Supported Versions

OpenStateStack is under **active development**. Only the following branches receive security updates:

| Branch    | Status           | Security Support |
| --------- | ---------------- | ---------------- |
| `main`    | Stable releases  | ✅ Full support   |
| `develop` | Active dev       | ✅ Full support   |
| others    | Feature branches | ❌ No support     |


## Reporting a Vulnerability
Because OpenStateStack underpins **sovereign digital infrastructure**, all security issues must be handled responsibly and privately.

* **Do NOT** create a public GitHub issue for security vulnerabilities.
* **Instead**, report vulnerabilities directly via email:
  📧 **[security@openstatestack.io](mailto:security@openstatestack.io)**

When reporting, please include:

1. A clear description of the vulnerability.
2. Steps to reproduce (if possible).
3. Potential impact (e.g., data exposure, denial of service, privilege escalation).
4. Any suggested mitigations.

## Security Response Process

1. **Acknowledgement** – We will confirm receipt of your report within **48 hours**.
2. **Assessment** – The core security team will review and triage the issue.
3. **Mitigation** – A fix will be developed in a private branch and validated.
4. **Deployment** – Fixes will be merged into supported branches and rolled out.
5. **Disclosure** – A coordinated security advisory will be published once mitigation is in place.

## Scope of Coverage

The following areas are in scope for responsible disclosure:

* Core OpenStateStack codebase (identity, payments, registries, messaging, data-exchange).
* Zero-knowledge proof circuits and cryptographic primitives.
* API endpoints and authentication/authorization layers.
* Deployment tooling and infrastructure configurations (if OSS-related).

Out of scope:

* Attacks requiring physical access to servers or devices.
* Social engineering attacks against maintainers, contributors, or partners.
* Third-party dependencies not maintained by OpenStateStack (though we welcome reports if you believe they impact us).


## Recognition

We greatly value the security research community.
* Valid reports may be acknowledged in our **Hall of Fame** (unless anonymity is requested).
* Monetary rewards may be available through our **bug bounty program** (details to be published by the Foundation).


## Contact
For urgent security matters:
📧 **[security@openstatestack.io](mailto:security@openstatestack.io)**
🔒 PGP key:  [Download](./oss-security-public.asc)
Fingerprint: `FC34 D56C 1B92 68C2 6882 B61A 09F2 7015 6CA1 4441`
