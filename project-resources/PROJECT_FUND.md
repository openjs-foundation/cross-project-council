# OpenJS Foundation Project-specific Initiative Funds

The OpenJS Foundation (OpenJSF) provides a set of monetary funds for projects of the OpenJSF.
These funds are designed to support collaboration and incentive project-specific initiatives that have high-impact within the individual project's scope.

Alongside these lines, the fund exists to support the development of the project when the volunteer-based approach is not enough to support the community, e.g. infrastructure, tools, or security.

## Archive of Past Project Funds

The list below contains a historical archive and reference of past approved project fund requests.

- [2023](../PROJECT_FUND/2023.md)

## Requesting Project Funds

Funds should be requested on an ad-hoc basis through a PR requesting the funds.
The level of funding will be determined on a case-by-case basis after consideration of the request and discussion with the project maintainers.

The requests should follow a specific template and contain relevant information regarding the project initiative, as well as any information that might be useful to highlight the need for funds and their benefits.

The Pull Request template below should be completed with a Pull Request containing an addition to the `PROJECT_FUND/{CurrentYear}.md`
spreadsheet from this repository, filling the required information.

### Fund Request PR Template

```md
## Fund Request for {Project Name}

- **Total amount of funds requested:** USD XXXX.XX
- **Fund Request Champions:**
  - Champion A (@handle)
  - Champion B (@handle)

### Purpose of the Request

<!-- Explain what is the ultimate goal this fund request aims to achieve -->

### Intended usage of the resouces

<!-- For what kind of resources should the monetary resources be allocated how are they intended to be used -->

### Success Criteria

<!-- What are the methods used to evaluate that the fund request had a positive outcome -->

### Distribution of the Funds

<!-- Explain here how these funds will be distributed/used -->
<!-- Feel free to use a Markdown Table or a List for breaking down the costs (tablesgenerator.com/markdown_tables) -->

### Timeline of the Request

<!-- Explain (possibly with a bullet-list) the timeline of the request, and how/when each part of the funds are being used -->

cc @openjs-foundation/cpc
```

## Process

The request must be made to the CPC for evaluation. The CPC evaluates the request following its [decision-making process](https://github.com/openjs-foundation/cross-project-council/blob/main/CPC-CHARTER.md#section-9-decision-making) and makes a recommendation to the Board.
Finally the request should be forwarded to the Board of Directors for final approval.

## Evaluation

An evaluation should be done after the conclusion of the timeline of the fund request. Ideally as a comment on the same PR as it would notify the current people subscribed to the Pull Request. The template below contains the recommended format for the evaluation, but we believe more/less information can be added by the champions of the request through good judgement.

```md
## Post-request Evaluation

<!-- This should be written ad-hoc after the timeline was concluded -->

#### How was the money spent

<!-- How did the money get spent; did it follow the timeline? What diverged? -->

---

- [ ] **Was the success criteria met?**
  - If not, please explain why and if possible any learnings.
```
