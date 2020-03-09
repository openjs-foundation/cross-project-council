# OpenJS Core Working Groups

OpenJS Core Working Groups (WG) are autonomous projects created by the [Cross Project Council (CPC)][].

Working Groups can be formed at any time, but must be ratified by the CPC. Once formed, the work defined in the Working Group charter is the responsibility of the WG rather than the CPC.

It is important that Working Groups are not formed prematurely. Working Groups are not formed to *begin* a set of tasks, but are formed once that work is underway and its contributors agree that doing the work as an autonomous project is the most beneficial next step.

If the work defined in a Working Group's charter is complete, the charter should be revoked.

A Working Group's charter can be revoked either by the consent of the Working Group's members, or by a CPC vote. Once revoked, any future work that previously fit within the scope of the dechartered working group becomes the responsibility of the CPC.

## Joining a Working Group

To find out how to join a working group, please review the GOVERNANCE.md document in the working group's repository.

## Starting A Core Working Group

A Working Group is established by first defining a charter that can be ratified by the CPC. A charter is a *statement of purpose*, a *list of responsibilities*, and a *list of initial membership*.

A Working Group needs 3 initial members. These should be individuals who are already undertaking the work described in the charter.

The list of responsibilities for the Working Group should be specific. Once established, these responsibilities are no longer governed by the CPC and therefore should not be broad or subjective. The only recourse the CPC has over the working group is to revoke the entire charter, and take on the work previously done by the working group themselves.

If the responsibilities described in the Working Group's charter are currently undertaken by another WG, then the Working Group's charter will additionally have to be ratified by that WG.

You can submit the Working Group charter for ratification by sending a Pull Request to this document, which adds it to the list of current Working Groups. Once ratified, the list of members should be maintained in the Working Group's README document.

## Bootstrap Governance

Once the CPC ratifies a charter, the Working Group inherits the following documentation for governance, contribution, conduct, and an MIT LICENSE. The Working Group is free to change these documents through their own governance process (hence the term "bootstrap").

```markdown
### *[insert WG name]* Working Group

The OpenJS *[insert WG name]* is jointly governed by a Working Group (WG) that is responsible for high-level guidance of the project.

The WG has the final authority over this project including:

* Technical direction
* Project governance and process (including this policy)
* Contribution policy
* GitHub repository hosting
* Conduct guidelines
* Maintaining the list of additional Collaborators

For the current list of WG members, please see the project [README.md](./README.md#current-project-team-members).

### Collaborators

The *[insert WG name]* GitHub repository is maintained by the WG and additional Collaborators who are added by the WG on an ongoing basis.

Individuals making significant and valuable contributions are made Collaborators, and given commit-access to the project. These individuals are identified by the WG, and their addition as Collaborators is discussed during the weekly WG meeting.

_Note:_ If you make a significant contribution and are not considered for commit-access, log an issue or contact a WG member directly and it will be brought up in the next WG meeting.

Modifications of the contents of the *[insert WG repo]* repository are made on a collaborative basis. Anybody with a GitHub account may propose a modification via pull request(s), and it will be considered by the project Collaborators. All pull requests must be reviewed and accepted by a Collaborator with sufficient expertise who is able to take full responsibility for the change. In the case of pull requests proposed by an existing Collaborator, an additional Collaborator is required for sign-off. Consensus should be sought if additional Collaborators participate and there is disagreement around a particular modification. Please see the _Consensus Seeking Process_ below for further detail on the consensus model that is used for governance.

Collaborators may opt to elevate significant or controversial modifications, or modifications that have not found consensus within the WG for discussion by assigning a ***WG-agenda*** tag to a pull request or issue. The WG should serve as the final arbiter, where required.

For the current list of Collaborators, see the project [README.md](./README.md#current-project-team-members).

### Working Group Membership

Working Group seats are not time-limited, and there is no fixed-size for the Working Group (beyond the requirement of needing 3 inidividuals to establish it). However, a sufficient number of participants should be involved to ensure adequate coverage of important areas of expertise, which is balanced with the ability to make decisions efficiently.

There is no specific set of requirements or qualifications for WG membership, beyond these rules.

The WG may add additional members to the WG by unanimous consensus.

A WG member may be removed from the WG by voluntary resignation, or by the unanimous consensus of all other WG members.

Changes to WG membership should be posted in the WG's meeting agenda, and may be suggested as any other agenda item (see "WG Meetings" below).

If a membership addition or removal is proposed during a meeting, and the full WG is not in attendance to participate, then the addition or removal is added to the agenda for the subsequent meeting. This is to ensure that all members are given the opportunity to participate in all membership decisions. If a WG member is unable to attend a meeting where a planned membership decision is being made, then their consent is assumed.

### Working Group Meetings

The WG meets regularly on a webinar platform. A designated moderator approved by the WG runs the meeting. Each meeting should be published to the [OpenJS YouTube Channel](https://www.youtube.com/channel/UCjxM1d3fv_mSEBsyp5MTFrg).

Items are added to the WG agenda that are considered contentious, or are modifications of governance, contribution policy, WG membership, or release processes.

The intention of the agenda is not to approve or review all patches, that should happen continuously on GitHub and be handled by the larger group of Collaborators.

Any community member or contributor can ask that something be added to the next meeting's agenda by logging a GitHub Issue. Any Collaborator, WG member, or moderator can add the item to the agenda by adding the ***WG-agenda*** tag to the issue.

Prior to each WG meeting, the moderator will share the Agenda with members of the WG. WG members can add any items they like to the agenda at the beginning of each meeting. The moderator and the WG cannot veto or remove items.

The WG may invite persons or representatives from related projects to participate in a non-voting capacity.

The moderator is responsible for summarizing the discussion of each agenda item, and commits it as a pull request after the meeting.

### Consensus Seeking Process

The Working Group follows a [Consensus Seeking](http://en.wikipedia.org/wiki/Consensus-seeking_decision-making) decision-making model.

When an agenda item has appeared to reach a consensus, the moderator will ask "Does anyone object?" as a final call for dissent from the group consensus.

If an agenda item cannot reach a consensus: a WG member can call for either a closing vote, or a vote to table the issue until the next meeting. The call for a vote must be seconded by a majority of the WG, or else the discussion will continue. A simple majority wins.

Note that changes to WG membership require unanimous consensus. See the "Working Group Membership" section above for more information.

<a id="developers-certificate-of-origin"></a>
## Developer's Certificate of Origin 1.1

*Note*: The DCO is mandatory for all OpenJS Foundation projects.

By making a contribution to this project, I certify that:

* (a) The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file; or

* (b) The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as indicated in the file; or

* (c) The contribution was provided directly to me by some other person who certified (a), (b) or (c) and I have not modified it.

* (d) I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my sign-off) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.

### Moderation Policy

The [OpenJS Moderation Policy][] applies to this Working Group. Moderation Policy TBD.

### Code of Conduct

The [OpenJS Code of Conduct][] applies to this Working Group.

[OpenJS Code of Conduct]: https://github.com/openjs-foundation/cross-project-council/blob/master/CODE_OF_CONDUCT.md
[OpenJS Moderation Policy]: https://github.com/openjs-foundation/cross-project-council/blob/master/Moderation-Policy.md
```

## Current Working Groups

None currently

[Cross Project Council (CPC)]: ./CPC-CHARTER.md
