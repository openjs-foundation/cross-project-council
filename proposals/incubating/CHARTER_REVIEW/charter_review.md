# Charter Submission, Review & Approval Process

This section describes how to submit charter documents for review, and how the CPC conducts project charter reviews for new projects, or for projects that may make changes to their charters from time to time.

Project charter documents live in project repositories - not in the CPC repository. 

## Submitting a project charter document
All project charters should follow the format of the PROJECT_CHARTER_TEMPLATE.md document located in this repository.

### Submitting a new charter (for onboarding projects)

Once your project team has drafted its charter following the template above and is satisfied that it accurately reflects the project:

* Open a pull request to add the charter on the appropriate repo in your project repository - for example, this is often an 'admin', 'meta', or 'documentation' repository. It should be in the same repository that the project uses for its Code of Conduct and Governance documents.  
* File an issue in the Project Onboarding repository - Titled *New {$Project Name} Charter Document* and include a link to this pull request.
* Tag '@openjs-foundation/cpc' on the issue - this notifies all CPC members that a document is ready for their review.
* Add the 'cross-project-council-agenda' label to the issue - this will ensure the issue is taken up at the next CPC meeting. 
* If the project would like to request legal review, note that in the issue as well (this is optional at the request of the project or the CPC).

### Submitting an update to an existing charter

If your project has decided that its existing charter document needs to be updated, complete the following steps:

* Open a pull request to update your previously approved charter. Make sure changes remain in the format of the PROJECT_CHARTER_TEMPLATE.md.
* File an issue in the Cross-Project-Council repository - Titled *Update {$Project Name} Charter Document* and include a link to this pull request.
* Tag '@openjs-foundation/cpc' on the issue - this notifies all CPC members that a document is ready for their review.
* Add the 'cross-project-council-agenda' label to the issue - this will ensure the issue is taken up at the next CPC meeting. 
* If the project would like to request legal review, note that in the issue as well (this is optional at the request of the project or the CPC).

## Reviewing a charter

Project Charters are the responsibility of the CPC. When reviewing a charter, the CPC shall evaluate:

1. The completeness of the document - all sections marked required in the PROJECT_CHARTER_TEMPLATE.md are filled out. Optional sections that have not been filled out are marked as intentionally omitted.
1. The comprehensibility of the document - a person familiar with the field but unfamiliar with the project should be able to read the charter and have a sound understanding of where it fits in the ecosystem. 
1. The accuracy of the document - the document should reflect the reality of the project. It should avoid hyperbolic language (e.g. "world's best developer experience"). 
1. The lifespan of the document - the CPC should take note of what factors may cause the charter document to change. If data that may change frequently appears in the charter - such as a list of names - the CPC may ask to remove it. 

If the project handles Personally Identifiable Information (PII), deals with a new intersection between technology and law, or would simply feel more comfortable, they or the CPC Board Representative may request review from Foundation legal counsel. This is an optional step.

CPC members should add themselves as reviewers to the associated charter issue. Comments or suggested edits to the charter document should be captured on the Pull Request. 

## Approving a charter

Project Charters should be reviewed and approved within two weeks of submission. An exception may be made if the charter is submitted during a holiday period (such as the end of the year) or in the event either the project or CPC has requested legal review. 

Charters are approved when they meet the requirements outlined in the 'Approving Charters' section of [GOVERNANCE.md](https://github.com/openjs-foundation/cross-project-council/blob/master/GOVERNANCE.md#approving-project-charters).
