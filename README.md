# PranaSync task tracker

A public tracker for the PranaSync team with a work item list, assigned teammate, linked branch and PR, verified GitHub evidence, and three status sections.

## Open the tracker

Live site: https://udayredy.github.io/PranaSync-Project-Tracker/index.html

The list is grouped into **Done**, **In progress**, and **Next sprint**. Use search and filters to narrow it. The per-item stage menu and CSV export are available on the page. Stage edits are saved in that browser only; they do not update GitHub.

## Stage mapping

- **Done**: merged to `main` or the work is present on `main`.
- **In progress**: merged to `feature/insight` or included in an open pull request.
- **Next sprint**: no current branch/PR evidence of active work. No tasks in the checked snapshot met this condition.

The simpler stage labels are mapped from the detailed GitHub state shown beside each item. Assignment and PR authorship remain separate facts.

## Project timeline

The start date is **October 1, 2026**, the date the user specified as the main repository's project start. GitHub author-date search did not independently verify an Oct 1 commit; the date is shown as a user-provided timeline baseline.

## Data sources and caveats

Task ownership comes from the supplied current roles document. Branches and PR status were checked against GitHub. The supplied ZIP checkout is stale at `c57a815`; live `main` is `2cdc54d`. Uday’s 22 assigned paths match files on `main` or in open PR #11. PRs #7–9 are merged into `feature/insight`, not directly into `main`.

The tracker is separate from the PranaSync source repository.
