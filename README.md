<h1 align="center"> VulnHub </h1>

<p align="center">
    <img src="docs/vulnhub-logo.jpg" alt="Jangow 1.0.1" width="600">
</p>

<p align="center">
    <img src="https://img.shields.io/badge/VulnHub-1A2332?style=for-the-badge&logo=linuxcontainers&logoColor=white"/>
    <img src="https://img.shields.io/badge/Offensive%20Security-%23000000?style=for-the-badge&logo=kalilinux&logoColor=white"/>
    <img src="https://img.shields.io/badge/Penetration%20Test-FF0000?style=for-the-badge&logo=hackaday&logoColor=white"/>
</p>

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
| [Jangow 1.0.1](jangow/jangow-pentest-report.md) | Easy | OS Command Injection, Credential Reuse, CVE-2021-4034 (PwnKit) |
| [Metasploitable2](metasploitable2/metasploitable2-pentest-report.md) | Easy | vsftpd 2.3.4 Backdoor (CVE-2011-2523) |