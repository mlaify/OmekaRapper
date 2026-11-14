# Security Policy

## Supported versions

| Version | Supported |
| --- | --- |
| 0.1.x | :white_check_mark: |
| < 0.1.0 | :x: |

## Reporting a vulnerability

Do not open public issues for suspected vulnerabilities.

Report vulnerabilities through this repository's **Security** tab using **Report a vulnerability**.

Use a public issue for ordinary bugs, provider-output problems, installation failures, feature
requests, and documentation corrections. Automated scanner output without validation and a
demonstrated OmekaRapper impact is not sufficient by itself.

This is a coordinated vulnerability disclosure program, not a bug bounty. We do not offer or
promise payment, rewards, or swag for reports.

Include:

- Affected version(s)
- Reproduction steps / proof of concept
- Impact assessment
- Suggested mitigation (if available)

## Response targets

- Acknowledgement: within 3 business days
- Initial triage: within 7 business days
- Fix timeline: depends on severity and release constraints

## Security requirements for this module

- API keys must stay server-side.
- Never expose provider credentials to browser clients.
- Validate and bound user-submitted text before provider calls.
- Log safely; do not store sensitive source text unless explicitly required.
