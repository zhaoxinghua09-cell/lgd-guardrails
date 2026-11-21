# Security Policy

## Scope

This repository is part of the LGD / UIBC trust-infrastructure ecosystem. Security
reports are welcome for source code, workflows, and published artifacts.

## Reporting a vulnerability

Please **do not** open a public issue. Use GitHub's private vulnerability reporting:

1. Open the repository **Security** tab.
2. Click **Report a vulnerability**.
3. Describe the issue, the affected path/commit, and a reproduction.

If private reporting is unavailable, open a minimal public issue titled
`security-contact-request` **without technical detail** and a maintainer will open a
private channel.

## What to expect

- Acknowledgement within 7 days.
- A triage decision (accept / needs-more-info / out-of-scope) within 14 days.
- Coordinated disclosure: we publish an advisory after a fix ships.

## Independence clause (evaluation repositories)

`LGD-Eval` is an independent evaluation identity. Evaluation results, scores and
verdicts may not be authored, edited or approved by the project or product
identities under evaluation. Any attempt to route an evaluation through the
evaluated identity is treated as a security-relevant integrity violation and must
be reported through the channel above.

## Out of scope

- Findings that require physical access to a maintainer device.
- Social engineering of maintainers.
- Denial-of-service by volume against third-party services.