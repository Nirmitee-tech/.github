# Security Policy

Nirmitee.io builds software that runs next to protected health information. We take reports about our open-source projects seriously and respond to all of them.

## Reporting a vulnerability

**Please do not open a public GitHub issue for a security problem.**

Email **security@nirmitee.io** with:

- the repository and version or commit affected
- a description of the issue and its impact
- steps to reproduce, and a proof of concept if you have one
- any suggested remediation

If you prefer, you can use GitHub's [private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) on the affected repository instead.

## What to expect

| Stage | Target |
|---|---|
| Acknowledgement of your report | 3 business days |
| Initial assessment and severity triage | 10 business days |
| Fix or documented mitigation for high/critical issues | 30 days |

We will keep you updated as we work through it, and we will credit you in the advisory unless you ask us not to.

## Scope

This policy covers the source code in public repositories under the [Nirmitee-tech](https://github.com/Nirmitee-tech) organization.

It does **not** cover our client deployments or hosted environments. If you believe you have found an issue in a system operated by Nirmitee.io on behalf of a customer, email security@nirmitee.io and we will route it to the right team — do not test against those systems.

## Please do not

- Access, modify or exfiltrate data that is not yours
- Run denial-of-service or load tests against any hosted environment
- Use social engineering against our staff or customers

## Protected health information

Never include real PHI, PII or production credentials in an issue, pull request or vulnerability report. If you need to demonstrate a problem with a data file, use synthetic data. If you believe real PHI has been committed to one of our repositories, email security@nirmitee.io immediately and we will treat it as an urgent incident.
