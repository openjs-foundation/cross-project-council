# OpenJS Cross Project Council

For the current list of Team members, see the project [README.md][README] and the [OpenJS Foundation Directory][] (restricted access for privacy reasons).

## Members

The [openjs-foundation/cross-project-council][cpc repo] GitHub
repository is maintained by the Team and additional Members who are
added on an ongoing basis.

## Team Membership

Team Membership is not time-limited. There is no fixed size of the Team.

There is no specific set of requirements or qualifications for Team Membership beyond these rules.

The following groups automatically have membership and can request to be added to the github team:

* OpenJS Foundation Voting Members
* OpenJS Foundation Regular Members
* OpenJS Foundation Board of Directors
* OpenJS Foundation Project Maintainers

## Team Meetings

The Team meets weekly on Zoom.us. A designated moderator
approved by the Team runs the meeting. Each meeting should be
published to YouTube.

Items are added to the Team agenda that are considered contentious or
are modifications of governance, contribution policy, Team membership,
or release process.

The intention of the agenda is not to approve or review all patches;
that should happen continuously on GitHub and be handled by the larger
group of Collaborators.

Any community member or contributor can ask that something be added to
the next meeting's agenda by logging a GitHub Issue. Any Collaborator,
Team member or the moderator can add the item to the agenda by adding
the ***cross-project-council-agenda*** label to the issue.

Prior to each Team meeting the moderator will share the agenda with
members of the Team. Team members can add any items they like to the
agenda at the beginning of each meeting. The moderator and the Team
cannot veto or remove items.

The moderator is responsible for summarizing the discussion of each
agenda item and sends it as a pull request after the meeting.

### Guidelines for sharing Board information in CPC meetings
To improve organizational transparency and collaboration between the CPC and Board, it is desireable for CPC Directors to be able update the CPC on topics discussed during Board meetings. The goal of the below guidelines is to make this process lightweight and allow for information to be shared with the CPC as freely as possible. This is why the audience of those Board updates are somewhat restricted.

- CPC Directors should use their own judgement about what may be shared with the CPC. When in doubt they should abstain from sharing information and seek explicit permission to do so. In particular, information pertaining to a specific member, staff, or about legal matters should never be shared.
- Board updates are not streamed and they are limited to CPC members.
- CPC Directors wanting to report on a Board meeting should inform the CPC Chair at the beginning of the call so that sufficient time can be carved out at the end of the call for the update.

## Consensus Seeking Process

The team follows the [decision-making][cpc charter decision making] and [voting][cpc charter voting] policies described in the charter.

## Elections

Elections are organized by the OpenJSF Program Director, following the [election calendar][] and the policies defined in the [CPC charter][cpc charter elections].


## Approving and Onboarding Regular Members

Our goal in the OpenJS Foundation is to do most of our work in public.
On occasion, there are matters and materials that must be kept private and shared only with Voting and Regular members.
As a result we have requirements in place in order to ensure that Voting and Regular members are known and active in the projects they represent or known to the CPC and active in its work.
Observers can participate in almost all aspects of the work of the CPC except those infrequent matters related to private information.

### Eligibility to become a Regular member

One must already be an Active OpenJS Collaborator, as described below, to be eligible to become a Regular Member of the CPC.

### How To Apply As A Regular Member

