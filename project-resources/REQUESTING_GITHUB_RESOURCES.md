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

The process for requesting Github resources is:

1. Estimate your monthly spend using https://github.com/pricing/calculator
1. Create and submit a PR using the template for CPC approval
1. If approved the CPC will discuss with OpenJS staff in the next CPC meeting
1. Once fully approved, you will need to add OpenJS staff as a billing manager on your project
    - Billing Managers have only access to Billing Settings on your GitHub organization
1. OpenJS will add a credit card and implement spending limits consistent with the request

The Pull Request template below should be completed with a Pull Request containing an addition to the `GITHUB_REQUESTS/{CurrentYear}.md` spreadsheet from this repository, filling the required information.

> [!NOTE]\
> The costs are are billed on a monthly-basis. Hence the the costs should be calculated on a monthly-basis.

### Best Practices

These best practices are a set of recommendations for maintaining a healthy usage of the resources.

#### Codespaces Best-Practices

- When enabling Codespaces, we recommend that only a set of repositories have Codespaces enabled, to avoid it being used on projects that do not require Codespaces.
- We recommend setting policies that best fit your project needs, but that are reasonable in terms of resource usages, such as:
  - Limiting the amount of concurrent Codespaces a member might own
  - Defining a reasonable timeout policy to avoid extra unnecessary costs
- If your organization has a large amount of members, we recommend limiting the access of Codespaces to members that would benefit from it and possibly making it an opt-in process (so that members request access to Codespaces)
  - This is a recommended practice as if individual members accidentally reach the budgetry limit defined, this affects everyones usage of Codespace as the feature would be locked out until the next billing cycle

### GitHub Resource Request PR Template

```md
## GitHub Resource Request for {Project Name}

- **Estimated monthly cost:** USD XXXX
- **Requested Features:**
  - [ ] Actions
  - [ ] Codespaces
  - [ ] Extra Large Runners (Actions)
- **Fund Request Champions:**
  - Champion A (@handle)
  - Champion B (@handle)

### Intended usage of the resources

<!-- For what kind of resources should the monetary resources be allocated how are they intended to be used -->

<!-- Feel also free to add relevant links to Issues, Discussions and Slack threads -->

cc @openjs-foundation/cpc
```

## Approvals

The request is submitted to the CPC for evaluation.
The CPC evaluates the request following its [decision-making process](https://github.com/openjs-foundation/cross-project-council/blob/main/CPC-CHARTER.md#section-9-decision-making) and if approved, informs OpenJS staff that the request needs budget approval.
Requests approved by the CPC are subject to final budget approval by the OpenJS Foundation.
