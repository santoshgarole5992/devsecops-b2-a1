# Security Policy

## Supported Versions

We release security updates for the latest version of this project. Please ensure you are using the most recent release.

| Version | Supported          |
| ------- | ------------------ |
| latest  | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability, please **do not create a public issue**. Instead, report it privately by emailing santoshgarole5992@gmail.com or via GitHub's [private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability).

We will respond as soon as possible and work with you to resolve the issue.

## Security Practices

This project follows security best practices, including:

- **No secrets or credentials are stored in the repository.**
- **Dependencies are regularly updated and scanned for vulnerabilities.**
- **Automated security checks are run on every push, pull request, and weekly via GitHub Actions.**

## Automated Security Checks

Our CI/CD pipeline includes the following security checks:

- **Static Code Analysis:** CodeQL scans for code vulnerabilities.
- **Dependency Scanning:** `pip-audit` checks for vulnerable Python dependencies.
- **Secure Code Linting:** Bandit analyzes Python code for security issues.
- **Secret Scanning:** Gitleaks detects accidentally committed secrets.
- **Docker Image Scanning:** Trivy scans Docker images for vulnerabilities.

Reports from these checks are available as workflow artifacts in GitHub Actions.

## Responsible Disclosure

We appreciate responsible disclosure of security issues. Please give us a reasonable time to address any findings before public disclosure.

---

**Thank you for helping keep this project secure!** 