# How to Contribute

One of the best ways to contribute is to participate in discussions and discuss issues. You can also contribute by submitting pull requests with code changes.

## General feedback and discussion
Please start a discussion on the [Home repo issue tracker](https://github.com/Microsoft/AppInsights-Home/issues). If you have feedback regarding the overall feature set of Application Insights or HockeyApp, you can also participate at the [Application Insights User Voice](http://aka.ms/aiuservoice).

## Bugs and SDK feature requests
Please log a new issue in the appropriate GitHub repo.

* [Asp.Net Core (formerly Asp.Net 5)](https://github.com/Microsoft/ApplicationInsights-aspnetcore)
* [DotNet Base](https://github.com/Microsoft/ApplicationInsights-dotnet)
* [DotNet Logging Adaptors](https://github.com/Microsoft/ApplicationInsights-dotnet-logging)
* [DotNet Server](https://github.com/Microsoft/ApplicationInsights-server-dotnet)
* [JavaScript](https://github.com/Microsoft/ApplicationInsights-js)
* [Java](https://github.com/Microsoft/ApplicationInsights-Java)
* [Node.js](https://github.com/Microsoft/ApplicationInsights-node.js)

## Specifications
Please read our specifications on the endpoint request-response protocol and SDK authoring before contributing to a client SDK.

* [Endpoint Protocol](EndpointSpecs/ENDPOINT-PROTOCOL.md)
* [SDK Authoring](EndpointSpecs/SDK-AUTHORING.md)

## General Contributing Guide

1. Unless it is a trivial change, make sure that there is a corresponding issue for your change first. If there is none, create one.
2. Create a fork in GitHub
3. Create a branch off the `develop` branch. Name it something that that makes sense, such as `issue-123` or `githubhandle-issue`. This makes it easy for everyone to figure out what the branch is used for. It also makes it easier to isolate your change from incoming changes from the origin.
4. Commit your changes and push your changes to GitHub
5. Create a pull request against the origin's `develop` branch. If you don't know what a pull request is read this article: https://help.github.com/articles/using-pull-requests.

Before submitting a feature or substantial code contribution please discuss it with the team and ensure it follows the product roadmap. You might also read these two blogs posts on contributing code: [Open Source Contribution Etiquette](http://tirania.org/blog/archive/2010/Dec-31.html) by Miguel de Icaza and [Don't "Push" Your Pull Requests](http://www.igvita.com/2011/12/19/dont-push-your-pull-requests/) by Ilya Grigorik.

### Commits

Please format commit messages as follows (based on this [excellent post](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)):

```
Summarize change in 50 characters or less

Provide more detail after the first line. Leave one blank line below the
summary and wrap all lines at 72 characters or less.

If the change fixes an issue, leave another blank line after the final
paragraph and indicate which issue is fixed in the specific format
below.

Fix #42
```

Also do your best to factor commits appropriately, i.e not too large with unrelated
things in the same commit, and not too small with the same small change applied N
times in N different commits. If there was some accidental reformatting or whitespace
changes during the course of your commits, please rebase them away before submitting
the PR.

## Contributor License
You must sign a [Contributor License Agreement](https://cla.microsoft.com/) before submitting your pull request. To complete the Contributor License Agreement (CLA), you will need to submit a request via the [form](https://cla.microsoft.com/) and then electronically sign the CLA when you receive the email containing the link to the document. You need to sign the CLA only once to cover submission to any Microsoft OSS project. 

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
