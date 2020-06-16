# Security Reporting for OpenJS Foundation Projects

>  Stage 2

## Champion

Marcin Hoppe (@marcin_hoppe)

## Description

Currently OpenJS Foundation projects do not have consistently documented standards for responsible reporting and disclosure of security vulnerabilities. This proposal aligns OpenJS Foundation projects with industry best practices in this space.

See also:
- [Security reporting in OpenJS Foundation projects](https://gist.github.com/MarcinHoppe/b13a870770522c31a8386ada48b2e40f)
- [Guidelines for responsible reporting and disclosure of security vulnerabilities](https://github.com/nodejs/package-maintenance/blob/master/docs/drafts/security-guidelines.md)

## Required Resources

- Generic security policy template that projects can easily adopt
- Vulnerability handling playbook for project maintainers
- Optionally: vulnerability disclosure platform (VDP)

## Who would be responsible?

The responsibility for adoption of security reporting standards would be owned by the projects. The CPC would be responsible for providing guidance and necessary shared resources.

## How would success be measured?

- 100% of Impact, Growth, and more than 50% of At-Large projects have:
    - Security policy on GitHub
    - Vulnerability reporting mechanism (email or VDP)
- 100% of projects graduating from Incubation have a security policy on GitHub

## Why this proposal is important

Open source projects that can responsibly accept security reports and respond with a coordinated vulnerability disclosure have a higher chance of being treated as trustworthy by adopters.

## Unresolved questions

- Do we leave it to projects to coordinate disclosure?
    - Some projects are already prepared, have infrastructure and processes in place. Others don't.
- Do we need to offer additional resources to projects?
    - Vulnerability disclosure platform?
    - Staff triage team?
- Do we need to have a coordinating body?
    - Security working group at the Foundation level?
- How to coordinate with similar industry initiatives?
    - Open Source Security Coalition (https://securitylab.github.com/)
    - Node.js Ecosystem Security WG (https://github.com/nodejs/security-wg)

## What is out of scope?

- This proposal does not cover bug bounties
    - The decision whether to offer bounties or not is left to individual projects

## What is necessary to complete this proposal

- [x] Input from projects on their commitment to accepting security reports
- [x] Providing projects with generic:
    - Minimum requirements for security reporting: [REQUIREMENTS](REQUIREMENTS.md)
    - Security policy template
    - Recommendation how to handle security reports
- [ ] Updating CPC processes and documentation to include security reporting and disclosure in:
    - Project onboarding
    - Project progression
- [ ] Agreement on level of support the Foundation can offer to projects
