# Project ideas

> View [Wagtail projects on outreachy.org](https://www.outreachy.org/apply/project-selection/#wagtail)

- [Accessibility features documentation](#accessibility-features-documentation)
- [Adopt generic class based views across the Wagtail admin](#adopt-generic-class-based-views-across-the-wagtail-admin)
- [Wagtail.org website accessibility](#wagtail-org-website-accessibility)

## Accessibility features documentation

Quick links:

- [Questions? Discussions thread: Accessibility features documentation](https://github.com/wagtail/outreachy/discussions/)
- [Record your contributions: Accessibility features documentation](https://www.outreachy.org/outreachy-december-2023-internship-round/communities/wagtail/accessibility-features-documentation/contributions/)

[Wagtail](https://wagtail.org/) is a Content Management System (CMS) built upon the [Django](https://www.djangoproject.com/) web framework. Our CMS features a very polished administration interface with lots of content management features, which we’re very proud of. Unfortunately our "editor guide" documentation for users hasn’t kept up with our more recent overhauls of the CMS, and in particular is missing a lot of information about the _accessibility features_ in the CMS, which is in direct contradiction with our goal to follow the [ATAG 2.0](https://www.w3.org/TR/ATAG20/) standard.

We therefore need to update our documentation to cover the accessibility features in the CMS, and make sure we have a process to do so in the future.

### Primary goals

The **main goal** of the project will be to extend our [user guide documentation](https://guide.wagtail.org/en-latest/), which we’ve recently transferred onto a new site for ease of management. This would involve getting familiar with the CMS, liaising with our existing documentation authors, planning new content as well as rewrites of existing content. By the end of the project, we would want all of Wagtail’s accessibility features to be documented – in line with our goal to meet the ATAG standard.

### Secondary goals

Depending on the candidate’s interests and skillset, we’re also interested in considering one or multiple **secondary goals**:

- Introduce documentation _directly in the CMS_ ("onboarding tour guide", or help text, or “More info” pop-ups), rather than only as a separate site
- Produce video content for documentation purposes. This could be either guided tutorials / how-to guide, or high-level "video tours" of accessibility features.
- Improve our process for keeping documentation up to date, by making changes to the website or introducing more advanced tooling. This could for example involve automated screenshot taking, or CMS features to mark content as needing rework.

### Stretch goals

A clear stretch goal would be to document CMS features that aren’t related to accessibility, which is also a requirement of the [ATAG 2.0](https://www.w3.org/TR/ATAG20/) standard.

### Skills

- Written English language: the contributor should be comfortable writing in idiomatic English (we follow the [Google developer documentation style guide](https://developers.google.com/style))
- Writing technical documentation: some experience required
- Accessibility: some experience required, and an interest to learn more

### System requirements

The contributor will need a microphone to join online meetings. There are no other requirements – if the contributor is interested in doing a bit of coding, they can either do this on their own computer or we will set up a cloud coding environment.

### Application tasks

- See our [contributor guide](contributor-guide.md) for how to get started with Outreachy.
- Go through all tasks defined in the relevant checklists.
- Prepare your application (exact tasks / template TBD)

### Mentors

We will have multiple mentors on this project – please use our [preferred communication channels](contributor-guide.md#communication-channels) where possible.

- Lead mentor: Damilola Oladele, [@activus-d](https://github.com/activus-d)
- Support mentor: Thibaud Colas, [@thibaudcolas](https://github.com/thibaudcolas)
- Support mentor: TBC
- Backup mentor: TBC

### Contributor teams

This project will involve coordinating with the following community teams / efforts:

- [Accessibility team](https://github.com/wagtail/wagtail/wiki/Wagtail-sub-teams#accessibility)
- [Documentation team](https://github.com/wagtail/wagtail/wiki/Wagtail-sub-teams#documentation)
- Editor guide contributors in #editor-guide on Slack

### Intern benefits

This project is an opportunity to make an impactful contribution for users of Wagtail, a lot of which are in the public sector / non-profit "tech for good" space. You will get to work with people who are passionate about documentation and accessibility, and get a behind-the-scenes look at how open source products get built.

The contributor will work with existing documentation contributors, and given very concrete opportunities to showcase their work in community events (DjangoCon, Wagtail Space conferences).

### Community benefits

We’ve been doing a lot of work on our documentation lately, and want to showcase it very prominently to our users, but could really use the help to make the content shine. Upon implementation, this documentation will be accessible within thousands of sites built with Wagtail. We also hope this work will help us set a standard for how to manage documentation upkeep in the future, as we expect Wagtail to further grow, and we’d love our newest features to be equally well documented as what will be produced with this project.

### Intern tasks

After getting to know Wagtail, the candidate will:

- Join the teams currently looking after our user guide documentation and our accessibility team.
- Get up to speed with the current content of the site, including known gaps for accessibility features
- Spend time with Wagtail to identify other gaps
- Produce a new content outline to complete by the end of the project, focusing on adding documentation for all accessibility features in the CMS.
- Write content for the parts of the outline we’ve earmarked collaboratively

Once the desired outline is complete, we can consider some of our secondary goals.

### Project resources

- [Wagtail roadmap: Admin accessibility audit](https://github.com/wagtail/roadmap/issues/46)
- [Wagtail issue: ATAG audit](https://github.com/wagtail/wagtail/issues/10515)
- [Editor Guide: About](https://guide.wagtail.org/en-latest/about/)

---

## Adopt generic class based views across the Wagtail admin

Quick links:

- [Questions? Discussions thread: Adopt generic class based views across the Wagtail admin](https://github.com/wagtail/outreachy/discussions/)
- [Record your contributions: Adopt generic class based views across the Wagtail admin](https://www.outreachy.org/outreachy-december-2023-internship-round/communities/wagtail/adopt-generic-class-based-views-across-the-wagtail-admin/contributions/)

The Wagtail admin consists of a mix of Django's function-based views and class-based views. In recent releases, we have been adding generic class-based views within Wagtail, which lets us reuse similar code for various views in the admin. For consistency and maintainability purposes, we have been migrating some of the function-based views into class-based views that extend the generic views. There are still plenty of views in the Wagtail admin that are yet to migrated to use the generic views. This project aims to refactor those views so that we can reduce code duplication and enforce consistency across the admin.

This project requires an intermediate level of understanding in Django, in particular the class-based views and the Django Template Language. Potential applicants are advised to demonstrate their skills in these particular areas before selecting this project idea.

### Skills

- Django: experimented

### System requirements

- Linux, macOS, or Windows computer with at least 2GB of RAM needed to run the site – in addition to RAM needed for other applications (web browser, code editor).
- Microphone to join online meetings

### Application tasks

- See our [contributor guide](contributor-guide.md) for how to get started with Outreachy.
- Go through all tasks defined in the relevant checklists.
- Prepare your application (exact tasks / template TBD)

### Mentors

We will have multiple mentors on this project – please use our [preferred communication channels](contributor-guide.md#communication-channels) where possible.

- Lead mentor: Sage Abdullah, [@laymonage](https://github.com/laymonage)
- Support mentor: TBC
- Support mentor: TBC
- Backup mentor: TBC

### Contributor teams

This project will involve coordinating with the following community teams / efforts:

- [Core team](https://github.com/wagtail/wagtail/wiki/Wagtail-core-team)
- UI contributors in #ui on Slack
- Code contributors in #development on Slack

### Intern tasks

Look at this issue for more details: [☂️ Adopt generic class based views across all areas of admin (epic) #8365](https://github.com/wagtail/wagtail/issues/8365)

### Project resources

- [☂️ Adopt generic class based views across all areas of admin (epic) #8365](https://github.com/wagtail/wagtail/issues/8365)

---

## Wagtail.org website accessibility

Quick links:

- [Questions? Discussions thread: Wagtail.org website accessibility](https://github.com/wagtail/outreachy/discussions/)
- [Record your contributions: Wagtail.org website accessibility](https://www.outreachy.org/outreachy-december-2023-internship-round/communities/wagtail/wagtailorg-accessibility/contributions/)

[Wagtail](https://wagtail.org/) is a Content Management System (CMS) built upon the [Django](https://www.djangoproject.com/) web framework. We want sites built with Wagtail to be as accessible as possible (see our [accessibility statement](https://wagtail.org/accessibility/)). As part of this internship, we want to improve our [wagtail.org](https://wagtail.org/) website to become a reference implementation of accessibility best practices in the Wagtail ecosystem.

### Primary goals

The project has two primary goals, which can be adjusted depending on the profile of the successful applicant:

- **Produce an accessibility audit** – reviewing in detail how different aspects of wagtail.org perform against established accessibility standards and best practices.
- **Implement accessibility improvements** – making changes to the site’s design and code to address the accessibility issues and possible improvements raised in the audit.

### Secondary goals

Our secondary goals are:

- **Exploring accessibility best practices** –trialling how different established practices fare when applied on a Wagtail project. For example around alt text, or how to configure Wagtail’s accessibility checker.
- **Sharing best practices with the community** – for example via blog posts, an audit methodology, or demonstrating common testing techniques.

### Stretch goals

Depending on the candidate’s interest and time available:

- **Auditing other sites** – the Wagtail ecosystem has a lot of other sites which would benefit from additional scrutiny.
- Adding **automated tests** – so rather than one-off checks, a page’s test results could be tracked over time, across the whole site.
- Adding **features in Wagtail** – based on the findings from the audit and the implementation, refining how the CMS works.

### Skills

- Accessibility: some experience required, and an interest to learn more
- Django: either previous experience with Django required, or previous experience with a similar framework, or with underlying web technologies (HTML, CSS)

### System requirements

- Linux, macOS, or Windows computer with at least 2GB of RAM needed to run the site – in addition to RAM needed for other applications (web browser, code editor).
- Microphone to join online meetings

### Application tasks

- See our [contributor guide](contributor-guide.md) for how to get started with Outreachy.
- Go through all tasks defined in the relevant checklists.
- Prepare your application (exact tasks / template TBD)

### Mentors

We will have multiple mentors on this project – please use our [preferred communication channels](contributor-guide.md#communication-channels) where possible.

- Lead mentor: Albina Starykova, [@albinazs](https://github.com/albinazs)
- Support mentor: Ben Morse, [@Morsey187](https://github.com/Morsey187)
- Support mentor: TBC
- Backup mentor: Thibaud Colas, [@thibaudcolas](https://github.com/thibaudcolas)

### Contributor teams

This project will involve coordinating with the following community teams / efforts:

- [Accessibility team](https://github.com/wagtail/wagtail/wiki/Wagtail-sub-teams#accessibility)
- [Developer relations team](https://github.com/wagtail/wagtail/wiki/Wagtail-sub-teams#developer-relations)
- Wagtail.org site contributors in #wagtail-org on Slack

### Intern benefits

There is a lot of room for improvement in Web Accessibility, and this project is an opportunity to make a real-world impact for organisations using Wagtail. Very few open source projects do the type of testing and improvements we will go through, so once done this work will be very visible within the CMS and accessibility space.

The contributor will also more generally learn a lot about web development, and product development in open source communities. They will be embedded within our accessibility team, and given very concrete opportunities to showcase their work in community events (DjangoCon, Wagtail Space conferences), and work with prominent organisations within our community.

### Community benefits

For Wagtail, this will be a very big improvement to the accessibility of our main site, which is critical to our community. This will take us further towards reaching our accessibility goals (<https://wagtail.org/accessibility>), and doing so via an Outreachy internship will ensure this work gets great visibility within our community and beyond.

### Intern tasks

Please refer to the goals described above.

### Project resources

- [Wagtail’s accessibility statement](https://wagtail.org/accessibility/)
- [Wagtail docs for site implementers: Accessibility considerations](https://docs.wagtail.org/en/stable/advanced_topics/accessibility_considerations.html)
- [Wagtail issue: ATAG audit](https://github.com/wagtail/wagtail/issues/10515)

## Template

For future use, the above as a template.

```markdown
## Template

Quick links:

- [Questions? Discussions thread: ](https://github.com/wagtail/outreachy/discussions/)
- [Record your contributions: ]()

<!-- Description here -->

### Primary goals

### Secondary goals

### Stretch goals

### Skills

### System requirements

### Application tasks

- See our [contributor guide](contributor-guide.md) for how to get started with Outreachy.
- Go through all tasks defined in the relevant checklists.
- Prepare your application (exact tasks / template TBD)

### Mentors

We will have multiple mentors on this project – please use our [preferred communication channels](contributor-guide.md#communication-channels) where possible.

- Lead mentor: TBC
- Support mentor: TBC
- Support mentor: TBC
- Backup mentor: TBC

### Contributor teams

This project will involve coordinating with the following community teams / efforts:

### Intern benefits

### Community benefits

### Intern tasks

### Project resources
```
