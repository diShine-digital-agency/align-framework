# Security policy

The ALIGN framework is a documentation-only repository — it contains markdown templates, guides, and a single client-side HTML tool. There is no server-side code, no database, and no authentication layer.

That said, we take the integrity of the materials seriously and appreciate responsible reporting of any issues.

---

## Scope

The following items are in scope for security reports:

- **Cross-site scripting (XSS) or other client-side vulnerabilities** in `tools/align-navigator.html`.
- **Malicious or misleading links** embedded in any markdown file.
- **Accidental exposure of sensitive data** (API keys, credentials, personal information) in any committed file or asset.

The following items are out of scope:

- Typos, formatting issues, or content disagreements (please open a regular issue for those).
- Vulnerabilities in third-party services linked from the documentation (e.g., analytics tools mentioned in the KPI dashboard).

---

## Reporting a vulnerability

If you discover a security issue, please report it privately rather than opening a public issue.

**Email:** kevin@dishine.it

Include the following in your report:

1. A description of the vulnerability and its potential impact.
2. Steps to reproduce the issue.
3. The affected file(s) and, if possible, a suggested fix.

We aim to acknowledge reports within 48 hours and to resolve confirmed issues within 7 days.

---

## Disclosure

We follow a coordinated disclosure approach. Once a fix has been merged, we will credit the reporter in the changelog unless they prefer to remain anonymous.
