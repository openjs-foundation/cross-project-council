# OpenJS GitHub Organization Management Policy

The [OpenJS Foundation GitHub Organization](https://github.com/openjs-foundation) is provided as a development resource by the OpenJS Foundation under the direction of the OpenJS Cross Project Council (CPC).

## OpenJS Administrative Ownership

The [OpenJS Cross Project Council Repository][] serves as the central location for managing OpenJS GitHub Organization administrative activities. Only OpenJS GitHub Organization owners (CPC members) have write permissions to the administrative documents in the this repository.

## Organization Roles

### Owners

Granting Owner permissions is determined by optimizing for the following conflicting requirements:

* Limiting access to reduce risk
* Enabling individuals to move community work forward without undue delay

When possible, automation and tools should be used to reduce the breadth of access that needs to be provided in order to enable individuals to move community work forward. As these tools are created, the groups to which Ownership permissions are granted will be reduced.

The following groups are granted Ownership permissions:

* CPC members

### Members

GitHub users are added as members to the [OpenJS GitHub Organization][] when they are added to any Working Group or team. Organization Owners should add new members to the organization when requested by a Working Group, or team.

## Repositories

Any repository created under the [OpenJS GitHub Organization][] is considered to be a project under the ownership of the OpenJS Foundation, and thereby subject to the Intellectual Property and Governance policies of the Foundation.

Any organization member may request the management of repositories within the OpenJS Foundation GitHub Organization by opening an issue in the [OpenJS CPC repository][]. The actions requested could be:

- Creating a new repository
- Deleting an existing repository
- Archiving an existing repository
- Transferring a repository into or out of the organization

Provided there are no objections from any CPC members raised in the issue, such requests are approved automatically after 72 hours. If any objection is made, the request may be moved to a vote by the CPC. If the CPC rejects the request, then the request is denied.

In certain cases, approval from the OpenJS Foundation Board of Directors may also be required.

### Teams

When making a request to create a new repository: specify the team(s) that will have write or admin access. If there is not an appropriate team to maintain a new repository, request a new team. Approval is automatically granted if there are no objections from the CPC after 72 hours.

## Removing or Blocking Individuals

Only OpenJS GitHub Organization owners may remove or block an individual from membership within the OpenJS Foundation. This is due largely to limitations in the way GitHub permissions are structured.

To remove any current member from the GitHub organization, an issue must be opened in the [OpenJS CPC repository][]. If, after 72 hours, there are no objections from any CPC members: removal occurs automatically. If there are objections: then a simple majority vote of the Cross Project Council in favor of removal is required.

Blocking an individual who is not currently a member of the GitHub organization may occur at any time, as subject to the policies outlined in the Moderation Guidelines.

## Use of Bots and Services

Automation tools such as bots and third-party services on any repository must be approved by the CPC, and are subject to regular security audits. Bots that perform actions on behalf of the project (such as moderation, or membership management actions) are required to maintain a log of all actions taken, that is accessible to all individuals who are granted Ownership permissions.

[OpenJS GitHub Organization]: https://github.com/openjs-foundation
[OpenJS Cross Project Council Repository]: https://github.com/openjs-foundation/cross-project-council
[OpenJS CPC Repository]: https://github.com/openjs-foundation/cross-project-council
