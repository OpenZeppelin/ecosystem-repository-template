<!-- Template: rename this file to SECURITY.md and delete the other SECURITY_*.md variant.
     Replace every {{...}} placeholder, then delete this comment. The OPTIONAL block stays
     hidden until a bug bounty program covers this repository. -->

# Security Policy

Security vulnerabilities should be [disclosed](#reporting-a-vulnerability) to the [project maintainers](./.github/CODEOWNERS), or alternatively by email to <security@openzeppelin.com>.

<!-- OPTIONAL — uncomment once a bug bounty program covers this repository, and change the
     sentence above to: "...disclosed to the project maintainers through [Immunefi], or
     alternatively by email to <security@openzeppelin.com>."

[Immunefi]: {{immunefi-program-url}}

## Bug Bounty

Responsible disclosure of security vulnerabilities is rewarded through a bug bounty program on
[Immunefi].

-->

## Supported Versions

The following versions are currently supported and receive security updates. Alpha, Beta and Release candidates will not receive security updates.

Security patches will be released for the latest minor of a given major release. For example, if an issue is found in versions >=1.13.0 and the latest is 1.14.0, the patch will be released only in version 1.14.1.

Only critical severity bug fixes will be backported to past major releases.

| Version   | Supported          |
| --------- | ------------------ |
| >= 0.1.x  | :white_check_mark: |
| <= 0.0.9  | :x:                |

## Reporting a Vulnerability

We're extremely grateful for security researchers and users that report vulnerabilities to us.
All reports are thoroughly investigated by the project's security team.

Vulnerabilities are reported privately via GitHub's [Security Advisories](https://docs.github.com/en/code-security/security-advisories) feature.
Please use the following link to submit your vulnerability: [Report a vulnerability](https://github.com/openzeppelin/{{Project name}}/security/advisories/new)

Please see
[Privately reporting a security vulnerability](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability#privately-reporting-a-security-vulnerability)
for more information on how to submit a vulnerability using GitHub's interface.

## Legal

{{Project name}} is made available under the GNU AGPL 3.0 License, which disclaims all warranties in relation to the project and which limits the liability of those that contribute and maintain the project, including OpenZeppelin. Your use of the project is also governed by the terms found at <https://www.openzeppelin.com/tos> (the "Terms"). As set out in the Terms, you are solely responsible for any use of {{Project name}} and you assume all risks associated with any such use. This Security Policy in no way evidences or represents an on-going duty by any contributor, including OpenZeppelin, to correct any flaws or alert you to all or any of the potential risks of utilizing the project.
