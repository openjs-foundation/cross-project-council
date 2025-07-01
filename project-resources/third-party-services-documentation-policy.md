# OpenJS Third Party Services Documentation Policy

## **Summary**

This policy establishes communications and documentation guidelines that allow the OpenJS Foundation to maintain visibility of the third party services OpenJS hosted projects are currently using or planning to in the future.

The Foundation wishes to leverage this information to:

* Identify opportunities for strategic vendor partnerships  
* Provide support and guidance for vendor partnerships  
* Understand development infrastructure needs across Foundation projects

This policy is intended to be structured in a way that enables the Foundation to understand and foster partnerships while respecting project autonomy and security considerations.

# **Policy: Notify the Foundation before changing existing significant service providers or engaging new ones**

Before engaging with a significant third-party SaaS or infrastructure provider, projects are asked to contact the OpenJS Foundation (Robin Ginn and Ben Sternthal) at [operations@openjsf.org](operations@openjsf.org). The Foundation may have an existing arrangement or might want to establish a new partnership. 

# **Policy: Maintain documentation of services**

All projects hosted by the OpenJS Foundation are asked to maintain a service registry file that documents significant third-party SaaS products and infrastructure providers used by the project. An example of the content and structure of this file can be found below under **services.md content and format**.

This policy has three components: 1) have the file, 2) make it accessible to OpenJS, and 3) keep the file up to date and notify OpenJS.

Projects may choose to use an OpenJS services.md file or their own service registry documentation.

**Policy Table of Contents**

- [1) Have a service registry file  
  - Option 1: Use an OpenJS services.md file  
  - Option 2: Use your own service registry documentation
- [2) Ensure the service registry is accessible to the OpenJS Foundation
- [3) Keep the service registry file up to date and notify the OpenJS Foundation of changes

## **1. Have a service registry file**

Projects have two options for how to:

* **Option 1:** Use a `services.md` file  
* **Option 2:** Use their own service registry file that contains at least the equivalent detail as an OpenJS `services.md` file

Regardless of their choice, the file must be shared with the OpenJS Foundation (Robin Ginn and Ben Sternthal).

### **Option 1: Use a services.md file**

Project maintainers can choose to use a `services.md` file to document significant third-party SaaS products and infrastructure providers used by the project.

`Services.md` may be as simple as a Markdown list like the one illustrated below. This example is illustrative and not intended to necessarily be comprehensive on what could be included as each project may have additional items unique to them.

#### **`Services.md` content and format**

```
# Third-Party Services Used

This project relies on the following third-party services:

## Hosting & Infrastructure
- **Cloud Provider:** AWS (EC2, S3)
- **CDN:** Cloudflare
- **DNS Provider:** Namecheap

## Development & CI/CD
- **Code Repository:** GitHub
- **CI/CD:** GitHub Actions, Travis CI
- **Artifact Storage:** Docker Hub, NPM

## Monitoring & Security
- **Logging:** Datadog
- **Error Tracking:** Sentry
- **Dependency Management:** Dependabot
- **Security Scanning:** CodeQL

## Communication & Support
- **Email Provider:** SendGrid
- **Issue Tracking:** GitHub Issues
```

Keep entries high-level. Do not include sensitive information such as vendor contacts, contract or license information, or specific data about the infrastructure itself, especially if the file is expected to be public.

### **Option 2: Use your own services registry documentation**

Project maintainers may choose to continue using their own existing service registry or create a more customized service registry file. The only requirement for this is that the service registry file contains the same level of detail as an OpenJS `services.md` file.

## **2. Ensure the service registry is accessible to the OpenJS Foundation**

Projects have two options on how to approach storing and granting OpenJS access to their service registry file. Regardless of the approach, the service registry file must be accessible to the OpenJS Executive Director Robin Ginn ([@rginn](https://www.github.com/rginn), [rginn@openjsf.org](mailto:rginn@openjsf.org)) and OpenJS Director of Program Management Ben Sternthal ([@bensternthal](https://www.github.com/bensternthal), [bsternthal@linuxfondation.org](mailto:bsternthal@linuxfondation.org)).

* **Option 1: Store the service registry file in the Project’s own GitHub organization**  
* **Option 2: Store the service registry file elsewhere**

Project maintainers must proactively inform the Foundation of where their service registry file is located by emailing [operations@openjsf.org](mailto:operations@openjsf.org).

### **Option 1:** **Store the service registry file in the Project’s own GitHub organization**

Projects may choose, at their own discretion, to place this file anywhere in their GitHub organization in either a public or private repository. The level of detail expected of the `services.md` file is typically not sensitive and often easily discovered; however, the Foundation leaves the decision of where the file is stored to each project's preferences and governance.

### **Option 2: Store the service registry file elsewhere**

Projects are free to choose another location, such as a Google Workspace or hackmd.io, to store their service registry file.

## **3. Keep the service registry file up to date and notify the OpenJS Foundation of changes**

The service registry file is to be updated as necessary to remain an accurate reflection of the current state of the project. Under certain circumstances, such as during a transition, it may be appropriate for the service registry file to also contain credible plans for future or in progress changes.

When considering or performing updates to the service registry file, regardless of where it is stored, inform Robin Ginn and Ben Sternthal by:

* Contacting [operations@openjsf.org](mailto:operations@openjsf.org) in advance of making a change.  
* Including [@rginn](https://www.github.com/rginn) and [@bensternthal](https://www.github.com/bensternthal) on issues, discussions, and pull requests regarding the change.

**If the service registry is stored in GitHub:**

* Include Robin Ginn ([@rginn](https://www.github.com/rginn)) and Ben Sternthal ([@bensternthal](https://www.github.com/bensternthal)) as collaborators with read access to the repository containing the service registry file so they can watch the repository for changes.

**If the service registry is stored elsewhere:**

* Grant Robin Ginn ([rginn@openjsf.org](mailto:rginn@openjsf.org)) and Ben Sternthnal ([bsternthal@linuxfondation.org](mailto:bsternthal@linuxfondation.org)) adequate permissions so that they can monitor the file for changes.

## **Questions and Support**

For questions about this policy or assistance with implementation, please contact the [OpenJS Foundation](operations@openjsf.org).

