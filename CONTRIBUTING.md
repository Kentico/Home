# Ways to contribute

There are many different ways in which you can contribute. One of the easiest ways is simply to use our software and provide us with your feedback through the right channel. You can also help us improve the open-source projects by submitting pull requests with code and documentation changes.

## Where to get support

Please note that the **level of provided support is always determined by the [SUPPORT](SUPPORT.md)** of a given open-source project. Also, always make sure you use the **[latest version](../../releases)** of any given OS project. We can't provide any help for older versions. We don't want to make things complicated so we try to take the same approach in all our repositories.

### I found a bug in a Kentico's open-source project

Sorry to hear that. Just log a new [GitHub issue](../../issues) and someone will take a look at it. Remember, the more information you provide, the easier it will be to fix the issue. If you feel like it, you can also fix the bug on your own and submit a new pull request.

### I need help with using the projects and/or coding

Take a look at our [Resources](./RESOURCES.md) and look for help in our developer community.

### I want to report a security bug

Please review our [Security](./SECURITY.md) guidance.

### I have an idea for a new feature (or feedback on existing functionality)

Everybody loves new features! You can submit a new [feature request](../../issues) or you can code it on your own and [send us a pull request](#submitting-pull-requests). In either case, don't forget to mention what's the use case and what's the expected output.

## Submitting pull requests

Unless you're fixing a typo, it's usually a good idea to discuss the feature before you submit a pull request with code changes, so let's start with submitting a new [GitHub issue](https://docs.github.com/en/github/managing-your-work-on-github/creating-an-issue) and discussing the whether it fits the vision of a given project.
You might also read these two blogs posts on contributing code: [Open Source Contribution Etiquette](http://tirania.org/blog/archive/2010/Dec-31.html) by Miguel de Icaza and [Don't "Push" Your Pull Requests](https://www.igvita.com/2011/12/19/dont-push-your-pull-requests/) by Ilya Grigorik. Note that all code submissions will be rigorously reviewed and tested by the Kentico Maintainers teams, and only those that meet an high bar for both quality and design/roadmap appropriateness will be merged into the source.

### Example - process of contribution

If not stated otherwise, we use [feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).

To start with coding, fork the repository you want to contribute to, create a new branch, and start coding. Once the functionality is [done](#definition-of-done), you can submit a [pull request](https://help.github.com/articles/about-pull-requests/).

### Definition of Done

- New/fixed code is covered with tests
- CI can build the code
- All tests are passing
- Coding style (spaces, indentation) is in line with the rest of the code in a given repository
- Documentation is updated (e.g. code examples in README, Wiki pages, etc.)
- All `public` members are documented (using XML doc, etc.)
- Code doesn't contain any secrets (private keys, etc.)
- Commit messages are clear. Please read these articles: [Writing good commit messages](https://github.com/erlang/otp/wiki/Writing-good-commit-messages), [A Note About Git Commit Messages](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html), [On commit messages](https://who-t.blogspot.com/2009/12/on-commit-messages.html)

Note: You do not need to update the project version numbers. Semantic version number updates for the project will be managed by the project maintainers.

### Feedback

Your pull request will now go through extensive checks by the subject matter experts on our team. Please be patient. Update your pull request according to feedback until it is approved by one of the Kentico maintainers. After that, one of our team members may adjust the branch you merge into based on the expected release schedule.

## Code of Conduct

The Kentico team is committed to fostering a welcoming community, therefore this project has adopted the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). If you have any additional questions or comments, you can contact us directly at <https://community.kentico.com/support>.
