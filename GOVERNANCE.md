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

## Consensus Seeking Process

The Team follows a [Consensus Seeking][] decision-making model.

When an agenda item has appeared to reach a consensus, the moderator
will ask "Does anyone object?" as a final call for dissent from the
consensus.

If an agenda item cannot reach a consensus, a Team member can call for
the item to be decided by a vote or to table the issue to the next
meeting. In both cases the decision must be seconded by a majority of the Team
or else the discussion will continue. Simple majority wins. Only Active
Members participate in a vote.

## Term for Voting Members

As per the [CPC charter][cpc charter term], the term for all voting members is normally 1 year:

> Voting members serve for a term of 1 year and must be re-nominated and ratified
> by the Voting CPC members each year.

Due to the bootstrap process, the term for the first year will be
shortened such that the initial term for all voting members ends March 31st, 2020.
Subsequent terms will be for a period of 1 year ending the following March 31st.

## Term for CPC Board representatives

As per the CPC charter, the term for CPC Board representatives is 1 year. Due to the bootstrap
process and the decision to stagger CPC representative terms by 6 months, the initial term for the
[Primary CPC Director][] will end February 28, 2021 and the initial term for the
[Secondary CPC Director][] will end August 31, 2020. Subsequent terms will be for a period
of 1 year ending the last day of February for the Primary CPC Director and August 31 for the
Secondary CPC Director.

In the event that the [Tertiary CPC Director][] seat is activated and a start date is determined,
the Tertiary CPC Director will then serve for a term of 1 year from that start date.

## Election process for Non-Impact Voting CPC members

As per the [CPC charter][cpc charter], the non-impact projects elect 2 voting CPC members:

> up to two (2) Voting members may be nominated by the non-impact projects based on a process set by the CPC.

These members will be elected for a term of 1 year as follows:

* Once a year an issue will be opened in the CPC repo announcing that the period for
  nominations is open.

* Any member from one of the non-impact projects can self-nominate emailing the chair of the CPC with their
  interest in running for the CPC.

* The nomination period will be open for 2 weeks at which point the CPC chair will list the nominees in the
  issue.

* Each of the candidates listed will be asked to open an issue in the CPC repo which includes the following:
  * Projects they are part of
  * Description of their background
  * The reasons they would like to act as a non-impact CPC voting member
  * Confirmation that they can devote the required time/effort.
  * Their employer (if applicable). This is needed due to the limitations
    on maximum employer representation in the CPC voting members.

* The projects will be asked to confirm membership as identified by the nominees.

* Each non-impact project will nominate two `voters` through a process of their choosing.

* Each voter will be able to vote for as many or as few candidates as they wish.

* Voting will start a week after the nomination period ends, and be open for two weeks.

* Those candidates who receive the greatest number of votes will be confirmed as
  the winners. In the case of a tie between 2 or more candidates, the winner will be
  chosen randomly unless:
   * There are only 2 candidates tied for the largest number of votes, in which case those 2
     candidates will be the winners, or
   * all but one of the candidates that are tied for the number of votes choose to conceed.

## Approving and Onboarding Regular Members

Our goal in the OpenJS Foundation is to do most of our work in public. On occasion, there are matters and materials that must be kept private and shared only with Voting and Regular members. As a result we have requirements in place in order to ensure that Voting and Regular members are known and active in the projects they represent or known to the CPC and active in its work. Observers can participate in almost all aspects of the work of the CPC except those infrequent matters related to private information.

### Eligibility to become a Regular member

One must already be an [Active OpenJS Collaborator][], as described below, to be eligible to become a Regular Member of the CPC.

### Means for approval/rejection, if citing project affiliation: (one of the following approvals is required)

- Project representatives from the project the user is claiming affiliation with have the ability to approve/reject the nomination.
- Voting members from the project the user is claiming affiliation with have the ability to approve/reject the nomination.

Regular members can self-nominate by opening a PR to add themselves to the Regular member list in the [README.md][README]. The PR should include information about how the potential new member has been active in the foundation or its member projects as described below in the [Active OpenJS Collaborator][] section of this document.

