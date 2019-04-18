# Contribution Guide
Contribution guide specifies the way and standards regarding contributions to all orbs-network projects.

## [Code of Conduct](./CODE_OF_CONDUCT.md)
We have adopted a Code of Conduct that we expect project participants to adhere to. Please read the full text so that you can understand what actions will and will not be tolerated.

## Open Development
All work on Orb network happens directly on [GitHub](https://github.com/orbs-network). 
Both core team members and external contributors send pull requests which go through the same review process.

## Engineering Standards
We value high quality code standards. Which is why the written code MUST be tested. It can be done using different types of tests, preferably in the [test-driven (TDD)](https://en.wikipedia.org/wiki/Test-driven_development) manner.

## Branching Procedure
We will do our best to keep the master branch in good shape, with tests passing at all times. 
If you send a pull request, please do it against the master branch. 

## Bugs
### Where to Find Known Issues
We are using GitHub Issues for our public bugs. We keep a close eye on this and try to make it clear when we have an internal fix in progress. 
Before filing a new task, make sure your problem doesn’t already exist.

### Reporting New Issues
The best way to get your bug fixed is to provide a reduced test case. In other cases, make sure to describe step-by-step instructions of how to reproduce an issue.

## How to Get in Touch
Community discussions: [community.orbs.network](https://comunity.orbs.network)

## Proposing a Change
If you intend to change the public API, or make any non-trivial changes to the implementation, we recommend filing an issue. This lets us reach an agreement on your proposal before you put significant effort into it.
If you’re only fixing a bug, it’s fine to submit a pull request right away but we still recommend to file an issue detailing what you’re fixing. This is helpful in case we don’t accept that specific fix but want to keep track of the issue.

### Your First Pull Request
Working on your first Pull Request? 

You can learn how from this free video series:
[How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

If you decide to fix an issue, please be sure to check the comment thread in case somebody is already working on a fix. If nobody is working on it at the moment, please leave a comment stating that you intend to work on it so other people don’t accidentally duplicate your effort.
If somebody claims an issue but doesn’t follow up for more than two weeks, it’s fine to take it over but you should still leave a comment.

### Sending a Pull Request   
The core contributors are monitoring for pull requests. They will review your pull request and either merge it, request changes to it, or close it with an explanation. We’ll do our best to provide updates and feedback throughout the process.
Before submitting a pull request, please make sure the following is done:
Fork the repository and create your branch from master.
If you’ve fixed a bug or added code that should be tested, add tests!
Ensure the test suite passes.

## License
By contributing to Orbs Network, you agree that your contributions will be licensed under its MIT license.

---
This document inspired by:
* https://reactjs.org/docs/how-to-contribute.html
* https://www.stellar.org/developers/guides/contributing.html
* https://www.contributor-covenant.org/

