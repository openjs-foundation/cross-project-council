# OpenJS Travel Fund
>  Stage 0

Tracked by https://github.com/openjs-foundation/cross-project-council/issues/172

## Champion

Jonah Stiennon @jonahss

## Description

The Node.js organizations that existed prior to the formation of the OpenJS foundation oversaw a monetary fund for the purpose of member and affiliate travel to, and lodging at, events related to the foundation's mission. This proposal proposes moving the management responsibilities of this fund to the Cross Project Council (CPC), and making the funds available to all members of this broader organization. Since all projects have voting representation on the CPC, the beneficiaries of the fund will jointly manage it, and the previous owners of the fund will still vote on its use.

We shall review the process in this proposal, but the intent is to leave the mechanics of the fund unchanged, simply moving from the purview of the Node.js project into the domain of the OpenJS Foundation, overseen by the CPC. This operation can be viewed as a refactor which moves the travel fund up one level in the organizational tree.

## Difference from the current process

The existing process requires approval from two members of the Node.js TSC and two members of the Node.js Community Committee.
The new process will requiree approval from four members of the CPC.

The treasurer will be a member of the CPC rather than the Node.js TSC or Community Committee.

## Practical Specifics

- Move relevant files from nodejs/admin to openjs-foundation/cross-project-council such as:
  - https://github.com/nodejs/admin/blob/master/MEMBER_TRAVEL_FUND.md
  - https://github.com/nodejs/admin/tree/master/TravelFunds
  - https://github.com/nodejs/admin/blob/master/travel-visas.md
  - https://github.com/nodejs/admin/blob/master/expense-report-template.xls
  - https://github.com/nodejs/admin/blob/master/reimbursement_process.pdf
- Modify these files to account for OpenJS rather than Node.js organizations
- Remove mentions from nodejs/admin README, add links to CPC README
- Expensify account needs to be migrated to OpenJS if it is not already
- Create new email address to take the place of travelapprovals@nodejs.org

## Required Resources

Permissions to the services and financial accounts involved. I believe @brianwarner should already have access, in which case there is nothing more to be done.

## How would success be measured?

Success will be achieved if non-Node.js members use the travel fund to attend a Foundation-related event.

## Why this proposal is important

Organizationally, the Node.js project is at the same level as the other impact projects in the Foundation, and so the travel fund should benefit all projects equally in opportunity. Plus, the sponsorships which pay for the fund sponsor the entire Foundation, not just the Node.js project.

## Unresolved Questions

- Which group is in charge of the actual budget?
- Does this require Board approval?

## What is necessary to complete this proposal

- Definition and wording of the travel fund mechanics
- Transfer of the current travel fund and tools/accounts to the CPC
