# Security Policy

This policy applies to all source code repositories managed under the GitHub account [@willtheorangeguy](https://github.com/willtheorangeguy/).

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public issues, discussions, or pull requests.**

Report them privately through GitHub's [private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability). On the affected repository, open the **Security** tab and choose **Report a vulnerability**. Only you and the maintainer will see the report until a fix is published.

Please include as much of the following as you can:

* The type of issue (buffer overflow, SQL injection, cross-site scripting, path traversal, and so on)
* Full paths of the source files related to the issue
* The location of the affected code — tag, branch, commit, or a direct URL
* Any special configuration needed to reproduce it
* Step-by-step reproduction instructions
* Proof-of-concept or exploit code, if you have it
* The impact, including how an attacker might exploit it

This information helps triage the report faster.

## What to Expect

| Stage | Target |
| ----- | ------ |
| Acknowledgement of your report | Within 7 days |
| Initial assessment and severity triage | Within 14 days |
| Fix released, or a timeline shared with you | Within 90 days |

These are targets for personal, unfunded projects, not contractual guarantees. If a report goes unanswered past these windows, you are welcome to escalate by opening a *non-sensitive* issue that says only that you are awaiting a response — please do not include vulnerability details.

## Supported Versions

Only the latest release of a given project receives security fixes. Older tags are not patched.

| Version | Supported |
| ------- | ------------------ |
| Latest release | :white_check_mark: |
| Everything else | :x: |

## Disclosure

Fixes are published as a new release with a GitHub Security Advisory. If you would like credit, say so in your report and you will be named in the advisory. If you would prefer not to be named, that is fine too.

Please give a reasonable window for a fix to ship before disclosing publicly.

## Scope

Reports about the code in these repositories are in scope. The following are generally **out of scope**:

* Vulnerabilities in third-party dependencies — report those upstream, though a heads-up here is welcome
* Findings that require physical access to a user's unlocked device
* Missing security headers or hardening suggestions with no demonstrated impact
* Automated scanner output submitted without a working proof of concept

Participation is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).
