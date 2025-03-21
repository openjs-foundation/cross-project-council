# OpenJS Foundation IP Policy Guidance

The purpose of this guide is to make it straightforward for projects to follow the [OpenJS Foundation IP Policy][IP Policy].

Of course, the source of truth remains the [IP Policy][].

If in doubt about anything related to IP after reading this document, first read the [IP Policy][], and then [ask for help](#getting-help).

## Basic requirements

There are four key requirements for all OpenJS Foundation projects:

1. [Licensing](#1-licensing)
2. [Copyright notices](#2-copyright-notices)
3. Displaying the [standard website footer](#3-standard-website-footer) on the project's website
4. [Adopting the DCO or a CLA](#4-adopting-the-dco-or-a-cla)

### 1. Licensing

Code may be licensed under:
  * [Apache, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
  * [Blue Oak Model License 1.0.0](https://opensource.org/license/blue-oak-model-license/)
  * [MIT](https://opensource.org/licenses/MIT)
  * [2-Clause BSD](https://opensource.org/licenses/BSD-2-Clause)
  * [3-Clause BSD](https://opensource.org/licenses/BSD-3-Clause)

Documentation may be licensed under:
  * [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
  * [MIT](https://opensource.org/licenses/MIT)

If you need to use a license which isn't in the [IP Policy][], you will
[need to obtain permission from the Board to do so](#obtaining-an-exemption-from-the-board).

### 2. Copyright notices

The recommendation is to use a general copyright statement of the following form (where XYZ is the project's name):

- **Copyright The XYZ Authors.**
- **Copyright The XYZ Contributors.**
- **Copyright Contributors to the XYZ project.**

By using this format, the project avoids having to deal with names of copyright holders, years or ranges of years, and variations on the (c) symbol.

If there are existing copyright lines add the recommended copyright statement below the existing copyright lines.

#### Editing existing copyright notices

You **must not** modify or remove existing copyright lines unless you put them there **and** have the right to do so.

However, you may update copyright lines that say "JS Foundation" or "Node.js Foundation" to "OpenJS Foundation" (as this simply reflects the merged status of the organizations) and remove the year(s) from copyright lines that mention the project or the foundation's name.

For example:

    * `Copyright 2025 John Doe.` **must not** be modified or removed.
    * `Copyright 2025 The XYZ Authors.` may be updated to `Copyright The XYZ Authors.`
    * `Copyright 2025 Node.js Foundation.` may be updated to `Copyright OpenJS Foundation.`


### 3. Standard website footer

All project websites need to have a [standard website footer][].

### 4. Adopting the DCO or a CLA

Each project must adopt either the [Developer Certificate of Origin (DCO)][DCO] or a Contributor License Agreement (CLA).

#### DCO

There are two options for implementing the DCO on your project:

1. By installing the [DCO bot](https://github.com/apps/dco) 
2. By including the following in your repository:
   1. Adding the DCO to your CONTRIBUTING.md file, [example](https://github.com/nodejs/node/blob/main/CONTRIBUTING.md)
   2. Adding the DCO to your PR templates, [example](https://raw.githubusercontent.com/nodejs/node/main/.github/PULL_REQUEST_TEMPLATE.md)

The DCO Bot is the preferred method and is also recommended for projects that require strict enforcement.

#### CLA

The Board has pre-approved an [individual CLA][ICLA] and a [corporate CLA][CCLA].
Projects can choose to adopt either the individual CLA by itself or both the individual CLA and the corporate CLA without any further review.

If you need to use a different CLA, you must
[obtain an exemption from the board](#obtaining-an-exemption-from-the-board).

CLAs are managed through [EasyCLA](https://docs.linuxfoundation.org/lfx/easycla). 


## Obtaining an exemption from the Board

If your project requires an exemption from the [IP Policy][], you will need to obtain special permission from the Board.
To do so, please [open an issue in the Cross Project Council repository](https://github.com/openjs-foundation/cross-project-council/issues/new?title=Board%20exemption%20request%20for), and assign or @-mention [@bensternthal](https://github.com/bensternthal) and [your Project Representatives](https://github.com/openjs-foundation/cross-project-council#impact-project-representatives) if your are an Impact project, the [At Large Project Representatives](https://github.com/openjs-foundation/cross-project-council#at-large-project-representatives) if you are an At Large project, or [your Champion](https://github.com/openjs-foundation/cross-project-council/blob/HEAD/PROJECT_PROGRESSION.md#application-champion) if you are an Incubating project.

## Getting help

If you have any questions about this policy or need assistance with its implementation, please contact the [OpenJS staff](mailto:operations@openjsf.org).

[IP Policy]: https://ip-policy.openjsf.org
[DCO]: https://developercertificate.org
[ICLA]: https://individual-cla.openjsf.org
[CCLA]: https://corporate-cla.openjsf.org
[standard website footer]: https://github.com/openjs-foundation/artwork#copyright-notices-for-project-website-footers
