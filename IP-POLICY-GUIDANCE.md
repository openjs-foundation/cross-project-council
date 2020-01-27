<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# OpenJS Foundation IP Policy Guidance

The purpose of this document is to provide an introduction to various aspects
of the [OpenJS Foundation IP Policy](https://ip-policy.openjsf.org). Please
note, if something appears inconsistent between the two documents, the IP
Policy is always the canonical source of information. This document is merely
meant to be interpretive, and changes to this document have no effect upon the
[IP Policy](https://ip-policy.openjsf.org) unless the Board of Directors votes
to accept them.

## Essential Guidance

We encourage everyone to [read the IP Policy](https://ip-policy.openjsf.org).
It is intentionally short and to the point.

At a high level, you will find the following key themes:

1. _DO NOT_ change copyright lines unless you put them there _AND_ have the right
to update them.  If you feel a need to add a _new_ copyright line, see the
[copyright guidance](#copyrights-and-openjs-foundation-projects).
1. You can use any of the open source licenses that are pre-approved in the
[IP Policy](https://ip-policy.openjsf.org) without any additional approvals.
1. If you need to use a license which isn't in the list, please ask the board.
1. Your project website needs to have a
[standard website footer](#copyright-notices-for-website-footers).
1. If in doubt about anything related to IP, first read the
[IP Policy](https://ip-policy.openjsf.org), and then
[ask for help](#getting-help).

There are also some optional things that projects can do which, while not
mandatory, are referenced in the IP Policy or in this guidance. For example:

1. You may update copyright lines that say "JS Foundation" or
"Node.js Foundation" to "OpenJS Foundation".  This is a factual update
reflecting the merged status of the organizations.
1. You may decide to use the [CLA](https://cla.openjsf.org), or decide to stop
using one.  This is optional under the OpenJS Foundation IP Policy, and is a
decision that is to be made by the project's maintainers.
1. Inserting [SPDX IDs](https://spdx.org/ids-how): While projects decide the
manner in which they communicate license information, SPDX short identifiers
are a good option because they improve the accuracy of automated license
scanners. If you are updating header information anyhow, they are a simple
one-line addition.

Please reach out to the Foundation with any questions on topics related to the
IP Policy by emailing
[legal-questions@lists.openjsf.org](mailto:legal-questions@lists.openjsf.org).

## Copyrights and OpenJS Foundation projects

### Ownership of Copyrights in OpenJS Foundation Contributions

When source code, documentation and other content is contributed to an Open JS Foundation
project, the copyrights in those contributions remain owned by the original
copyright holders.

The copyrights are not _assigned_ to OpenJS Foundation. Instead, they are _licensed_ for
distribution as part of the project. Whether a project uses the DCO or a CLA,
the original copyright holders retain their copyrights.

### Copyright Notices

OpenJS Foundation does not require or recommend that every contributor include their
copyright notice in contributed files. [See below for more details on why
not.](#why-not-list-every-copyright-holder)

Instead, OpenJS Foundation recommends using a more general statement in a form similar to the
following (where XYZ is the project's name):

- **Copyright The XYZ Authors.**
- **Copyright The XYZ Contributors.**
- **Copyright Contributors to the XYZ project.**

These statements are intended to communicate the following:
- the work is copyrighted;
- the contributors of the code licensed it, but retain ownership of their copyrights; and
- it was licensed for distribution as part of the named project.

By using a common format, the project avoids having to deal with names of
copyright holders, years or ranges of years, and variations on the (c) symbol.
This aims to minimize the burden on developers and maintainers as well as
redistributors of the code.

### What if I want my copyright notice included?

Please note that it is _not wrong_, and it is acceptable, if a contributor
wishes to keep their own copyright notices on their contributions. The above is
a recommended format for ease of use, but is not mandated by OpenJS Foundation.

If you are contributing on behalf of your employer, you may wish to discuss with
your legal department about whether they will require you to include a copyright
notice identifying them as the copyright holder in contributions.

### What about Third Party Code?

If a file only contains code that originates from a third party source who
didn't contribute it themselves, then you would _not_ want to add the notices
above. (In a similar vein, you wouldn't add a notice identifying you as the
copyright holder either, if you didn't own it.) Just preserve the existing
copyright and license notices as they are.

If, however, you add copyrightable content to a pre-existing file from another
project, then at that point you could _add_ a copyright notice similar to the
one above.

## Don't Change Someone Else's Notice without their Permission

You _should not_ change or remove someone else's copyright notice unless they
have expressly permitted you to do so. This includes third parties' notices in
pre-existing code.

### Why not list every copyright holder?

There are several reasons why OpenJS Foundation doesn't require or recommend trying to list
every copyright holder for contributions to every file:

- Copyright notices are not mandatory in order for the contributor to retain
  ownership of their copyright.
- Copyright notices are rarely kept up to date as a file evolves, resulting in
  inaccurate statements.
- Trying to keep notices up to date, or to correct notices that have become
  inaccurate, increases the burden on developers without tangible benefit.
- Developers and maintainers often do not want to have to worry about e.g.
  whether a minor contribution (such as a typo fix) means that a new copyright
  notice should be added.
- Adding many different copyright notices may increase the burden on downstream
  distributors, if their license compliance processes involve reproducing
  notices.
- The specific individual or legal entity that owns the copyright might not be
  known to the contributor; it could be you, your employer, or some other entity.

### Copyright notices for website footers

Please use one of these standard footers, which have been approved by OpenJS
Foundation legal counsel and the Board of Directors:

#### For nodejs.org, and projects which reference Node.js

##### Text

> Copyright [OpenJS Foundation](https://openjsf.org) and [project name] contributors. All rights reserved. The [OpenJS Foundation](https://openjsf.org) has registered trademarks and uses trademarks.  For a list of trademarks of the [OpenJS Foundation](https://openjsf.org), please see our [Trademark Policy](https://trademark-policy.openjsf.org/) and [Trademark List](https://trademark-list.openjsf.org/).  Node.js is a trademark of Joyent, Inc. and is used with its permission.  Trademarks and logos not indicated on the [list of OpenJS Foundation trademarks](https://trademark-list.openjsf.org) are trademarks™ or registered® trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.
> 
> [The OpenJS Foundation](https://openjsf.org/) | [Terms of Use](https://terms-of-use.openjsf.org/) | [Privacy Policy](https://privacy-policy.openjsf.org/) | [OpenJS Foundation Bylaws](https://bylaws.openjsf.org/) | [Trademark Policy](https://trademark-policy.openjsf.org/) | [Trademark List](https://trademark-list.openjsf.org/) | [Cookie Policy](https://www.linuxfoundation.org/cookies/)

##### Markdown

```
Copyright [OpenJS Foundation](https://openjsf.org) and [project name] contributors. All rights reserved. The [OpenJS Foundation](https://openjsf.org) has registered trademarks and uses trademarks.  For a list of trademarks of the [OpenJS Foundation](https://openjsf.org), please see our [Trademark Policy](https://trademark-policy.openjsf.org/) and [Trademark List](https://trademark-list.openjsf.org/).  Node.js is a trademark of Joyent, Inc. and is used with its permission.  Trademarks and logos not indicated on the [list of OpenJS Foundation trademarks](https://trademark-list.openjsf.org) are trademarks™ or registered® trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.

[The OpenJS Foundation](https://openjsf.org/) | [Terms of Use](https://terms-of-use.openjsf.org/) | [Privacy Policy](https://privacy-policy.openjsf.org/) | [OpenJS Foundation Bylaws](https://bylaws.openjsf.org/) | [Trademark Policy](https://trademark-policy.openjsf.org/) | [Trademark List](https://trademark-list.openjsf.org/) | [Cookie Policy](https://www.linuxfoundation.org/cookies/)
```

##### HTML

```
<p>Copyright <a href="https://openjsf.org">OpenJS Foundation</a> and [project name] contributors. All rights reserved. The <a href="https://openjsf.org">OpenJS Foundation</a> has registered trademarks and uses trademarks.  For a list of trademarks of the <a href="https://openjsf.org">OpenJS Foundation</a>, please see our <a href="https://trademark-policy.openjsf.org">Trademark Policy</a> and <a href="https://trademark-list.openjsf.org">Trademark List</a>.  Node.js is a trademark of Joyent, Inc. and is used with its permission. Trademarks and logos not indicated on the <a href="https://trademark-list.openjsf.org">list of OpenJS Foundation trademarks</a> are trademarks&trade; or registered&reg; trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.</p>

<p><a href="https://openjsf.org">The OpenJS Foundation</a> | <a href="https://terms-of-use.openjsf.org">Terms of Use</a> | <a href="https://privacy-policy.openjsf.org">Privacy Policy</a> | <a href="https://bylaws.openjsf.org">OpenJS Foundation Bylaws</a> | <a href="https://trademark-policy.openjsf.org">Trademark Policy</a> | <a href="https://trademark-list.openjsf.org">Trademark List</a> | <a href="https://www.linuxfoundation.org/cookies">Cookie Policy</a></p>
```

#### For projects unrelated to Node.js:

##### Text

> Copyright [OpenJS Foundation](https://openjsf.org) and [project name] contributors. All rights reserved. The [OpenJS Foundation](https://openjsf.org) has registered trademarks and uses trademarks.  For a list of trademarks of the [OpenJS Foundation](https://openjsf.org), please see our [Trademark Policy](https://trademark-policy.openjsf.org/) and [Trademark List](https://trademark-list.openjsf.org/).  Trademarks and logos not indicated on the [list of OpenJS Foundation trademarks](https://trademark-list.openjsf.org) are trademarks™ or registered® trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.
> 
> [The OpenJS Foundation](https://openjsf.org/) | [Terms of Use](https://terms-of-use.openjsf.org/) | [Privacy Policy](https://privacy-policy.openjsf.org/) | [OpenJS Foundation Bylaws](https://bylaws.openjsf.org/) | [Trademark Policy](https://trademark-policy.openjsf.org/) | [Trademark List](https://trademark-list.openjsf.org/) | [Cookie Policy](https://www.linuxfoundation.org/cookies/)

##### Markdown

```
Copyright [OpenJS Foundation](https://openjsf.org) and [project name] contributors. All rights reserved. The [OpenJS Foundation](https://openjsf.org) has registered trademarks and uses trademarks.  For a list of trademarks of the [OpenJS Foundation](https://openjsf.org), please see our [Trademark Policy](https://trademark-policy.openjsf.org/) and [Trademark List](https://trademark-list.openjsf.org/).  Trademarks and logos not indicated on the [list of OpenJS Foundation trademarks](https://trademark-list.openjsf.org) are trademarks™ or registered® trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.

[The OpenJS Foundation](https://openjsf.org/) | [Terms of Use](https://terms-of-use.openjsf.org/) | [Privacy Policy](https://privacy-policy.openjsf.org/) | [OpenJS Foundation Bylaws](https://bylaws.openjsf.org/) | [Trademark Policy](https://trademark-policy.openjsf.org/) | [Trademark List](https://trademark-list.openjsf.org/) | [Cookie Policy](https://www.linuxfoundation.org/cookies/)
```

##### HTML

```
<p>Copyright <a href="https://openjsf.org">OpenJS Foundation</a> and [project name] contributors. All rights reserved. The <a href="https://openjsf.org">OpenJS Foundation</a> has registered trademarks and uses trademarks.  For a list of trademarks of the <a href="https://openjsf.org">OpenJS Foundation</a>, please see our <a href="https://trademark-policy.openjsf.org">Trademark Policy</a> and <a href="https://trademark-list.openjsf.org">Trademark List</a>.  Trademarks and logos not indicated on the <a href="https://trademark-list.openjsf.org">list of OpenJS Foundation trademarks</a> are trademarks&trade; or registered&reg; trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.</p>

<p><a href="https://openjsf.org">The OpenJS Foundation</a> | <a href="https://terms-of-use.openjsf.org">Terms of Use</a> | <a href="https://privacy-policy.openjsf.org">Privacy Policy</a> | <a href="https://bylaws.openjsf.org">OpenJS Foundation Bylaws</a> | <a href="https://trademark-policy.openjsf.org">Trademark Policy</a> | <a href="https://trademark-list.openjsf.org">Trademark List</a> | <a href="https://www.linuxfoundation.org/cookies">Cookie Policy</a></p>
```

## Getting help

If you have a question about this policy or how to implement it, please reach out to [legal-questions@lists.openjsf.org](mailto:legal-questions@lists.openjsf.org).

