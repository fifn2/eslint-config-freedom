# Contributing to eslint-config-freedom

## Introduction

First off, thank you for considering contributing to eslint-config-freedom. It's people like you that make eslint-config-freedom such a great tool.

### Why should I even care about your CONTRIBUTING.md?

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

### What kinds of contributions are you looking for?

eslint-config-freedom is an open source project and we love to receive contributions from our community — you! There are many ways to contribute, from correcting typos or blog posts, improving the documentation, submitting bug reports and feature requests or writing code which can be incorporated into eslint-config-freedom itself.

### What kinds of contributions are you **not** looking for?

We're not looking for any kind of contribution that relates to opinionated code style. This eslint config was meant to shy away from that kind of thing.

## Ground Rules

### Responsibilities

- Ensure that all javascript code follows our styleguide (see styleguide section).
- Create issues for any major changes and enhancements that you wish to make.
- Try to use the functional programming paradigm over the object oriented or procedural paradigms.
- Remember to adhere to [SemVer](https://semver.org/) for versioning.
- Be welcoming to newcomers and encourage diverse new contributors from all backgrounds. See the [Code of Conduct](CODE_OF_CONDUCT.md).

## Your First Contribution

Help people who are new to your project understand where they can be most helpful. This is also a good time to let people know if you follow a label convention for flagging beginner issues.

Unsure where to begin contributing to eslint-config-freedom? You can start by looking through these beginner and help-wanted issues:

- Issues labeled "good first issue" - issues which should only require a few lines of code, and a test or two.
- Help wanted issues - issues which should be a bit more involved than beginner issues.

### First Time _Ever_?

**Working on your first Pull Request?** You can learn how from this _free_ series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

## Getting started

### Big Contributions

For something that is bigger than a one or two line fix:

1.  Create your own fork of the code
2.  Do the changes in your fork
3.  If you like the change and think the project could use it:
    - Be sure you have followed the code style for the project, and that the changes pass all tests.
    - Change the version number (refer to [SemVer](https://semver.org/))
    - Note the [Code of Conduct](CODE_OF_CONDUCT.md).
    - Send a pull request, and wait for it to be reviewed!

### Small Contributions

Small contributions are still very valuable to this project! However, even small contributions such as fixing spelling errors need to **increment the patch version number**.
As a rule of thumb, changes are obvious fixes if they do not introduce any new functionality or creative thinking. As long as the change does not affect functionality, some likely examples include the following:

- Spelling / grammar fixes
- Typo correction, white space and formatting changes
- Comment clean up
- Bug fixes that change default return values or error codes stored in constants
- Moving source files from one directory to another

# Styleguide

## Javascript

We use our own eslint-config-freedom for development, but we use [eslint-config-airbnb-base](https://www.npmjs.com/package/eslint-config-airbnb-base) for production and the refactoring part of the TDD cycle.
We do this by setting `process.env.NODE_ENV`, and travis makes sure that this is production when code is commited.

### Commit Messages

We use the [seven rules of good commit messages](https://chris.beams.io/posts/git-commit/#seven-rules).

## Where'd you get this excellent template?

Glad you asked! You can find it [here](https://github.com/nayafia/contributing-template/blob/master/CONTRIBUTING-template.md). It's a combination of a lot of different open source contributing guidlines.
