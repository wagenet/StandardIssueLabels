# StandardIssueLabels
A Set of Standardized Labels for Github Issues

## Purpose

The idea behind these labels is to make it easy to find things that are actually important to us. Bugs and regressions take high priorities. Only certain people are qualified to review features and documentation. Cleanup stuff is important but not high priority usually. We also want to know who/what any given ticket is blocking on.

## Suggested Labels

* **Issue Types**
  * **Bug** - Anything that is broken
  * **Regression** - A bug that did not exist in previous versions and isnâ€™t a new feature (applied in tandem with Bug)
  * **Feature** - Anything that involves API changes, should generally only be for PRs or bug reports on in-progress features.
  * **Performance** - A performance related issue. We could track this as a bug, but usually these would have slightly lower priority that standard bugs.
  * **Cleanup** - Not a bug, not a feature, just code cleanup.
  * **Documentation** - Self-explanatory.
* **Blockers** 
  * **Needs Bug Verification** - A bug report, needs verification that itâ€™s actually a bug.
  * **Ready for PR** - A well defined bug, needs someone to PR a fix.
  * **Needs Code Review** - A PR that needs the code to be verified by someone.
  * **Needs Submitter Response** - Anything that is blocking on the submitter.
  * **Needs Team Discussion** - Cannot progress until the core team has discussed further.
* **Categories** - These change per-project, may want to prefix, e.g. "C: HTMLBars". The big thing here is to keep proliferation low. If it gets too high, we might just want to change the issue title instead, e.g. prefix with "[HTMLBars]".
  * **HTMLBars**
  * **Router**
  * ...
* **Miscellaneous** - These are per project and might be useful for further organization but should be kept to a minimum as well.
  * **Good for New Contributors** - What it says on the tin. In theory this helps new people find stuff to work on. (Do we have evidence that people are paying attention to this? If not, it's just noise.)

## Other Notes

* All PR Titles for in progress features should be prefixed with `[FEATURE name]`
