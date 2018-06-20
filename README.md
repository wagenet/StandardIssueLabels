# StandardIssueLabels
A Set of Standardized Labels for Github Issues

## Purpose

The idea behind these labels is to make it easy to find things that are actually important to us. Bugs and regressions take high priorities. Only certain people are qualified to review features and documentation. Cleanup stuff is important but not high priority usually. We also want to know who/what any given ticket is blocking on.

## Suggested Labels

* **Issue Types**
  * **Bug** - Anything that is broken
  * **Regression** - A bug that did not exist in previous versions and isn't a new feature (applied in tandem with Bug)
  * **Feature** - Anything that involves API changes, should generally only be for PRs or bug reports on in-progress features.
  * **Performance** - A performance related issue. We could track this as a bug, but usually these would have slightly lower priority than standard bugs.
  * **Cleanup** - Not a bug, not a feature, just code cleanup.
  * **Documentation** - Self-explanatory.
* **Blockers** 
  * **Needs Bug Verification** - A bug report, needs verification that it's actually a bug.
  * **Needs Reproduction** - Needs a test case or other reproduction of the issue.
  * **Has Reproduction** - Indicates a test case exists and is up-to-date.
  * **Ready for PR** - A well defined bug, needs someone to PR a fix.
  * **PR Pending** - A well defined bug, with a PR pending to fix.
  * **Needs Code Review** - A PR that needs the code to be verified by someone.
  * **Needs Submitter Response** - Anything that is blocking on the submitter.
  * **Needs Team Discussion** - Cannot progress until the core team has discussed further.
* **Categories** - These change per-project, may want to prefix, e.g. "C: HTMLBars". The big thing here is to keep proliferation low. If it gets too high, we might just want to change the issue title instead, e.g. prefix with "[HTMLBars]".
  * **HTMLBars**
  * **Router**
  * ...
* **Miscellaneous** - These are per project and might be useful for further organization but should be kept to a minimum as well.
  * **good first issue** - What it says on the tin. This helps new people find stuff to work on, because [GitHub actively promotes it](https://help.github.com/articles/helping-new-contributors-find-your-project-with-labels/) and [initializes new repositories with that label](https://help.github.com/articles/about-labels/#using-default-labels).

## Other Notes

* All PR Titles for in progress features should be prefixed with `[FEATURE name]`
