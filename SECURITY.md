# Security Policy

## Reporting a Vulnerability

We take security seriously and appreciate your efforts to responsibly disclose vulnerabilities.

**Please do NOT open a public issue for security vulnerabilities.**

### Reporting Process

1. **Email your report** to **security@citizenweather.org** with:
   - Description of the vulnerability
   - Steps to reproduce (if applicable)
   - Potential impact and severity
   - Suggested fix (if you have one)
   - Your contact information

2. **Include these details**:
   - Affected project(s) and version(s)
   - Environment details (OS, runtime, dependencies)
   - Proof of concept or logs
   - Any relevant attachments

3. **What happens next**:
   - We'll acknowledge receipt within 48 hours
   - We'll investigate and keep you informed of progress
   - We'll work with you on a fix timeline
   - We'll coordinate disclosure once fixed

### Responsible Disclosure Guidelines

- **Do not** publicly disclose the vulnerability until we've had time to fix it
- **Do not** exploit the vulnerability beyond what's necessary to demonstrate it
- **Do not** access data beyond what's needed to confirm the issue
- **Do not** disrupt service or harm users
- **Allow reasonable time** (typically 90 days) for fixes before public disclosure
- **Contact us privately first** before contacting other parties

## Security Best Practices

### For Users

- Keep your dependencies up to date
- Use the latest stable versions
- Monitor security advisories
- Enable security features in your deployment
- Use environment variables for sensitive data
- Follow the principle of least privilege

### For Contributors

- Never commit secrets, API keys, or credentials
- Use `.gitignore` for sensitive files
- Review code for common vulnerabilities
- Run security tools locally (SAST, dependency scanners)
- Use secure coding practices
- Follow dependency management guidelines

### For Maintainers

- Enable branch protection on main branches
- Require code reviews before merging
- Use automated security scanning (CodeQL, SAST tools)
- Monitor dependencies with Dependabot
- Keep frameworks and libraries updated
- Review and audit access permissions regularly
- Archive or deprecate old projects
- Communicate security updates clearly

## Supported Versions

| Version | Status | Security Updates | End of Life |
|---------|--------|-----------------|-------------|
| 1.x | Current | Yes | TBD |
| < 1.0 | Legacy | Critical Only | TBD |

## Security Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [CWE/SANS Top 25](https://cwe.mitre.org/top25/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [GitGuardian Blog](https://blog.gitguardian.com/)

## Automated Security Scanning

This organization uses:
- **GitHub CodeQL** — Static application security testing
- **Dependabot** — Dependency vulnerability scanning
- **GitHub Secret Scanning** — Prevents secret leaks
- **Branch Protection** — Enforces code review before merge

## Contact

- **Security Issues**: security@citizenweather.org
- **Code of Conduct Issues**: conduct@citizenweather.org
- **General Questions**: hello@citizenweather.org

---

Thank you for helping keep CitizenWeather secure! 🔐
