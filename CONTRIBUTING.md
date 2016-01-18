# Contributing guidelines

There are many different ways in which you can contribute. One of them is simply by using our software and providing us with your feedback or you can actively participate by coding some new features.

This guide describes general guidelines that most of the repositories refer to. We don't want to make things complicated so we try to follow the same rules in every repository. But sometimes there are some rules specific for that particular repository. Always check the contributing guideline and readme in that repository as well.


## I have an idea for a new feature

Everybody loves new features! You can create a new issue or you can code it on your own and provide us with the pull request. Anyway, don't forget to mention what's the use case and what's the expected output.

You can also discuss the feature before you start the implementation. Ask us on a repository [Gitter](https://gitter.im/Kentico) chat or create a GitHub issue.


## I found a bug

Sorry to hear that. Just create new GitHub issue and someone will take a look at that. Please, don't forget to provide us with all the important information like

- Steps to reproduce the issue
- Environment and software version used
- Screenshot
- Error message
- What is the expected behavior

The more information you provide, the easier would it be to fix the issue. You can also fix the bug on your own and submit a new pull request.


## Submitting pull requests

If not stated otherwise, we use [feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow). To start with coding, fork the repository you want to contribute to, create a new branch and start coding.


### Example - process of contribution

1. ```Tom``` forks this repository
2. Creates a new branch for his ```cool``` feature
3. Hacks his code
4. Writes some tests
5. Once he's happy with the changes, he submits a pull request from his ```cool``` branch to ```master``` branch
6. We discuss the pull request with ```Tom``` and maybe suggest some adjustments
7. Once the code is ready, someone from maintainers will merge it into the ```master``` branch


### Code requirements

- Code is buildable
- All tests are green
- Code design follows the .NET [Framework Design Guidelines](https://msdn.microsoft.com/en-us/library/ms229042.aspx)
    - If you're not sure about some rules, follow the style of the existing code.
    - Use "Format the whole document" button in Visual Studio to fix indentation ![format](https://cloud.githubusercontent.com/assets/9810625/12391368/a14d7726-bde7-11e5-9a0f-3310c833f5ca.png)
- Documentation is updated
  


### Learn how to write good commit messages

We hate sloppy commit messages. No more ```Performance tuning``` or ```Changed a few files```. Please read the following articles to understand what a good commit message is.

- [Writing good commit messages](https://github.com/erlang/otp/wiki/Writing-good-commit-messages)
- [A Note About Git Commit Messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
- [On commit messages](http://who-t.blogspot.com/2009/12/on-commit-messages.html)
