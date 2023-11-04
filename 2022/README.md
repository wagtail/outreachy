## Table of Contents

* [Resources](#resources)
* [About Wagtail](#about-wagtail)
* [Contributors](#contributors)
  * [Contributor initial checklist](#contributor-initial-checklist)
  * [Documentation contributors checklist](#documentation-contributors-checklist)
  * [Accessibility project checklist](#accessibility-project-checklist)
  * [Stimulus project checklist](#stimulus-project-checklist)
* [Improve your chances of being accepted](#improve-your-chances-of-being-accepted)
* [Your first contribution](#your-first-contribution)
* [Projects](#projects)
  * [Develop tools to help Wagtail editors create accessible content](#develop-tools-to-help-wagtail-editors-create-accessible-content)
  * [Improve user guide documentation for Wagtail](#improve-user-guide-documentation-for-wagtail)
  * [Introduce Stimulus for interactive widgets within Wagtail](#introduce-stimulus-for-interactive-widgets-within-wagtail)
* [Coordinators and mentors](#coordinators-and-mentors)
  * [Organisation coordinators](#organisation-coordinators)
  * [Mentors](#mentors)
* [Frequently asked questions](#frequently-asked-questions)

## Resources

* [outreachy.org](https://www.outreachy.org/)
* [#outreachy channel on Slack, for any questions](https://github.com/wagtail/wagtail/wiki/Slack)
* [Wagtail documentation](http://docs.wagtail.org/)
* [Wagtail blog](https://wagtail.org/blog/)
* [Video: Contributing to Open Source for the first time](https://youtu.be/c6b6B9oN4Vg)

## About Wagtail

Wagtail is a popular content management system. It's built on Python, by an active and engaged open source community, which has grown rapidly since Wagtail's release in 2014. Wagtail is available in over 40 languages, and used by some of the world's best-known organizations, including NASA, Google, Mozilla, MIT, and the UK's National Health Service, as well as museums, universities, non-profits, governments, banks, studios, restaurants, startups and bloggers around the world.

Like Python and Django, the technologies which underpin it, Wagtail is known for its welcoming community. We're keen to increase the geographic and cultural diversity of our core team, who are currently spread across Europe, Africa and North America. We seek to offer friendly support on Slack, StackOverflow and Github, and we encourage the community to meet in real life where possible, with recent sprints and conferences held in South Africa, Iceland, the USA, Belarus and the UK.

Wagtail has moved fast in the last few years, with particular focus on the editor experience, the refinement of APIs for headless CMS architectures and accessibility. We have adopted a regular quarterly release cycle, which aims to minimise upgrade time while providing compelling new features and improvements with each point releases. We're seeking help to deliver some of our more ambitious plans, many of which are expressed as [RFCs]. We're also open to your ideas for making Wagtail the best open source CMS for the 2020s!

## Contributors

We expect participants to go through a few initial tasks as part of the Outreachy contribution period, ahead of their final application. This is for you to get to know Wagtail as a project and community, and get a sense of how we can work together. It also helps mentors assess the skills of candidates, so we can decide which projects we can take on with you.

Based on your preferred project idea(s), go through the relevant tasks lists below.

### Contributor initial checklist

For **all** projects – participants to Outreachy should:

1. [ ] Have a good understanding of how Outreachy works.
2. [ ] Join the [Wagtail Slack](https://github.com/wagtail/wagtail/wiki/Slack) and introduce yourself on the #new-contributors channel. Let us know a bit about you (what you’re comfortable with!), skills you have and skills you want to practice, which projects you’re interested in.
3. [ ] Update your profile image in Slack to be something other than the default image (can be a photo of you or any image you like).
4. [ ] Invest time to discover what project(s) you like.
5. [ ] Ask questions about the project(s) you are interested in.
6. [ ] Get to know the Wagtail community.
7. [ ] Join GitHub, if you have not already, ensure you have an image on your profile and your preferred public name set.
8. [ ] Make small contributions to Wagtail already. Show that you understand how open-source projects work. This can be all sorts of different kinds of tasks – helping orient people on Slack, identifying problems with Wagtail, our documentation. Making changes to the code, documentation, translation, etc.
9. [ ] Attend one of our Outreachy Q&A sessions (more details to come)

### Documentation contributors checklist

For people interested in contributing to project 2 _"Improve user guide documentation for Wagtail"_, we expect you to go through the following initial tasks as part of getting up to speed with Wagtail as a community:

- [ ] Use [Wagtail Gitpod](https://wagtail.org/blog/gitpod/) to go through the [Wagtail tutorial](https://docs.wagtail.org/en/latest/getting_started/tutorial.html). Use the "Open in browser" feature, _not_ "Open in VS Code". Let us know if you encounter blockers.
- [ ] Use Gitpod again, this time to [set up our fully-fledged bakerydemo website](https://github.com/wagtail/bakerydemo#setup-with-gitpod). This will allow you to test more Wagtail features
- [ ] Read through some of our [documentation for developers](https://docs.wagtail.org/en/stable/) and [documentation for users](https://docs.wagtail.org/en/stable/editor_manual/index.html), to get a sense of our voice and tone, and writing style.
- [ ] Read about [Diátaxis](https://diataxis.fr/), the documentation structure we use for Wagtail.
- [ ] Write a **short blog post** describing your Outreachy involvement so far, and share it with us. The post must be in English, include at least one image, be less than 500 words, and score a Grade 4 or lower on <https://hemingwayapp.com/>. It can be a public post on your own blog or a blogging site, or a Google Docs document you share with us (make sure commenting is enabled). You can talk about anything Outreachy – things you’re doing with Wagtail but also before, or any other Outreachy community you’re also trying to work with. To share the post, DM Thibaud Colas on Slack or @-mention [@thibaud_colas](https://twitter.com/thibaud_colas) on Twitter.
- [ ] Review our [new user guide website](https://wagtail.org/editor-guide-site) and its contents, and provide feedback proposing specific improvements in the [Outreachy: Improve user guide documentation for Wagtail](https://github.com/wagtail/guide/discussions/116) discussion thread. Those can be improvements to the existing content, or addition of new content you think is missing based on trying out Wagtail. You may also suggest features that would make the site nicer to use, or make the documentation more accessible to users.
- [ ] Using your local copy of Wagtail, or [gitpod-wagtail-develop](https://github.com/wagtail/gitpod-wagtail-develop), or the GitHub editing interface, make contributions to the existing documentation in the [`docs/` folder]. For Gitpod users – use the "Open in browser" feature, _not_ "Open in VS Code".(https://github.com/wagtail/wagtail/tree/main/docs) of our project. See a list of [issues tagged "Documentation"](https://github.com/wagtail/wagtail/issues?q=is%3Aopen+label%3ADocumentation+sort%3Aupdated-desc).

### Accessibility project checklist

For people interested in contributing to projects 1 _"Develop tools to help Wagtail editors create accessible content"_, we expect you to go through the following tasks:

- [ ] Confirm you have a basic familiarity with Git and GitHub.
- [ ] Go through the [Wagtail tutorial](https://docs.wagtail.org/en/latest/getting_started/tutorial.html) on your own computer (no Gitpod). Let us know if you encounter blockers.
- [ ] Create a [development environment](https://docs.wagtail.org/en/latest/contributing/developing.html) for working on Wagtail. Again, without Gitpod. There are good instructions in our [official documentation](https://docs.wagtail.org/en/latest/contributing/index.html).
- [ ] Make at least one bug fix or feature enhancement to Wagtail as a pull request, excluding documentation changes, following our documentation for contributors.
- [ ] Go through the [Sa11y documentation](https://sa11y.netlify.app/)
- [ ] Read the [ATAG standard](https://www.w3.org/TR/ATAG20/), which we are trying to meet as part of this project

### Stimulus project checklist

For people interested in contributing to project 3 _"Introduce Stimulus for interactive widgets within Wagtail"_, we expect you to go through the following tasks:

- [ ] Confirm you have a basic familiarity with Git and GitHub.
- [ ] Go through the [Wagtail tutorial](https://docs.wagtail.org/en/latest/getting_started/tutorial.html) on your own computer (no Gitpod). Let us know if you encounter blockers.
- [ ] Create a [development environment](https://docs.wagtail.org/en/latest/contributing/developing.html) for working on Wagtail. Again, without Gitpod. There are good instructions in our [official documentation](https://docs.wagtail.org/en/latest/contributing/index.html).
- [ ] Make at least one bug fix or feature enhancement to Wagtail as a pull request, excluding documentation changes, following our documentation for contributors.
- [ ] Go through the [Stimulus handbook](https://stimulus.hotwired.dev/handbook/origin)
- [ ] Read our [Stimulus RFC (Request For Comments)](https://github.com/wagtail/rfcs/blob/rfc/stimulus/text/078-adopt-stimulus-js.md)

Here are additional resources which you may find helpful to better understand this project:

- https://github.com/hotwired/stimulus-starter
- https://dev.to/lb/creating-an-interactive-event-budgeting-tool-within-wagtail-53b3
- https://dev.to/lb/creating-a-schematic-editor-within-the-wagtail-cms-with-stimulusjs-n5j

## Improve your chances of being accepted

The best thing you can do to improve your chances of being accepted as an Outreachy contributor with Wagtail is to start contributing now. Make yourself known to the community for your contributions. Do general contributions, and try to contribute to an area related to your proposal. When the time comes to evaluate applications, you will be a known individual.

We're looking for candidates who can demonstrate that they can engage in the Wagtail project. We're here to help, but we can't watch you every step of the way. We need to see motivation from you. Your activities before the submissions process are the best way to demonstrate this.

## Your first contribution

- [ ] I have read and been through the [contributor checklist](#contributor-initial-checklist)
- [ ] I have identified a good first task, either on my own, or one of the [good first issues](https://github.com/wagtail/wagtail/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22good+first+issue%22), or one tagged [Outreachy](https://github.com/wagtail/wagtail/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3AOutreachy), or looking at [5 simple ways anyone can contribute to Wagtail](https://wagtail.org/blog/5-simple-ways-anyone-can-contribute-to-wagtail/)
- [ ] For GitHub issues – no one else is working on the issue I selected, so I’ve added a comment stating I’m working on it.
- [ ] I have read [Ten tasty ingredients for a delicious pull request](https://wagtail.org/blog/ten-tasty-ingredients-for-a-delicious-pull-request/)
- [ ] I have opened a pull request following those guidelines, mentioning my involvement with Outreachy, the name I want to be credited with in the release notes, and describing my changes (following the template provided by Wagtail)
- [ ] 🙌 Nice one! Share your pull request in our #outreachy channel on Slack so we can celebrate

## Projects

See our initial announcement: [Outreachy: welcoming new contributors to open source](https://wagtail.org/blog/outreachy-welcoming-new-contributors-to-open-source/), and our internships: [Our very first Outreachy Interns](https://wagtail.org/blog/our-very-first-outreachy-interns/).

### Develop tools to help Wagtail editors create accessible content

- Contributor: Albina Starikova [@albinazs](https://github.com/albinazs), Twitter: [@albinastarykova](https://twitter.com/albinastarykova)
- Mentors: Sage Abdullah, Joshua Munn, Thibaud Colas
- [outreachy.org link](https://www.outreachy.org/outreachy-december-2022-internship-round/communities/wagtail/#create-an-accessibility-checker-for-wagtail)
- Project updates: [Built-in accessibility checker for Wagtail #9262](https://github.com/wagtail/wagtail/discussions/9262)
- GitHub team: [`@wagtail/outreachy-accessibility`](https://github.com/orgs/wagtail/teams/outreachy-accessibility)
- GitHub Projects board: [Outreachy: Accessibility checker](https://github.com/orgs/wagtail/projects/19/views/1)

### Improve user guide documentation for Wagtail

- Contributor: Damilola Oladele [@activus-d](https://github.com/activus-d), Twitter: [@activus_d](https://twitter.com/activus_d)
- Mentors: Stephanie Brown, Jonny Peacock, Storm Heg, Thibaud Colas, Coen van der Kamp
- [outreachy.org link](https://www.outreachy.org/outreachy-december-2022-internship-round/communities/wagtail/#improve-user-guide-documentation-for-wagtail)
- Project updates: [Outreachy: Editor Guide internship updates](https://github.com/wagtail/guide/discussions/282)
- GitHub team: [`@wagtail/outreachy-guide`](https://github.com/orgs/wagtail/teams/outreachy-guide)
- GitHub Projects board: [Outreachy: Editor Guide](https://github.com/orgs/wagtail/projects/21/views/1)

### Introduce Stimulus for interactive widgets within Wagtail

- Contributor: Loveth Omokaro [@Lovelyfin00](https://github.com/Lovelyfin00), Twitter: [@lovelyfin00](https://twitter.com/lovelyfin00)
- Mentors: LB, Thibaud Colas, Paarth Agarwal
- [outreachy.org link](https://www.outreachy.org/outreachy-december-2022-internship-round/communities/wagtail/#introduce-stimulus-for-interactive-widgets-within-)
- GitHub team: [`@wagtail/outreachy-stimulus`](https://github.com/orgs/wagtail/teams/outreachy-stimulus)
- GitHub Projects board: [Outreachy: Stimulus (RFC 78)](https://github.com/orgs/wagtail/projects/14/views/1)

## Coordinators and mentors

Our Outreachy participation is made possible thanks to our contributors volunteering to coordinate and mentor the projects.

### Organisation coordinators

Our coordinators oversee our involvement with the program, coordinating mentors and contributors. They are the point of contact for Outreachy. Our coordinators are:

- Thibaud Colas. To contact Thibaud, direct message them on [Slack](https://github.com/wagtail/wagtail/wiki/Slack) @Thibaud.
- Meagen Voss. To contact Meagen, direct message them on [Slack](https://github.com/wagtail/wagtail/wiki/Slack) @Meagen Voss.

### Mentors

Our mentors look after the contributors during the internship.

- Sage Abdullah [@laymonage](https://github.com/laymonage), Twitter: [@laymonage](https://twitter.com/laymonage)
- Joshua Munn [@jams2](https://github.com/jams2)
- Thibaud Colas [@thibaudcolas](https://github.com/thibaudcolas), Twitter: [@thibaud_colas](https://twitter.com/thibaud_colas), Mastodon: N/A
- Stephanie Brown
- Jonny Peacock [@ jonnypeaks](https://github.com/jonnypeaks)
- Storm Heg [@Stormheg](https://github.com/Stormheg), Twitter: [@Stormheg](https://twitter.com/stormheg)
- Coen van der Kamp [@allcaps](https://github.com/allcaps), Twitter: [@allcaps](https://twitter.com/allcaps)
- LB [@lb-](https://github.com/lb-), Twitter: [@\_lb\_](https://twitter.com/_lb_)
- Paarth Agarwal [@PaarthAgarwal](https://github.com/PaarthAgarwal), Twitter: [@AgarwalPaarth](https://twitter.com/AgarwalPaarth)

## Making a successful final application

Follow [our application template](https://docs.google.com/document/d/1BgzSB4XJR4nzPAAdEEpVPhV0f7ojKRda0O_togLcfBY/edit#) to share your draft with mentors.

- Always, always, always submit what you wrote on the Outreachy site, not just our Google Docs. The docs are just there for mentors’ reviews. The Outreachy site is the source of truth. Make sure what you add there is up-to-date and spotless.
- If you send a document in Google Docs back to us to get reviews – make sure the doc’s sharing settings allows us to view the contents and comments!

### Community questions

#### In your own words, what problem is the project attempting to solve? 50 words max

#### In your own words, what is the main goal of the project? 50 words max 

#### In your own words, what are the benefits that this project will bring to Wagtail’s users and community? 50 words max

#### Why are you interested in this specific project? 100 words max 

### Project timeline

Drafting a project timeline is a *hard* task! It requires a good understanding of the project, of the proposed tasks we shared, of the time all of this might take… even for regular contributors, it’s a tough ordeal.

Here are the steps I’d recommend if you don’t know where to start:

1. Start with a list of tasks in sequential order
2. Populate this list with the high-level tasks we shared in each project’s description on the Outreachy site
3. For each of those, try to break down the task into 3-5 sub-tasks
4. Estimate how much time the tasks might take (1, 3, 5 days)
5. For those new sub-tasks that you estimated for more than 1-2 days, try to break them down into more tasks if possible. Repeat as much as you want!
6. Think of when you’ll need a review from others (our contributors, our core team, the mentors). Add getting those reviews, and addressing feedback from those reviews, as tasks
7. Think of other forms of quality assurance / testing you could do. Add those as tasks.
8. Add tasks for any preliminary research you might need to do in order to achieve some of the tasks

Once you’ve done this – add / revise your estimates. Then based on your estimates, you can split the tasks week by week! Make sure to leave some room for blog posts, meetings, and just generally plan conservatively

## Frequently asked questions

### Contributing

#### Is it okay for me to work on a task someone else has already claimed?

No. We want contributors to be able to take their time when they pick a task, and not feel stressed that someone else might decide to tackle the same issue.

#### If I’m unable to complete a task on time and someone else shows interest in it, will it be assigned to the person?

No. You can keep working on an issue as long as you want and we’ll keep it assigned to you. Though if you’re unable to complete a task you might prefer to work on something else.

#### I’m not as active as other participants. Do I have a chance?

We’re looking for candidates who can demonstrate their ability to engage with our community and contribute to their project, but quality beats quantity. Ask thoughtful questions, make realistic project plans, and go through a few meaningful contributions. That’s all we need.

#### Can we write the blog post with an informal tone?

Yes! This is your blog post, any tone you’re comfortable writing in is good.
