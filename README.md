# GfK Open Source Policy

## General

-   GfK encourages contributions to existing open source projects used by us.
-   GfK also encourages releasing new open source projects on the GfK GitHub account.
-   Always ensure that you do not share
    -   Confidential information, e.g. credentials.
    -   Details on our infrastructural setup, which could widen our attack surface.
    -   Code and algorithms giving us an edge over competitors.
    -   Any data owned by GfK or by our clients.

## Contributing to Existing Projects

### Non-Code Contributions

This includes reporting issues, improving documentation, reviewing pull requests etc. You are encouraged to do any of these given that they relate to your regular work, e.g.

-   Reporting an issue you faced during you regular project work.
-   Improving the documentation of a function critical to your project.
-   Reviewing a pull request concerning a bug impacting your team or including a promising new feature.

### Code Contributions

Code contributions triggered by your regular work are highly encouraged, e.g.

-   Fixing a bug blocking your work.
-   Adding a feature required for your project.

Larger contributions on your own initiative during working hours need approval from your manager.

## Releasing a New Project

Releasing software as open source can have multiple benefits for you, your team and GfK as a whole:

-   We value the growth of our people, and therefore strongly encourage individuals to learn from their contributions to the open source community.
-   If the project solves problems relevant to others, you are likely to get support from the community in terms of bug reports and fixes, pull requests with interesting new features etc.
-   It will support GfK's employer branding as a tech company and help attract talent in technologies relevant to us.

### Get Buy-In From Management and Your Team

By making a decision to open source a project you are making a commitment to:
- Spend time preparing it for release
- Be efficient in responding to issues and pull requests that are submitted
- Be responsible for maintaining the project
- Be responsible for reacting to bug reports
- Be responsible for engaging directly with contributors
- Be responsible for upholding the standards and quality of contributions

Make sure you fully understand this commitment, and that your team and manager also understand how this will impact them.

### Prepare for Release

Open sourcing projects should be a frictionless process; we therefore will always strive to help our colleagues in whatever way we can.

As a starting point, any new project is strongly encouraged use the following asset repository as a skeleton:
- [GfK Asset Template Repository](https://github.com/gfkse/template)


Include the required assets with your code:
-   README.md with a high level overview/documentation.
-   MAINTAINERS.md with your contact information.
-   LICENSE stating the license, generally MIT with GfK SE as copyright holder.
-   CONTRIBUTING.md with information on how to contribute to the project.

Follow best practices for the type of software you are releasing.
*E.g R packages, do not need a MAINTAINERS.md since the relevant information is already stated in DESCRIPTION.*

-   All new projects must start from a clean commit history. Do not publish a new repository that contains history.
-   It is your responsiblity to make sure no confidential or secret information is published.
-   Ensure that the code is in a state which is useful to others:
    -   It does not depend on GfK-specific infrastructure.
    -   It is well documented.
    -   It is clear how to build/install/run.

### Ask for Review

Once you think you are ready to go, please reach out to the GfK Open Source CoP for a review.

### After Release

-   You put a lot of effort into open-sourcing your project. Now is the time to talk about it at conferences, appropriate mailing lists etc. Is there an official repo for your kind of software, e.g. PyPI, npm, or CRAN? Try to publish it there.
-   Be timely in responding to the community and contributors. This includes new issues, pull requests, feature requests etc., even if it is just communicating that you currently do not have time to look into it.
-   Actively create issues on your own if you long for help from the community.

## Credits
This document is greatly inspired by <https://opensource.zalando.com/docs>.