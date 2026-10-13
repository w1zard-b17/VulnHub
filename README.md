# VulnHub

![Pentest](https://img.shields.io/badge/Penetration%20Test-FF0000?style=for-the-badge&logo=hackaday&logoColor=white)
![VulnHub](https://img.shields.io/badge/VulnHub-1A2332?style=for-the-badge&logo=linuxcontainers&logoColor=white)

A personal collection of penetration testing write-ups for [VulnHub](https://www.vulnhub.com/) virtual machines, done for hands-on practice.

Each write-up documents the full process for a given machine — reconnaissance, enumeration, exploitation, and privilege escalation — along with the reasoning behind each step, not just the final commands. The goal is to build a reusable reference for common attack patterns and techniques across different boxes.

## Structure

Each machine gets its own markdown report, typically named after the target (e.g. `jangow-pentest-report.md`), covering:

- Target information and scope
- Reconnaissance and service enumeration
- Vulnerability discovery
- Exploitation steps
- Privilege escalation
- Root cause analysis and remediation recommendations

## Write-ups

| Machine | Difficulty | Key Vulnerabilities |
|---------|-----------|----------------------|
| [Jangow 1.0.1](jangow-pentest-report.md) | Easy | OS Command Injection, Credential Reuse, CVE-2021-4034 (PwnKit) |