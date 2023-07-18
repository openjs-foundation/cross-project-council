# OpenJS Foundation GitHub Resources Requests

OpenJS Foundation can provide monthly funding for the following Github resources:

- Actions
- Codespaces
- Extra Large Runners (Actions)

Funding for resources requires:

1. CPC Approval
2. OpenJS Foundation Budget Approval

## Archive of Approved Requests

The list below contains a historical archive and reference of past approved project fund requests.

- [2023](./GITHUB_REQUESTS/2023.md)

## Requesting GitHub Resources

The process for requesting Github resources is as follows:

1. Estimate your monthly spend using https://github.com/pricing/calculator
2. Create a PR using the below template
3. Sumbit PR for CPC approval
4. If approved bring forward to OpenJS staff for budget approval
5. Once fully approved, OpenJS will need to be added as a billing manager, so that a virtual credit card can be
added.
6. OpenJS will implement spending limits consistent with the request


The requests should follow a specific template and contain relevant information regarding the requested features, as well as any information that might be useful to highlight the need for the requested features.

The Pull Request template below should be completed with a Pull Request containing an addition to the `GITHUB_REQUESTS/{CurrentYear}.md`
spreadsheet from this repository, filling the required information.

### Best Practices

These best practices are a set of recommendations for maintaining a healthy usage of the resources.

#### Codespaces Best-Practices

- When enabling Codespaces, we recommend that only a set of repositories have Codespaces enabled, to avoid it being used on projects that do not require Codespaces.
- We recommend setting policies that best fit your project needs, but that are reasonable in terms of resource usages, such as:
  - Limiting the amount of concurrent Codespaces a member might own
  - Defining a reasonable timeout policy to avoid extra unnecessary costs
- If your organisation has a large amount of members, we recommend limiting the access of Codespaces to members that would benefit from it and possibly making it an opt-in process (so that members request access to Codespaces)
  - This is a recommended practice as if individual members accidentally reach the budgetry limit defined, this affects everyones usage of Codespace as the feature would be locked out until the next billing cycle

### GitHub Resource Request PR Template

```md
## GitHub Resource Request for {Project Name}

- **Estimated monthly spend:** USD XXXX.XX
- **Requested Features:**
  - [ ] Actions
  - [ ] Codespaces
  - [ ] Extra Large Runners (Actions)
- **Fund Request Champions:**
  - Champion A (@handle)
  - Champion B (@handle)

### Intended usage of the resouces

<!-- For what kind of resources should the monetary resources be allocated how are they intended to be used -->

### Distribution of the Funds

<!-- Explain here how these funds will be distributed/used -->
<!-- Feel free to use a Markdown Table or a List for breaking down the costs (tablesgenerator.com/markdown_tables) -->

### Timeline of the Request

<!-- Explain (possibly with a bullet-list) the timeline of the request, and how/when each part of the funds are being used -->

cc @openjs-foundation/cpc
```

## Approvals

The request is submitted to the CPC for evaluation. The CPC evaluates the request following its [decision-making process](https://github.com/openjs-foundation/cross-project-council/blob/main/CPC-CHARTER.md#section-9-decision-making) and if approved, informs OpenJS staff
that the request needs budget approval. Requests approved by the CPC are subject to final budget approval by
the OpenJS Foundation.
