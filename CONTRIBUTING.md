**# Contributing to VS Code

Welcome, and thank you for your interest in contributing to VS Code!

There are several ways in which you can contribute, beyond writing code. The goal of this document is to provide a high-level overview of how you can get involved.

## Asking Questions


Have a question? Instead of opening an issue, please ask on [Stack Overflow](https://stackoverflow.com/questions/tagged/visual-studio-code) using the tag `visual-studio-code`.

The active community will be eager to assist you. Your well-worded question will serve as a resource to others searching for help.

## Providing Feedback

Your comments and feedback are welcome, and the development team is available via a handful of different channels.

See the [Feedback Channels](https://github.com/microsoft/vscode/wiki/Feedback-Channels) wiki page for details on how to share your thoughts.

## Reporting Issues

Have you identified a reproducible problem in VS Code? Do you have a feature request? We want to hear about it! Here's how you can report your issue as effectively as possible.

### Identify Where to Report

The VS Code project is distributed across multiple repositories. Try to file the issue against the correct repository. Check the list of [Related Projects](https://github.com/microsoft/vscode/wiki/Related-Projects) if you aren't sure which repo is correct.

Can you recreate the issue even after [disabling all extensions](https://code.visualstudio.com/docs/editor/extension-gallery#_disable-an-extension)? If you find the issue is caused by an extension you have installed, please file an issue on the extension's repo directly.

### Look For an Existing Issue

Before you create a new issue, please do a search in [open issues](https://github.com/microsoft/vscode/issues) to see if the issue or feature request has already been filed.

Be sure to scan through the [most popular](https://github.com/microsoft/vscode/issues?q=is%3Aopen+is%3Aissue+label%3Afeature-request+sort%3Areactions-%2B1-desc) feature requests.

If you find your issue already exists, make relevant comments and add your [reaction](https://github.com/blog/2119-add-reactions-to-pull-requests-issues-and-comments). Use a reaction in place of a "+1" comment:

* 👍 - upvote
* 👎 - downvote

If you cannot find an existing issue that describes your bug or feature, create a new issue using the guidelines below.

### Writing Good Bug Reports and Feature Requests

File a single issue per problem and feature request. Do not enumerate multiple bugs or feature requests in the same issue.

Do not add your issue as a comment to an existing issue unless it's for the identical input. Many issues look similar but have different causes.

The more information you can provide, the more likely someone will be successful at reproducing the issue and finding a fix.

The built-in tool for reporting an issue, which you can access by using `Report Issue` in VS Code's Help menu, can help streamline this process by automatically providing the version of VS Code, all your installed extensions, and your system info. Additionally, the tool will search among existing issues to see if a similar issue already exists.

Please include the following with each issue:

* Version of VS Code
* Your operating system
* List of extensions that you have installed
* Reproducible steps (1... 2... 3...) that cause the issue
* What you expected to see, versus what you actually saw
* Images, animations, or a link to a video showing the issue occurring
* A code snippet that demonstrates the issue or a link to a code repository the developers can easily pull down to recreate the issue locally
  * **Note:** Because the developers need to copy and paste the code snippet, including a code snippet as a media file (i.e. .gif) is not sufficient.
* Errors from the Dev Tools Console (open from the menu: Help > Toggle Developer Tools)

### Creating Pull Requests

* Please refer to the article on [creating pull requests](https://github.com/microsoft/vscode/wiki/How-to-Contribute#pull-requests) and contributing to this project.

### Final Checklist

Please remember to do the following:

* [ ] Search the issue repository to ensure your report is a new issue
* [ ] Recreate the issue after disabling all extensions
* [ ] Simplify your code around the issue to better isolate the problem

Don't feel bad if the developers can't reproduce the issue right away. They will simply ask for more information!

### Follow Your Issue

Once submitted, your report will go into the [issue tracking](https://github.com/microsoft/vscode/wiki/Issue-Tracking) workflow. Be sure to understand what will happen next, so you know what to expect and how to continue to assist throughout the process.

## Automated Issue Management

We use GitHub Actions to help us manage issues. These Actions and their descriptions can be [viewed here](https://github.com/microsoft/vscode-github-triage-actions). Some examples of what these Actions do are:

* Automatically close any issue marked `info-needed` if there has been no response in the past 7 days.
* Automatically lock issues 45 days after they are closed.
* Automatically implement the VS Code [feature request pipeline](https://github.com/microsoft/vscode/wiki/Issues-Triaging#managing-feature-requests).

If you believe the bot got something wrong, please open a new issue and let us know.

## Contributing Fixes

If you are interested in writing code to fix issues, please see [How to Contribute](https://github.com/microsoft/vscode/wiki/How-to-Contribute) in the wiki.

## Thank You

Your contributions to open source, large or small, make great projects like this possible. Thank you for taking the time to contribute.
**# Contributing to GNU Code Idea (GCI)

Welcome, and thank you for your interest in contributing to GNU Code Idea (GCI)!

## ⚠️ Important Note: Project Status

GCI is currently a **dependent fork** of Microsoft's VSCode. This means most bugs and issues originate from the upstream VSCode codebase.

**Please report most issues directly to [Microsoft/VSCode](https://github.com/microsoft/vscode) first.**

## Where to Report Issues

### 🐛 Report to Microsoft/VSCode if:
- The bug reproduces in original VSCode
- It's related to core editor functionality
- It occurs with all extensions disabled
- It's a general feature request for editor capabilities

### 🐛 Report to GCI if:
- The bug is **specific to GCI modifications**
- It's related to our **GPL-licensed components**
- It involves features **unique to GCI**
- You've confirmed the issue doesn't exist in upstream VSCode

## Asking Questions

**For all questions and discussions:**
- Use our [GitHub Discussions](https://github.com/your-org/gci/discussions)
- Or create a question issue in [GitHub Issues](https://github.com/your-org/gci/issues) with the `question` label

## Providing Feedback

We welcome feedback on:
- **GCI-specific features** and modifications
- **Licensing** and philosophical direction  
- **Integration** with free software ecosystems

For general editor feedback, please use [VSCode's feedback channels](https://github.com/microsoft/vscode/wiki/Feedback-Channels).

## Reporting Issues Effectively

### Before Creating an Issue

1. **Check upstream first**: Try reproducing in [latest VSCode](https://code.visualstudio.com/download)
2. **Disable extensions**: Ensure the issue isn't extension-related  
3. **Search existing issues**: Check both [GCI issues](https://github.com/your-org/gci/issues) and [VSCode issues](https://github.com/microsoft/vscode/issues)

### When Reporting to GCI

For GCI-specific issues, please include:

- GCI version and build information
- Confirmation that the issue doesn't reproduce in upstream VSCode
- Steps to reproduce (1... 2... 3...)
- Expected vs actual behavior
- OS and architecture
- Any GCI-specific features involved

## Contributing Code

Since we closely follow upstream, most code contributions should be made to [Microsoft/VSCode](https://github.com/microsoft/vscode/wiki/How-to-Contribute).

We welcome contributions to:
- GCI-specific modifications
- Integration with free software tools
- Documentation and localization
- Build system improvements

## Issue Management

We automatically sync with upstream security fixes and improvements. GCI-specific issues will be managed following our [security policy](SECURITY.md).

## Thank You

Thank you for supporting free software and helping build a truly free IDE ecosystem! Your contributions help advance software freedom for all developers.
