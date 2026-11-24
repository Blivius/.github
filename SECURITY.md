# Security policy

This policy covers every Blivius repository that doesn't have its own `SECURITY.md`. Where a
repository has one, that file wins.

## Reporting a vulnerability

**Do not open a public issue, discussion or pull request for a vulnerability.**

Report it privately, in this order of preference:

1. On the affected repository, through **Security → Report a vulnerability** (GitHub private
   vulnerability reporting).
2. By email to **security@blivius.com**, if the repository doesn't offer private reporting or you
   can't tell which repository is affected.

Include what you can of:

- the repository, and the version or commit;
- how it runs (binary, container image, package, Homebrew formula);
- steps to reproduce;
- what an attacker gains, and what they need first.

## What happens next

| | Within |
| --- | --- |
| Acknowledgement | 3 business days |
| Initial assessment: confirmed or not, and severity | 7 days |
| A fix, or a plan with a date, for a critical or high issue | 30 days |

A confirmed issue is fixed privately, released, and then disclosed in a GitHub security advisory,
with a CVE where one applies. Disclosure is coordinated with you, within 90 days of the report at
most. Reporters are credited unless they would rather not be.

Out of scope: self-XSS, missing security headers without a demonstrated impact, issues that need
an already-compromised host, and denial of service by volume alone.
