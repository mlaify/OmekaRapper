# Security reporting

This repository follows the
[mlaify organization-wide security reporting policy](https://github.com/mlaify/.github/blob/main/SECURITY.md).
That policy defines the reporting channel, maintainer limits, unsupported environments, and the
absence of payment, rewards, swag, response commitments, or remediation commitments.

## Supported versions

| Version | Supported |
| --- | --- |
| 0.1.x | :white_check_mark: |
| < 0.1.0 | :x: |

## Project-specific reporting details

Use this repository's **Security** tab and select **Report a vulnerability** for a credible,
confidential vulnerability in OmekaRapper. Use a public issue for ordinary bugs,
provider-output problems, installation failures, feature requests, and documentation corrections.

Include the affected version, safe reproduction steps, realistic impact, and a suggested
mitigation if one is available.

## Security requirements for this module

- API keys must stay server-side.
- Never expose provider credentials to browser clients.
- Validate and bound user-submitted text before provider calls.
- Log safely; do not store sensitive source text unless explicitly required.
