# Transferring an existing repository into the organization

## Step 1. Get the repository ready

Ideally, the repository should have the following documents in place:

- `CODE_OF_CONDUCT.md`: it can be a reference to
  [the OpenJS Foundation's Code of Conduct](https://github.com/openjs-foundation/cross-project-council/blob/master/CODE_OF_CONDUCT.md).
- `CONTRIBUTING.md`: if there isn't one already, [the contributing guide][]
  of Node.js core could be a good example. Consider including the Developer's
  Certificate of Origin section in the document to avoid potential copyright
  conflicts.
- `LICENSE`, or other kind of documents that describe the license of
  the project.
- `README.md`

## Step 2. Open an issue in the cross-project-council repository

_The person opening the issue should be a member of the Cross Project Council
so they can ping the relevant GitHub teams to discuss the request.
If the person who wants to initiate the request is not a member, they could ask
an existing member to open the issue._

Go to [the issue tracker of the Cross Project Council repository][], open an issue to request moving the repository into the organization. The issue should include:

- The owner and the name of the repository, and a link to it.
- What the repository is for, why it should be transferred into the organization.
- Mention `@openjs-foundation/cpc` so the Cross Project Council members can be
  notified about the request and weigh in.

See the [OpenJS Foundation GitHub Organization Management Policy][] on how the request is approved.

## Step 3. Transfer the repository

When the request is approved, the owner of the repository can start transferring
the repository into the OpenJS GitHub organization. The person can be made a
member of the OpenJS GitHub organization so they have the necessary permissions
to complete the transfer.

See [GitHub's documentation on transferring repos][] on how to perform the necessary actions.


[GitHub's documentation on transferring repos]: https://help.github.com/articles/about-repository-transfers/
[OpenJS Foundation GitHub Organization Management Policy]: https://github.com/openjs-foundation/cross-project-council/blob/master/GITHUB_ORG_MANGEMENT_POLICY.md
[the contributing guide]: ./CONTRIBUTING.md
[the issue tracker of the Cross Project Council repository]: https://github.com/openjs-foundation/cross-project-council/issues