1. Please submit the [Regular Member Application Form](https://forms.gle/vAKptPXXz8StL4yh6)     
2. The CPC will review requests as soon as possible, usually in the next CPC private session (every 2 weeks)

### CPC Review Process

- Pending requests will be sent to the private CPC mailing list prior to the review meeting
- In the context of the lazy consensus process, the pending request list is a proposal to accept
  all of the requests. CPC members may raise any objections before the scheduled meeting,
  otherwise a final decision to approve a request can be confirmed in the meeting.
- If any requests are rejected, an email with the rejected requests will be sent to the private
  CPC mailing list and CPC members will have 2 days to object before the decision is confirmed.

### Approved

* The CPC will create a pull request adding your name to the Regular member list in the [README.md][README].
* The OpenJS Foundation Operations <operations@openjsf.org> team will:
   * Add the member to the GitHub `cpc-regular-members` [team][cpc regular members team]
   * Add the member to the `cpc-private` email list
* The CPC Chair or Vice-Chair will introduce the new member at the next CPC meeting. 


### Not Approved

* If you are not approved you will be notified privately via email

_Note: Former Voting members whose terms have just ended will automatically become Regular members, unless they indicate otherwise._

## Definition of an Active OpenJS Collaborator

### To be considered an active OpenJS Collaborator, one of the following is required:

- Activity within a project, community, or collaboration space.
- A demonstrated level of contribution to the CPC's work during the past 30 days.

_Note: "Activity" is defined as recent, sustained contributions during the past 90 days. Contributions can include, but are not limited to, participation in meetings, issues or pull-requests, editing documentation, community management, marketing, organizing events, as well as similar activities as they relate to the OpenJS Foundation and its member projects._

## Approving Project Charters

Per the [CPC charter section 5][], the voting CPC members are responsible for approving project charters and changes to them.

Approval of the initial charter or changes to an existing charter will be requested by opening an issue requesting approval in the cross-project-council [repository][cpc repo].

The request is approved when:

* There are no outstanding objections
* There are two or more approvals by voting CPC members
* The board has been consulted in the case of substantial changes
* The issue has been open for at least 14 days

## Merging PRs into this Repository

Pull requests that do not change the charter or governance of the CPC can be merged into this repository provided the following conditions have been met:

* There are no outstanding objections
* There are two approvals by CPC members
* The PR has been open for at least 72 hours

Pull requests that change governance of the CPC (including approving changes to Working Groups) must meet the following conditions in addition to the ones listed for regular PRs.

* The PR has been open for at least 14 days OR consensus is reached in a meeting with quorum of voting members.

Pull requests that change the charter of the CPC must meet the following conditions in addition to the ones listed for changing CPC governance:

* The text of the PR must be approved by a simple majority of the voting members.
* The text of the PR must be approved by the board.

If consensus cannot be reached, a pull request may still be landed after a vote by the Voting CPC members to override outstanding objections.

### Fast-Tracking PRs

Special exception is made for pull requests seeking to make any of the following
changes to this repository:

- Errata fixes.
- Editorial changes.
- Meeting minutes.
- Updates to the team lists.
- Doc Fixes.

Charter changes cannot be fast-tracked.

To propose fast-tracking a pull request, apply the ***fast-track*** label. Then add a comment that CPC members may upvote.

If someone disagrees with the fast-tracking request, remove the label. Do not fast-track the pull request in that case.

The pull request may be fast-tracked if two CPC members approve the fast-tracking request. To land, the pull request itself still needs two CPC member approvals.

CPC members may request fast-tracking of pull requests they did not author. In that case only, the request itself is also one fast-track approval. Upvote the comment anyway to avoid any doubt.

[cpc repo]: https://github.com/openjs-foundation/cross-project-council
[CPC charter section 5]: ../CPC-CHARTER.md#section-5-responsibilities-and-expectations-of-the-cpc
[cpc charter decision making]: ../CPC-CHARTER.md#section-9-decision-making
[cpc charter voting]: ../CPC-CHARTER.md#section-10-voting
[cpc charter elections]: ../CPC-CHARTER.md#section-7-elections
[election calendar]: ../Dates-and-Reminders.md#elections-calendar
[cpc regular members team]: https://github.com/orgs/openjs-foundation/teams/cpc-regular-members
[README]: ../README.md
[OpenJS Foundation Directory]: https://github.com/openjs-foundation/directory-private/blob/HEAD/cpc-private.md
[Active OpenJS Collaborator]: #definition-of-an-active-openjs-collaborator
