# Security Policy

This policy covers every repository in the [TomatoPHP](https://github.com/tomatophp) organization unless a repository ships its own `SECURITY.md`.

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest major release of each package | Yes, security fixes and bug fixes |
| Previous major release, when the package README lists it under *Compatibility* | Yes, security fixes only |
| Older releases | No |

Security fixes are released as a patch version on every supported line. Please upgrade to the latest patch release of your line.

## Reporting a Vulnerability

**Please do not open a public issue, discussion or pull request for security problems.**

Report privately through one of these channels:

1. **GitHub private vulnerability reporting** (preferred): open the repository's **Security** tab and click **Report a vulnerability**.
2. **Email**: [engfadymondy@gmail.com](mailto:engfadymondy@gmail.com) with the subject `SECURITY: <package name>`.

Please include:

- the package and version (or commit) affected;
- a description of the issue and its impact;
- steps or a proof of concept to reproduce it;
- any suggested fix, if you have one.

## What to Expect

| Step | Target time |
|------|-------------|
| Acknowledge your report | within 3 business days |
| Confirm the issue and share an initial assessment | within 7 days |
| Release a fix for critical / high severity issues | within 30 days |
| Release a fix for medium / low severity issues | within 90 days |

We keep you updated while we work on the fix. We publish a GitHub Security Advisory once the fixed version is available, request a CVE when appropriate, and credit you as the reporter unless you prefer to stay anonymous.

We ask that you keep the details private until the fix is released and the advisory is published. We follow a 90-day coordinated disclosure window by default and will agree on a different date with you if needed.

## Scope

In scope: code in TomatoPHP repositories and the packages published from them on Packagist.

Out of scope: vulnerabilities in third-party dependencies (please report them upstream), issues that need a compromised server or admin account, and missing hardening that has no demonstrated security impact.
