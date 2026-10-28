# Security Policy

## Reporting a Vulnerability

Please do not open a public issue for security problems.

Report vulnerabilities privately through GitHub: go to the repository's **Security** tab and click **Report a vulnerability**. A maintainer will reply as soon as possible.

Include as much as you can:

- What the issue is and where it lives (file, route, or page)
- Steps to reproduce it
- What an attacker could do with it

## Secrets

Never commit real credentials. Local secrets belong in `.env`, which Git ignores. Use `.env.example` for placeholder values only.
