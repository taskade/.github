# Security Policy

This policy applies to every Taskade repository that does not publish its own.

## Reporting a vulnerability

**Do not open a public issue, pull request, or Discussion for a security problem.**
These repositories are public, so a report filed in one is visible to everyone,
including anyone who would rather exploit the issue than see it fixed.

Use one of these private channels instead:

| Channel | Where |
| --- | --- |
| Preferred | The repository's **Security** tab, then **Report a vulnerability**. Private between you and our maintainers. |
| Email | [support@taskade.com](mailto:support@taskade.com), monitored by our support team and routed to engineering. |

Helpful reports include what you found, the steps to reproduce it, the impact you
believe it has, and anything you already tried. Please stay inside your own test
account while investigating.

## What to expect

The full policy, including safe harbor and disclosure terms, is published at
[taskade.com/security](https://www.taskade.com/security). In short:

- **Response time.** We are a small team and do not guarantee one. Reports go to a
  monitored mailbox and are routed to engineering. Complex reports take longer to triage.
- **Disclosure.** 90-day coordinated disclosure when feasible, subject to investigation
  requirements. Please give us a reasonable window before going public.
- **Rewards.** We do not run a bug bounty program and do not pay for vulnerability
  reports, in cash, gift cards, subscription credit or any equivalent. This applies to
  every report, however severe. What we offer is that we read it, act on what is valid,
  and tell you what we decided.
- **Safe harbor.** If you act in good faith, stay within your own test account, and give
  us reasonable time to fix an issue, we will not pursue legal action against you for
  that research. We cannot waive claims belonging to our customers or other third parties.
- **Recognition.** On request, we credit you by name in the disclosure thread once a fix
  ships. We do not maintain a public researcher listing or hall of fame.

If [taskade.com/security](https://www.taskade.com/security) and this file ever disagree,
the published policy is the one that applies.

## Scope

Report vulnerabilities in the **Taskade product**: the web app, the mobile and desktop
apps, the public API, Taskade Genesis apps, AI agents, and the published packages and
servers in these repositories.

A broken link, a wrong price in a table, or an outdated screenshot is a documentation
bug, not a vulnerability. Open a normal issue for those.

## Not a vulnerability report?

- **Product bugs and account questions:** [taskade.com/contact](https://www.taskade.com/contact)
- **Anything specific to one repository:** open an issue there

## Never commit secrets

These repositories are public and secret scanning with push protection is enabled. Do
not commit `.env` files, API tokens, private keys, or customer data, and use placeholder
values in every example. If you do commit a credential, rotate it immediately, then see
[GitHub: removing sensitive data](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository).

Generate and revoke your own API tokens at
[taskade.com/settings/api](https://www.taskade.com/settings/api).
