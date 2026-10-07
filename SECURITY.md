# Security policy

This policy applies to every public repository under [rolandzeiner](https://github.com/rolandzeiner) that has no `SECURITY.md` of its own.

## Supported versions

Only the latest release of each project receives security fixes. If you're on an older version, please update and check whether the problem is still there before you report it.

## Reporting a vulnerability

Please don't open a public issue or pull request for a security problem.

Report it privately through GitHub instead. Each link opens the report form for that project:

- [badegewaesser-austria](https://github.com/rolandzeiner/badegewaesser-austria/security/advisories/new)
- [ladestellen-austria](https://github.com/rolandzeiner/ladestellen-austria/security/advisories/new)
- [linz-linien-austria](https://github.com/rolandzeiner/linz-linien-austria/security/advisories/new)
- [nextbike-austria](https://github.com/rolandzeiner/nextbike-austria/security/advisories/new)
- [orrery-card](https://github.com/rolandzeiner/orrery-card/security/advisories/new)
- [spinning-wheel-card](https://github.com/rolandzeiner/spinning-wheel-card/security/advisories/new)
- [tankstellen-austria](https://github.com/rolandzeiner/tankstellen-austria/security/advisories/new)
- [webcam-timelapse](https://github.com/rolandzeiner/webcam-timelapse/security/advisories/new)
- [wiener-linien-austria](https://github.com/rolandzeiner/wiener-linien-austria/security/advisories/new)

You need to be signed in to GitHub. Only you and the maintainer can see the report.

For a repository that isn't listed, open its **Security** tab, choose **Advisories**, and click **Report a vulnerability**. If the button is missing, open an issue that asks for a private contact and leave the details out.

A good report includes:

- the project and its version, plus the Home Assistant version if it matters
- what an attacker could do, and what access they would need first
- steps to reproduce, or a proof of concept

## What happens next

These projects are maintained by one person, so replies are best effort. I'll acknowledge your report, tell you whether I can reproduce it, and keep you posted while I work on a fix. Once the fix is released I'll publish the advisory and credit you, unless you'd rather not be named.

## Scope

In scope is the code in these repositories: the integrations, the Lovelace cards, and the build and release workflows.

Out of scope, and best reported to their own maintainers:

- Home Assistant itself (see [Home Assistant's security page](https://www.home-assistant.io/security/))
- HACS
- the third-party services these projects read data from