In addition to being an [Active OpenJS Collaborator][], the PR to add a Regular member is approved when:

* There are no outstanding objections
* There are two or more approvals by voting CPC members
* The PR has been opened for at least 1 week

Once a PR is ready to be landed, the CPC member who lands the pull request should:

* Send a notification to the project contacts for the project identified in the PR
  indicating that a new Regular CPC member has joined the CPC on behalf of the project.
* Add the member to the github `cpc-regular-members` [team][cpc regular members team]
* Add the member to the `cpc-private` email list and private directory by opening a PR against the [OpenJS Foundation CPC directory][]
* Introduce the new member at the next CPC meeting.

_Note: Former Voting members whose terms have just ended will automatically become Regular members, unless they indicate otherwise._

## Definition of an Active OpenJS Collaborator

### To be considered an active OpenJS Collaborator, one of the following is required:

- Activity within a project, community, or collaboration space.
- A demonstrated level of contribution to the CPC's work during the past 30 days.

_Note: "Activity" is defined as recent, sustained contributions during the past 90 days. Contributions can include, but are not limited to, participation in meetings, issues or pull-requests, editing documentation, community management, marketing, organizing events, as well as similar activities as they relate to the OpenJS Foundation and its member projects._

## Approving Project Charters

Per the [CPC charter section 5][], the voting CPC members are responsible for approving project
charters and changes to them.

Approval of the initial charter or changes to an existing charter will
be requested by opening an issue requesting approval in the cross-project-council
[repository][cpc repo].

The request is approved when:

* There are no outstanding objections
* There are two or more approvals by voting CPC members
* The board has been consulted in the case of substantial changes
* The issue has been open for at least 14 days

## Merging PRs into this Repository

Pull requests that do not change the charter or governance of the CPC can be merged into
this repository provided the following conditions have been met:

* There are no outstanding objections
* There are two approvals by CPC members
* The PR has been open for at least 72 hours

Pull requests that change governance of the CPC (including approving changes to
Working Groups) must meet the following conditions in addition to the ones
listed for regular PRs.

* The PR has been open for at least 14 days OR consensus is reached in a meeting
  with quorum of voting members.

Pull requests that change the charter of the CPC must meet the following conditions
in addition to the ones listed for changing CPC governance:

* The text of the PR must be approved by a simple majority of the voting members.
* The text of the PR must be approved by the board.

If consensus cannot be reached, a pull request may still be landed after a vote
by the Voting CPC members to override outstanding objections.

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
[cpc charter]: https://github.com/openjs-foundation/cross-project-council/blob/master/CPC-CHARTER.md
[cpc charter term]: https://github.com/openjs-foundation/cross-project-council/blob/master/CPC-CHARTER.md#voting-members
[CPC charter section 5]: https://github.com/openjs-foundation/cross-project-council/blob/master/CPC-CHARTER.md#section-5-responsibilities-and-expectations-of-the-cpc
[cpc regular members team]: https://github.com/orgs/openjs-foundation/teams/cpc-regular-members
[README]: ./README.md
[OpenJS Foundation Directory]: https://github.com/openjs-foundation/directory-private/blob/master/cpc-private.md
[Consensus Seeking]: http://en.wikipedia.org/wiki/Consensus-seeking_decision-making
[Active OpenJS Collaborator]: #definition-of-an-active-openjs-collaborator
[OpenJS Foundation CPC directory]: https://github.com/openjs-foundation/directory-private/blob/master/groups/cross-project-council.yml
[Primary CPC Director]: https://github.com/openjs-foundation/cross-project-council/blob/master/CPC-CHARTER.md#the-primary-cpc-director-as-defined-in-43d-in-the-openjs-foundation-bylaws
[Secondary CPC Director]: https://github.com/openjs-foundation/cross-project-council/blob/master/CPC-CHARTER.md#the-secondary-cpc-director-as-defined-in-43e-in-theopenjs-foundation-bylaws
[Tertiary CPC Director]: https://github.com/openjs-foundation/cross-project-council/blob/master/CPC-CHARTER.md#the-tertiary-cpc-director-as-defined-in-43f-in-the-openjs-foundation-bylaws
