# Guide to Community Health Files for OpenJS Foundation Projects

Community health files are documents related to project collaboration. Most commonly, these include:

- `CODE_OF_CONDUCT.md`
- `CONTRIBUTING.md`
- `GOVERNANCE.md`
- `SECURITY.md`

> [!NOTE]
> See the [full list](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file#supported-file-types) of supported default community health files

## Default Community Health Files

Instead of adding these files to every repository within an organization, we can add them only once to a special organization repository which must be named `.github`. GitHub will automatically use the community health files specified at this location by default for all repositories within the organization.

The filenames must match [what is expected by GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file#supported-file-types) and must be in one of these locations:

- The root of the `.github` repository
- The `.github` folder in the `.github` repository
- The `docs` folder in the `.github` repository

Where possible, it is best to have only one file for each type of community health file, specified in the `.github` repository, and to avoid having individual files for each repository. However, specific project needs may require repository-specific files.

> [!Important]
> If a file also exists in a repository, then that file will take precedence over the organization default.

### Community Health Files That Projects Should Have

- Organizations/projects must have at least `CODE_OF_CONDUCT.md` and `SECURITY.md` files.
- A [`CONTRIBUTING.md`](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors) file is highly recommended for all organizations/projects.
- A `GOVERNANCE.md` file should be provided for all organizations/projects with formal governance.

> [!NOTE]
> All projects must have a LICENSE file, but it is not possible to provide a default LICENSE file for the organization. Every repository requires its own LICENSE file.

#### `CODE_OF_CONDUCT.md`

Organizations/projects should use the following content for their `CODE_OF_CONDUCT.md` file. This will avoid any issues that would arise by duplicating content.

```md
This repository is an OpenJS Foundation project and subscribes to its [Code of Conduct](https://github.com/openjs-foundation/cross-project-council/blob/main/CODE_OF_CONDUCT.md).
```

#### `SECURITY.md`

All organizations/projects must have a security policy. This file must inform users how they can privately report security issues to projects.

At a [bare minimum](https://github.com/ossf/oss-vulnerability-guide/blob/main/templates/security_policies/github_security_policy.md), it should direct users to an email address.

It should also include any other reporting mechanism used by the project, such as [GitHub PVR](https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories/configuring-private-vulnerability-reporting-for-an-organization).

##### Further Guidance for Developing Security Policy

For guidance and assistance on developing security policy, reach out to [the OpenJS Security Collaboration Space](https://github.com/openjs-foundation/security-collab-space/#security-collaboration-space).

Another good resource is the [OpenSSF Guide to implementing a coordinated vulnerability disclosure process for open source projects](https://github.com/ossf/oss-vulnerability-guide/blob/main/maintainer-guide.md).

## Further Resources on Best Practices

Community health files are one aspect of best practices that projects should follow. For more information on best practices, see the [OpenSSF Best Practices Badge Guide](https://github.com/openjs-foundation/security-collab-space/blob/main/best-practices-badge.md).
