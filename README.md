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

### Contributor License Agreements

The following CLAs have been signed on GfK company level:

- Google CLA
- CNCF CLA

In order to contribute to projects covered by these CLAs on behalf of GfK we can add you to the group of _authorized contributors_. Please reach out to the [Open Source CoP](https://teams.microsoft.com/l/team/19%3a3750f2603cd245c69b72915c9f002335%40thread.tacv2/conversations?groupId=7bb77e08-5b4b-4e49-aca3-b594498deaf0&tenantId=60f3f635-a520-4eb7-a859-dbc5572fc839) (internal link).

## Releasing a New Project

Releasing software as open source can have multiple benefits for your team and GfK as a whole:

-   If the project solves problems relevant to others, you are likely to get support form the community in terms of bug reports and fixes, pull requests with interesting new features etc.
-   It will support GfK's employer branding as a tech company and help attract talent in technologies relevant to us.

### Get Buy-In From Management and Your Team

Releasing a new open source project requires time and effort, both for preparing for the release and then for maintaining the project, reacting to bug reports etc. Make sure this is understood by your team and your manager.

### Prepare for Release

-   Include the required assets with your code:
    -   README.md with a high level overview/documentation.
    -   MAINTAINERS.md with your contact information.
    -   LICENSE.md stating the license, generally MIT with GfK SE as copyright holder.
    -   CONTRIBUTING.md with information on how to contribute to the project, <https://github.com/gfkse/template/blob/master/CONTRIBUTING.md> should be a good starting point.
-   Follow the best practices w.r.t. the type of software you are releasing. For R packages, e.g., you do not need a MAINTAINERS.md since the relevant information is already stated in DESCRIPTION.
-   Again ensure that there is no confidential information contained in the code and the git history. It is probably safest to not push the git history but rather start a new repo from the current commit.
-   Ensure that the code is in a state which is useful to others:
    -   It does not depend on GfK-specific infrastructure.
    -   It is well documented.
    -   It is clear how to build/install/run.

### Ask for Review

Once you think you are ready to go, please reach out to the [Open Source CoP](https://teams.microsoft.com/l/team/19%3a3750f2603cd245c69b72915c9f002335%40thread.tacv2/conversations?groupId=7bb77e08-5b4b-4e49-aca3-b594498deaf0&tenantId=60f3f635-a520-4eb7-a859-dbc5572fc839) (internal link) for a review.

### After Release

-   You put a lot of effort into open-sourcing your project. Now is the time to talk about it on conferences, appropriate mailing lists etc. Is there an official repo for your kind of software, e.g. PyPI, npm, or CRAN? Try to publish it there.
-   Timely react to new issues, feature requests etc., even if it is just communicating that you currently do not have time to look into it.
-   Actively create issues on your own if you long for help from the community.

## Credits
This document is greatly inspired by <https://opensource.zalando.com/docs>.
