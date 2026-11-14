# Security Policy

The Ministry of Health and Child Care (MOHCC) Zimbabwe takes the security of
its software and the data it may process — including health information —
seriously. This policy applies to all repositories in this organization that
do not define their own `SECURITY.md`.

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues,
discussions, or pull requests.**

Instead, report privately by email:

- **Primary contact:** ichihwai@mohcc.org.zw (Developer/Maintainer)
- **Escalation:** tchawurura@mohcc.org.zw (Director of ICT) — use if the primary
  contact is unreachable or the matter requires Directorate-level decision.

When reporting, please include:

- A description of the vulnerability and its potential impact.
- Steps to reproduce it, or a proof of concept.
- The affected repository, branch/commit, and environment (if known).
- Whether the issue may affect patient or other sensitive health data.

## What to expect

- Acknowledgement of your report within **5 working days**.
- An initial assessment of severity and next steps within **10 working days**.
- Coordinated disclosure: we ask reporters not to publicly disclose a
  vulnerability until a fix has been released or 90 days have passed,
  whichever comes first, unless otherwise agreed.

## Scope

This policy covers code and configuration in repositories under the
`mohcc-zw` organization. It does not cover third-party services, dependencies
upstream of our code, or infrastructure not managed by MOHCC — please report
those to the relevant vendor.

## A note on the contact address

The contacts above are individual MOHCC ICT Directorate staff email
addresses. Before this organization is used for production or sensitive
health-data systems, the Directorate should consider assigning a shared
security mailbox so disclosure handling does not depend on any one person's
availability.
