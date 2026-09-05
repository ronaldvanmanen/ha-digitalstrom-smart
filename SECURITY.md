# Security Policy

Woon IoT BV takes security reports seriously. This policy implements Annex I, Part II (5) of
Regulation (EU) 2024/2847 (Cyber Resilience Act).

## Reporting a vulnerability

Mail **security@wooniot.nl**. Please include, where you can:

- the component or endpoint involved,
- the steps that show the problem,
- what you believe the impact is.

Encrypted reporting is possible — ask for our key in a first message.

Please do **not** open a public GitHub issue for a security problem. Use the mail address above,
or GitHub's private [security advisory](https://github.com/wooniot/ha-digitalstrom-smart/security/advisories/new)
form.

## What you can expect from us

| When | What |
|------|------|
| Within 72 hours | We confirm receipt and name a contact person. |
| Within 10 working days | We tell you whether we confirm the finding and how we assess it. |
| Until resolved | We keep you informed. |

A fix is released as soon as it is available. Because this integration is distributed through
HACS, users choose when to install it, so we mark security-relevant releases as such in the
release notes.

We are happy to credit you by name in the advisory — or leave you out. Your call.

## What we ask of you

- Give us reasonable time to fix the problem before disclosing it publicly. We work to a 90-day
  guideline and will talk to you if something takes longer.
- Do not access or modify other people's data, and do not disrupt anyone's installation.
- Do not run automated attacks that put availability at risk.

If you report in good faith and stay within these lines, we will not pursue legal action.

## Reporting to the authorities

Actively exploited vulnerabilities and severe incidents are reported to the designated CSIRT and
ENISA under Article 14 of the regulation: an early warning within 24 hours, a notification within
72 hours, and a final report within the applicable deadline. **These obligations apply from
11 September 2026.**

## Out of scope

Missing best practices without demonstrable impact, unverified output from automated scanners,
and issues that only occur on outdated or unpatched systems belonging to the user.

## Supported versions

| Version | Supported |
|---------|-----------|
| 4.2.x | Yes |
| < 4.2 | Please update first |

Security updates are provided for at least five years after a version is placed on the market,
in line with Article 13(8).

## Compliance dossier

The full dossier — EU Declaration of Conformity, technical documentation, risk assessment and
software bill of materials — is published and live-verifiable:

**https://dev.cra-portal.eu/verify.html?p=21**
