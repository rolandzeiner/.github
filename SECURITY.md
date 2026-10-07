# Security policy

This policy applies to every public repository under [rolandzeiner](https://github.com/rolandzeiner) that has no `SECURITY.md` of its own.

## Supported versions

Only the latest release of each project receives security fixes. If you're on an older version, please update and check whether the problem is still there before you report it.

## Reporting a vulnerability

Please don't open a public issue or pull request for a security problem.

Report it privately instead:

1. Open the **Security** tab of the affected repository.
2. Click **Report a vulnerability**.
3. Fill in the form. Only you and the maintainer can see the report.

If the button is missing, open an issue that asks for a private contact and leave the details out.

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
