# Contributing

## How do I contribute?

There are two logical ways to contribute to the code and content usrse.github.io, including (but not limited to):

 - opening up an issue to ask a question, report a bug, or request a feature
 - working on a change to the website and opening up a pull request to discuss

This guide will help you to communicate with usrse (if needed) and guide you with
proper steps to make your contribution.

## Communication

Whether you are opening a pull request or an issue, you might want to communicate with
others in the community first. How can you do this? You can:

 - have discussion on the USRSE slack (usrse.slack.com) in the `#website` channel
 - open an issue at https://www.github.com/usrse/usrse.github.io
 - write an email to contact@us-rse.org (for more private questions)

It could be that you want to talk about a new feature or bug, and then follow up by opening
an issue at https://www.github.com/usrse/usrse.github.io/issues. It could also be
that you want to suggest and then work on a new feature, but you want to check first
that a pull request would be welcomed. Regardless of your need, the above channels
can offer you a means to do this.

### Teams

We have several teams on the repository that you can reference (@ "at") if you need help!

 - @usrse-admin: should be used for more important discussion that should involve administrators.
 - @usrse-maintainers: are referenced when a new pull request is open, and are primarily responsible for doing or assigning review.

## Making a Contribution

### Making Edits to the Website Repo
To make a contribution, you will need to edit the US RSE GitHub repo (https://github.com/USRSE/usrse.github.io).

Text, images, and other website assets go in different places. Here's a brief guide to a few key areas:
- The webpage text exist in markdown files (.md) in several places like `_events`, `_pages`, and `wg`. The best way to find the page you're trying to edit is to follow the path in the URL of the page itself. Example: editing the page for "https://us-rse.org/events/2022/2022-10-funder-talk-series/" would be in `_events` -> `2022` -> `2022-10-funder-talk-series.md`
- Small files like .png images go into `assets` -> `_img`
- Larger files like slides from a speaker series currently go into a read-only Google Drive. One exists for the speaker series [here](https://drive.google.com/drive/folders/1HiwQZgmXF30BSFDxEfQOfu68Hv4F4NwC?usp=share_link). 
  - You'll need to ask to add slides to that folder if you are not an editor.
  - Managers will need to change the permissions of files added there to be read-only and provide a share link that is accessible to anyone with the link to view.


### Pull Requests

When making a pull request contribution, it is important to properly communicate the
gist of the contribution. If it is a simple code or editorial fix, simply
explaining this within the GitHub Pull Request (PR) will suffice. But if this
is a larger fix or enhancement, it should be first discussed with the project
leader or developers. See the [communication channels](#communication) for ways
to do this.

#### Pull Request Process

The repository comes with a [pull request template](PULL_REQUEST_TEMPLATE.md) that provides you with a checklist and
helpful reminders for these points.

1. All pull requests should be sent to the main branch, unless you are testing an integration, in which case you should cc @usrse-admin in an issue, or ask for help on the website channel of usrse.slack.com.
2. Follow the existing code style precedent.
3. Test and preview your PR locally, and tell the reviewers if you were not able to
4. If necessary, update the README.md.
5. The pull request must receive at least one review and approval by a repository maintainer (for small fixes) and two for larger changes or changes to content for merge, along with all tests passing.


#### Issue Process

We encourage all community members to open issues on the GitHub [issues board](https://www.github.com/usrse/usrse.github.io/issues) whether you have a question, feature request, or bug report. In the case that you do not
have a GitHub account, you are welcome to communicate your issue via [other avenues](#communication)
and a maintainer will create a GitHub issue on your behalf.
