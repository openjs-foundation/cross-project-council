## I. Overview

This governance policy describes how an open source project can formally join the OpenJS Foundation, hereinafter referred to as the "Foundation", via the [Project Proposal Process](#ii-project-proposal-process). It describes the [Stages](#iii-stages---definitions--expectations) a project may be admitted under and what the criteria and expectations are for a given stage, as well as the acceptance criteria for a project to move from one stage to another. It also describes the [Annual Review Process](#vi-annual-review-process) through which those changes will be evaluated and made. 

Project progression - movement from one stage to another - allows projects to participate at the level that is most appropriate for them given where they are in their lifecycle. Regardless of stage, all Foundation projects benefit from a deepened alignment with existing projects, and access to mentorship, support, and foundation resources such as the travel fund.

<!-- For more information about how your project can benefit from Foundation membership and services, please see [TBD Document](). -->

## II. Project Proposal Process

### Introduction

This governance policy sets forth the proposal process for projects to be accepted into the Foundation. The process is the same for both existing projects which seek to move into the Foundation, and new projects to be formed within the Foundation.

### Project Proposal Requirements

New projects should express interest to join the OpenJS Foundation via an email to new-projects@lists.openjsf.org with a filled-out [Project Application Template](./NEW_PROJECT_APPLICATION.md). The initial application will have a silent period for internal only discussion. It's worth noting that this is not a commitment to transfer IP, but rather an initial exploration - IP transfer would happen once the project is moved into incubation. If your application is denied during this phase you will be notified privately. If there are no objections to the application, projects will given an `incubation` status and begin the on-boarding process. **Note** the `incubation` status is temporary as we determine if the project is a good fit. At any time during the `incubation` process a project can withdraw either voluntarily or at the request of the CPC.

#### Previous Project Applications

Some projects have decided to publicly share their application after being accepted for incubation. This can be helpful for new applicants to get a sense of what is expected. Please bear in mind, however, that each project is different and that applications will vary accordingly. The CPC considers the resources that each project has available, and the expectations for the application of a large corporate-backed project going for Impact stage will not be the same as those of volunteer maintained effort aiming for the At Large stage.

* [AMP's application](https://gist.github.com/tobie/b5ce633d2622ca4f28e8374d9de8bdf5)
* [Fastify's application](https://gist.github.com/mcollina/beb83b8bc594ae506e11c83aef9c537d)


#### Roles

##### Applicant

Individual or group who submits the application on behalf of a project to join the OpenJS Foundation.

##### Application Manager

The Application Manager ensures progress through the process, helps the project understand the work to be 
completed along with explaining where they are in the application process. Applications Managers can be a
member of the OpenJS Foundation staff, CPC Member, or other person approved by the CPC.

##### Application Champion

The Application Champion is a member of the CPC who commits to do the following:

1. Provide weekly update to the Applicant on progression through the process.
1. Be available to answer questions from the Applicant.
1. Advocate on behalf of the Project applying.
1. Help to explain why the Project is a good fit.
1. Help the Application Manager when needed.
1. Be available as a primary point of contact through the incubation period if reached.

The Application Champion *must not* be the Applicant.

#### Process

1. Initial email sent to new-projects@lists.openjsf.org with filled-out [Project Application Template](./NEW_PROJECT_APPLICATION.md).
1. Silent period. Internal only discussion.
1. Initial acceptance as [Incubating] Project.
1. An acknowledgement is sent to the applicant by Foundation staff within 48 hours (striving to reply within 24 hours when possible).
1. Silent period. Internal only discussion. The content of these discussion along with the content of the application itself are kept confidential.
1. Initial acceptance as an [Incubating] Project. Before public announcement there will be:
   * Private email to the CPC members which asks for +1 or objections to the application becoming public. This email will include:
     * The name of the application manager for the application
     * The name of the application champion for the application
     * Completed application 
     * Completed application-fit checklist.
     * Confirmation that the board has had an FYI and there were no objections.
     * Confirmation that there are no existing objections from CPC members.
     This is not a formal vote just the process to ensure we have regular CPC concensus to move forward.
   * If there is agreement to move forward:
     * Confirmation to the applicant that they are ready to have their application become public.
     * Discussion/agreement between applicant, application manager and Foundation media team to agree on announce date.
       Confirm next steps beyond announcement.  
   * If lack of consensus to move forward:
      * Correspondence from foundation staff to applicant about non-acceptance.
      * If possible, give guidance to the project in their quest to find a foundation home
        (ex. perhaps a different foundation would be a more suitable endeavor.)
   * Discussion/agreement between applicant, application manager and Foundation media team to agree on announce date.
1. Project goes through process of adhering to [on-boarding checklist](#onboarding-checklist).
1. Project completes a charter review process by the CPC as outlined in the [CPC Governance](./governance/GOVERNANCE.md#approving-project-charters). NOTE: this process takes two weeks to complete
1. Project graduates from incubation by a pull request adding the project to the [README.md](./README.md) file at its appropriate initial stage. The merging of this pull request proceeds as any other pull request to the README.md file.

##### Initial fit checklist

1. Is project open/willing to move to open governance?
1. Will project adopt the OpenJS CoC?
1. Licences are compatible with Foundation requirements.
1. What Trade Marks will be transferred
1. What domains will be transferred
1. What IP currently exists and how was it licensed
1. No red flags from website, social media accounts, etc.
1. Confirmation that application is authorized to represent the project.
1. Fit with OpenJS Foundation (not all of these need to be met, but provide different ways of assessing strategic fit).
   1. Impact on JavaScript Community.
   1. How much and how broad is usage within the JavaScript Community.
   1. Level of activity and progress within the project.
   1. Synergy or overlap with existing projects in the Foundation.
   1. Level of comfort that project will be successful.  
  
## Onboarding Checklist

<!--If this checklist is updated please ensure `https://github.com/openjs-foundation/project-status/blob/HEAD/.github/ISSUE_TEMPLATE/00-project-onboarding-checklist-template.md` is updated as well -->

This is an informational checklist to help projects onboard into the OpenJS Foundation - tasks we will complete together after your project has been accepted into the incubation process. If you have any questions or need help, the OpenJS Foundation CPC is available to assist.

- [ ] Adopt the [OpenJS Foundation Code of Conduct](https://code-of-conduct.openjsf.org/)
- [ ] Update project CoC reporting methods to include OpenJS Foundation escalation path
- [ ] List official domains that the project commits to transfer to the OpenJS Foundation following graduation
- [ ] Identify and document other core project infrastructure
- [ ] Adopt either the [Contributor License Agreement (CLA) or the Developer Certificate of Origin (DCO)](https://github.com/openjs-foundation/cross-project-council/blob/HEAD/governance/IP_POLICY_GUIDANCE.md#4-adopting-the-dco-or-a-cla)
- [ ] Add or Update Governance.md document (required for Impact stage)
- [ ] Confirm required files in place (CODE_OF_CONDUCT.md, LICENSE.md)
- [ ] Publish Project Charter on website or GitHub (see [charter template](https://github.com/openjs-foundation/cross-project-council/blob/HEAD/PROJECT_CHARTER_TEMPLATE.md))
- [ ] Update [legal copyright notice](https://github.com/openjs-foundation/cross-project-council/blob/HEAD/governance/IP_POLICY_GUIDANCE.md#2-copyright-notices) on GitHub
- [ ] Add [copyright notices for project website footers](https://github.com/openjs-foundation/artwork#copyright-notices-for-project-website-footers) to project website
- [ ] Add [OpenJS Foundation logo](https://github.com/openjs-foundation/artwork#openjs-foundation-logos) to project website
- [ ] [Add Project logo](https://github.com/openjs-foundation/artwork#preparing-artwork-for-contribution) to OpenJS Foundation website
- [ ] Add Project to the [CPC repo's README.md](https://github.com/openjs-foundation/cross-project-council/blob/HEAD/README.md#incubating-projects) as an Incubating project
- [ ] List trademarks the project commits to transfer to the OpenJS Foundation following graduation
- [ ] If project is using crowdfunding platforms, add disclaimer from the OpenJS Foundation [Trademark Policy](https://trademark-policy.openjsf.org) to platforms
- [ ] Identify individuals from the project to join the CPC
- [ ] Document project and foundation contacts for:
  * marketing & social media
  * infrastructure
  * legal/governance help
- [ ] Publish security policy (see [PROJECT_SECURITY_REPORTING](https://github.com/openjs-foundation/cross-project-council/blob/HEAD/PROJECT_SECURITY_REPORTING.md))

## Post-graduation Checklist

<!--If this checklist is updated please ensure `https://github.com/openjs-foundation/project-status/blob/HEAD/.github/ISSUE_TEMPLATE/project-post-graduation-checklist-template.md` is updated as well -->

This is a checklist to help projects complete the post-graduation tasks they committed to during onboarding - tasks we will complete together after your project has graduated from the incubation process. If you have any questions or need help, the OpenJS Foundation CPC is available to assist.

- [ ] Transfer previously indicated official domains to OpenJS Foundation, if any
- [ ] If relevant, implement the appropriate tool to enforce CLA or DCO
- [ ] Transfer previously indicated trademarks to the OpenJS Foundation, if any

## III. Stages - Definitions & Expectations

Every Foundation project has an associated maturity level. Proposed Foundation projects should state their preferred maturity level. Projects of all maturities have access to Foundation resources.

All Foundation projects may attend CPC meetings and contribute work regardless of their stage. 

### At Large Projects

#### Definition

At Large projects are projects which the CPC believes are, or have the potential to be, important to the ecosystem of Top-Level Projects or the JS ecosystem as a whole. They may be early-stage projects just getting started, or they may be long-established projects with minimal resource needs. The At Large stage provides a beneficial, neutral home for these projects in order to foster collaborative development and provide a path to deeper alignment with other Foundation projects via the graduation process.

#### Examples

1. New projects that are designed to extend one or more Foundation projects with functionality or interoperability libraries. 
1. Independent projects that fit the Foundation mission and provide potential for a novel approach to existing functional areas (or are an attempt to meet an unfulfilled need).
1. Projects commissioned or sanctioned by the Foundation.
1. Any project that realistically intends to join the Foundation Incubation or Top Level Stages in the future and wishes to lay the foundations for that transition.

#### Expectations

End users should evaluate At Large projects with care, as this stage does not set requirements for community size, governance, or production readiness. At Large projects will receive minimal marketing support from the Foundation. Projects will be reviewed on an annual basis; they may also request a status review by submitting a report to the CPC.

#### Acceptance Criteria

To be considered for the At Large Stage, the project must meet the following requirements:
* 2 CPC sponsors to champion the project & provide mentorship as needed
* A presentation to at the meeting of the CPC
* Adherence to the Foundation IP Policy
* Upon acceptance, At Large projects must list their status prominently on website/readme


### Impact Stage

#### Definition

The Impact Stage is for projects that have reached their growth goals and are now on a sustaining cycle of development, maintenance, and long-term support. Impact Stage projects are used commonly in enterprise production environments and have large, well-established project communities.     

#### Examples

1. Projects that have publicly documented release cycles and plans for "Long Term Support" (LTS).
1. Projects that have themselves become platforms for other projects.
1. Projects that are able to attract a healthy number of committers on the basis of its production usefulness (not simply 'developer popularity').
1. Projects that have several, high-profile or well known end-user implementations.

#### Expectations

Impact Stage projects are expected to participate actively in CPC proceedings, and as such have a binding vote on CPC matters requiring a formal vote, such as the election of a CPC Director. They receive ongoing financial and marketing support from the Foundation, and are expected to cross promote the foundation along with their activities. 

#### Acceptance Criteria

To graduate from At Large stage or for a new project to join as an Impact project, a project must meet the following criteria:

 * Document that it is being used successfully in production by at least two independent end users which, in the CPC’s judgement, are of adequate quality and scope.
 * Have a defined governing body of at least 5 or more members (owners and core maintainers), of which no more than 1/3 is affiliated with the same employer. In the case there are 5 governing members, 2 may be from the same employer. 
 * Have a documented and publicly accessible description of the project's governance, decision-making, contribution, and release processes. This is preferably laid out in a GOVERNANCE.md file and references a CONTRIBUTING.md and AUTHORS.md file showing the current and emeritus committers.
 * Demonstrate a substantial ongoing flow of commits and merged contributions.
 * Have a healthy number of committers from at least two organizations. A committer is defined as someone with the commit bit; i.e., someone who can accept contributions to some or all of the project.
 * Adopt the Foundation Code of Conduct.
 * Accept security reports and publicly disclose them after the fix has been made available.
 * Have a public list of project adopters for at least the primary repo (e.g., ADOPTERS.md or logos on the project website).
 * Other metrics as defined by the applying Project during the application process in cooperation with the CPC.
 * Receive a supermajority vote from the CPC to move to Impact stage. Projects can move directly from At Large to Impact, if they can demonstrate sufficient maturity and have met all requirements. 


### Emeritus Stage

#### Definition

Emeritus projects are projects which the maintainers feel have reached or are nearing end-of-life. Emeritus projects have contributed to the ecosystem, but are not necessarily recommended for modern development as there may be more actively maintained choices. The Foundation appreciates the contributions of these projects and their communities, and the role they have played in moving the ecosystem forward. 

#### Examples

1. Projects that are "complete" by the maintainers' standards.
1. Projects that do not plan to release major versions in the future.

#### Expectations

Projects in this stage are not in active development. Their maintainers may infrequently monitor their repositories, and may only push updates to address security issues, if at all. Emeritus projects should clearly state their status and what any user or contributor should expect in terms of response or support. If there is an alternative project the maintainers recommend, it should be listed as well. The foundation will continue to hold the IP and any trademarks and domains, but the project does not draw on foundation resources. 

#### Acceptance Criteria

Projects may be granted Emeritus status through CPC consensus and with the approval of the maintainers of the project.
In cases where the project maintainers aren't responding after having been repeatedly contacted through appropriate channels about the CPC's intent to move the project to Emeritus stage, the CPC may proceed with the stage change without approval from the maintainers.

### Incubating

#### Definition

Incubating projects are projects that are in the process of completing their on-boarding checklist to join the foundation. Projects in this phase may be looking to join the foundation as At-Large or Impact Stage. Members of incubating projects are invited to join Cross Project Council meetings as a guest, please refer to the [CPC Charter](./CPC-CHARTER.md) for details on how guests may participate in the meetings.

#### Examples

1. Projects that have been accepted into incubation process after silent period.

#### Expectations

It is expected that incubating project will make an active effort to work through the on-boarding process in a reasonable timeframe. They will be offered foundation support to help do so.

#### Acceptance Criteria

1. consensus within private mailing list to move into incubation process

## IV. Growth Plan

At Large project that are interested in reaching Impact Stage need to develop a growth plan to so do. This plan needs to be developed in collaboration with the CPC and approved by it.

Once this growth plan is approved by the CPC, these projects will receive mentorship from the CPC and additional support from the Foundation in order to meet their goals, provided the project stays on track.

A project's progress toward its growth plan goals will be reviewed on a regular basis.

Projects are generally expected to meet their growth plan goals within two years.

## V. Sunsetting Checklist

<!--If this checklist is updated please ensure `https://github.com/openjs-foundation/project-status/blob/HEAD/.github/ISSUE_TEMPLATE/02-project-sunsetting-checklist-template.md` is updated as well -->

This is an informational checklist to help projects move to Emeritus Stage. Tasks will be completed together with the CPC and Foundation staff. The goal is to make sure that the Foundation is able to make required changes to the project if the need arises, and revive the project should this become desireable. If you have any questions or need help, the OpenJS Foundation CPC is available to assist.

- [ ] Decide in collaboration with the CPC whether the project needs to be archived or whether a call for maintenance is warranted
- [ ] Confirm all official domains that the project owns have been transfered to the OpenJS Foundation
- [ ] Cancel all cost-incurring infrastructure deployed by the project which is no longer necessary for Emeritus stage
- [ ] Provide admin access to all infrastructute deployed by the project which isn't cancelled
- [ ] Update project website, charter, and README to reflect Emeritus Stage
- [ ] If the project is making a call for maintenance, provide clear way to contact the CPC
- [ ] Archive the project
- [ ] Move [project logo](https://github.com/openjs-foundation/artwork) to Emeritus Stage section
- [ ] Move project logo on OpenJS Foundation website to Emeritus Stage section
- [ ] Mark project in the [CPC repo's README.md](https://github.com/openjs-foundation/cross-project-council/blob/HEAD/README.md#incubating-projects) as Emeritus
- [ ] Update security policy (see [PROJECT_SECURITY_REPORTING](https://github.com/openjs-foundation/cross-project-council/blob/HEAD/PROJECT_SECURITY_REPORTING.md))


## VI. Annual Review Process

The CPC shall develop an annual review process to determine whether projects are in the stage that accurately reflects their needs and goals. 

[Incubating]: #incubating
