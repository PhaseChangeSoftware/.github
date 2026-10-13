# Security Policy

This policy applies to every repository in the **PhaseChangeSoftware** organization that does not
publish its own. It is served by GitHub from the organization's `.github` repository, so it is the
policy a reporter sees on any of our repositories.

## Reporting a vulnerability

**Do not open a public issue, pull request, or discussion for a security vulnerability.**

Report it privately by email to **securityalerts@phasechange.ai**. If the repository has
[private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
enabled, its **Security → Report a vulnerability** form is preferred: it goes straight to the
team that owns the repository and keeps the report attached to it. Email reaches our security
team, who forward it to the owning team.

Please include, as far as you can:

- the repository and the affected version, commit, or deployed environment
- what an attacker can do with it, and what access they need to start
- the steps to reproduce it
- any logs, requests, or proof-of-concept you already have

## What happens next

| Stage | Target |
|---|---|
| We acknowledge your report | 2 business days |
| We confirm or dispute it, and tell you which | 10 business days |
| We agree a remediation timeline with you | on confirmation |

We will keep you updated while we work, and we will tell you when the fix ships. If we decide not
to act on a report, we will say so and explain why rather than letting it go quiet.

## Scope

Anything in a PhaseChangeSoftware repository. Reports about third-party dependencies are welcome,
though we will usually be forwarding them upstream — say so if you have already reported there, so
we do not duplicate your work.

## Disclosure

We ask that you do not publish until a fix has shipped or 90 days have passed since your report,
whichever comes first. If we need longer, we will tell you why and agree it with you. We will
credit you by name in the advisory unless you would rather we did not; tell us which you prefer
when you report.

## Not a vulnerability report?

For anything else — a bug, a question, a support request — open a normal issue in the repository
concerned, or contact the owning team listed in its `CODEOWNERS`.
