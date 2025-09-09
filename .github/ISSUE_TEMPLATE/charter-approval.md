body:
- type: input
  id: name
  attributes:
    label: Project name
  validations:
    required: true
- type: dropdown
  id: type
  attributes:
    label: Is this for a new charter or for changes to an existing one?
    options:
      - New charter
      - Charter change
  validations:
    required: true
- type: input
  id: url
  attributes:
    label: Link to the open pull request on the project repository
  validations:
    required: true
- type: textarea
  id: info
  attributes:
    label: Please provide any information you believe is useful for the CPC to review this charter change.
- type: markdown
  attributes:
    value: |
      CPC Members, please review and approve the open pull request linked above.
