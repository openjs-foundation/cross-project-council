# OpenJS Travel Fund
>  Stage 0

Tracked by https://github.com/openjs-foundation/cross-project-council/issues/172

## Champion

Jonah Stiennon @jonahss

## Description

The Node.js organizations that existed prior to the formation of the OpenJS foundation oversaw a monetary fund for the purpose of member and affiliate travel to, and lodging at, events related to the foundation's mission. This proposal proposes moving the management responsibilities of this fund to the Cross Project Council (CPC), and making the funds available to all members of this broader organization. Since all projects have voting representation on the CPC, the beneficiaries of the fund will jointly manage it, and the previous owners of the fund will still vote on its use.

We shall review the process in this proposal, but the intent is to leave the mechanics of the fund unchanged, simply moving from the purview of the Node.js project into the domain of the OpenJS Foundation, overseen by the CPC. This operation can be viewed as a refactor which moves the travel fund up one level in the organizational tree.

The current fund is used mostly for attending collaborator summits, and we do not expect this to change.

## Difference from the current process

The existing process requires approval from two members of the [Node.js TSC](https://github.com/nodejs/TSC) and two members of the [Node.js Community Committee](https://github.com/nodejs/community-committee).
The new process will require approval from four members of the CPC.

The role of fund "treasurer" will be removed, as it has been found to be redundant and is not currently filled (see https://github.com/openjs-foundation/cross-project-council/pull/268#issuecomment-513888283).

## Practical Specifics

- Move relevant files from nodejs/admin to openjs-foundation/cross-project-council such as:
  - https://github.com/nodejs/admin/blob/master/MEMBER_TRAVEL_FUND.md
  - https://github.com/nodejs/admin/tree/master/TravelFunds
  - https://github.com/nodejs/admin/blob/master/travel-visas.md
  - https://github.com/nodejs/admin/blob/master/expense-report-template.xls
  - https://github.com/nodejs/admin/blob/master/reimbursement_process.pdf
- Modify these files to account for OpenJS rather than Node.js organizations
- Remove mentions from nodejs/admin README, add links to CPC README
- Remove the role of treasurer

## Required Resources

@brianwarner reports that everything can stay the same for the tools and accounts involved.
No other resources required.

## How would success be measured?

Success will be achieved if Node.js and non-Node.js members use the travel fund to attend a Foundation-related event, and nobody notices the difference.

## Why this proposal is important

Organizationally, the Node.js project is at the same level as the other impact projects in the Foundation, and so the travel fund should benefit all projects equally in opportunity. Plus, the sponsorships which pay for the fund sponsor the entire Foundation, not just the Node.js project.

## Unresolved Questions

- Who is the current treasurer of the fund?

## What is necessary to complete this proposal

- Approval and buy-in from Node.js TSC and CommComm.
- OpenJS board approval
- Definition and wording of the travel fund mechanics, mostly moving files and updating references.
