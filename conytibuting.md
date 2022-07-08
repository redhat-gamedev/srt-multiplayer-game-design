# Contributing to Space Ring Things

The following is a set of guidelines for contributing to Space Ring Things - Scaleable Multiplayer Games (SRT) and its repositories, which are hosted in the [redhat-gamedev](https://github.com/redhat-gamedev) on GitHub. These are mostly guidelines, so use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [What is SRT?][#what-is-srt)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

## Code of Conduct

This project and everyone participating in it is governed by the
[SRT Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected
to uphold this code. Please report unacceptable behavior to [email](mailto:email).

## What should I know before I get started?

### What is SRT?

SRT is a multiplayer space game developed by Red Hat's Gaming Community of
Practice (COP). For more information on the history of the game and design
choices check out the [Game Design README(https://github.com/redhat-gamedev/srt-multiplayer-game-design/blob/master/README.md)

It is important to note that SRT resides in the following repositories:
  * [srt-multiplayer-game-design](https://github.com/redhat-gamedev/srt-multiplayer-game-design)
  * [srt-game-server](https://github.com/redhat-gamedev/srt-game-server)
  * [srt-web-client](https://github.com/redhat-gamedev/srt-web-client)
  * [srt-ruby-lobby](https://github.com/redhat-gamedev/srt-ruby-lobby)
  * [srt-godot-server](https://github.com/redhat-gamedev/srt-godot-server)
  * [srt-godot-client](https://github.com/redhat-gamedev/srt-godot-client)
  * [srt-website](https://github.com/redhat-gamedev/srt-website)

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for SRT. Following these
guidelines helps maintainers and the community understand your report, reproduce
the behavior, and find related reports.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report)
as you might find out that you don't need to create one. When you are creating a
bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). 
Fill out [the required template](https://github.com/redhat-gamedev/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md),
the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing
that you're experiencing, open a new issue and include a link to the original
issue in the body of your new one.

#### Before Submitting A Bug Report

* **Determine [which repository the problem should be reported in](#what-is-srt)**.
* **Perform a [cursory search](https://github.com/search?l=&q=is%3Aissue++repo%3Aredhat-gamedev%2Fsrt-multiplayer-game-design+repo%3Aredhat-gamedev%2Fsrt-web-client+repo%3Aredhat-gamedev%2Fsrt-godot-server+repo%3Aredhat-gamedev%2Fsrt-game-server+repo%3Aredhat-gamedev%2Fsrt-ruby-lobby&type=issues)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined [which repository](#what-is-srt)
your bug is related to, create an issue on that repository and provide the following information by filling in [the template](https://github.com/redhat-gamedev/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md).
amy@stable srt-multiplayer-game-design % nano contributing.md
amy@stable srt-multiplayer-game-design % nano contributing.md
amy@stable srt-multiplayer-game-design % git add .
amy@stable srt-multiplayer-game-design % git status
On branch contribution
Your branch is up to date with 'origin/contribution'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   contributing.md

amy@stable srt-multiplayer-game-design % git commit
[contribution 27d38bd] Create contributing.md
 1 file changed, 130 insertions(+)
 create mode 100644 contributing.md
amy@stable srt-multiplayer-game-design % git push 
Enter passphrase for key '/Users/amy/.ssh/id_rsa': 
ERROR: Permission to spotzz/srt-multiplayer-game-design.git denied to spotz.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
amy@stable srt-multiplayer-game-design % cat contributing.md 
# Contributing to Space Ring Things

The following is a set of guidelines for contributing to Space Ring Things - Scaleable Multiplayer Games (SRT) and its repositories, which are hosted in
the [redhat-gamedev](https://github.com/redhat-gamedev) on GitHub. These are mostly guidelines, so use your best judgment, and feel free to propose changes
to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)
  * [What is SRT?][#what-is-srt)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

## Code of Conduct

This project and everyone participating in it is governed by the [SRT Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold
this code. Please report unacceptable behavior to [email](mailto:email).

## What should I know before I get started?

### What is SRT?

SRT is a multiplayer space game developed by Red Hat's Gaming Community of Practice (COP). For more information on the history of the game and design
choices check out the [Game Design README(https://github.com/redhat-gamedev/srt-multiplayer-game-design/blob/master/README.md)

It is important to note that SRT resides in the following repositories:
  * [srt-multiplayer-game-design](https://github.com/redhat-gamedev/srt-multiplayer-game-design)
  * [srt-game-server](https://github.com/redhat-gamedev/srt-game-server)
  * [srt-web-client](https://github.com/redhat-gamedev/srt-web-client)
  * [srt-ruby-lobby](https://github.com/redhat-gamedev/srt-ruby-lobby)
  * [srt-godot-server](https://github.com/redhat-gamedev/srt-godot-server)
  * [srt-godot-client](https://github.com/redhat-gamedev/srt-godot-client)
  * [srt-website](https://github.com/redhat-gamedev/srt-website)

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for SRT. Following these guidelines helps maintainers and the community understand your report,
reproduce the behavior, and find related reports.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When
you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report).  Fill out [the required template](https://github.com/redhat-gamedev/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md),
the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the
original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Determine [which repository the problem should be reported in](#what-is-srt)**.
* **Perform a [cursory search](https://github.com/search?l=&q=is%3Aissue++repo%3Aredhat-gamedev%2Fsrt-multiplayer-game-design+repo%3Aredhat-gamedev%2Fsrt-web-client+repo%3Aredhat-gamedev%2Fsrt-godot-server+repo%3Aredhat-gamedev%2Fsrt-game-server+repo%3Aredhat-gamedev%2Fsrt-ruby-lobby&type=issues)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined [which repository](#what-is-srt)
your bug is related to, create an issue on that repository and provide the following information by filling in [the template](https://github.com/redhat-gamedev/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md).
Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible.
* **Explain what behavior you expected to see instead and why.**
* **Include screenshots** which show you following the described steps and clearly demonstrate the problem.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of SRT) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of SRT?** What's the most recent version in which the problem doesn't happen?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for SRT, including completely new features and minor improvements to existing functionality.
Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one.
When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](https://github.com/redhat-gamedev/.github/blob/master/.github/ISSUE_TEMPLATE/architecture-design-record.md), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

* **Determine [which repository the enhancement should be suggested in](#what-is-srt).**
* **Perform a [cursory search](https://github.com/search?l=&q=is%3Aissue++repo%3Aredhat-gamedev%2Fsrt-multiplayer-game-design+repo%3Aredhat-gamedev%2Fsrt-web-client+repo%3Aredhat-gamedev%2Fsrt-godot-server+repo%3Aredhat-gamedev%2Fsrt-game-server+repo%3Aredhat-gamedev%2Fsrt-ruby-lobby&type=issues)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined [which repository](#what-is-srt) your enhancement suggestion is related to, create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Explain why this enhancement would be useful** to most SRT users.

### Your First Code Contribution

Unsure where to begin contributing to SRT? You can start by looking through these `beginner` and `help-wanted` issues:

* [Beginner issues][beginner] - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

Once you have an issue to work on you're ready to get started. The following workflow is based on the GitHub [Quickstart](https://docs.github.com/en/get-started/quickstart) documentation.
	
Workflow:

* **Determine [which repository you will be working with](#what-is-srt)**
* **[Fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo)**
* **[Create a branch in your fork](https://docs.github.com/en/get-started/quickstart/github-flow#create-a-branch)**
* **[Work on your issue](https://docs.github.com/en/get-started/quickstart/github-flow#make-changes)**
* Create your Pull Request

You can also use the [CLI](https://training.github.com/downloads/github-git-cheat-sheet.pdf) to follow the workflow. 

### Pull Requests

The process described here has several goals:

- Maintain SRT's quality
- Fix problems that are important to users
- Engage the community in working toward the best possible SRT
- Enable a sustainable system for SRT's maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](PULL_REQUEST_TEMPLATE.md)
2. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
