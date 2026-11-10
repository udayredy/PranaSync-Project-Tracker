# PranaSync project tracker

A standalone public task and branch tracker for the PranaSync team. GitHub status snapshot checked 2026-11-10.

## Open the tracker

Live site: https://udayredy.github.io/PranaSync-Project-Tracker/

The source is in `index.html` and `tracker.html`. Use the owner and status filters to narrow cards. Change a card’s workflow state to save it in that browser’s local storage. Those edits do not sync to GitHub.

## Project timeline

The tracker covers the project from its start. The project start date is **October 1, 2026**, as specified by the user for the date the project was first pushed to the main repository. This is a user-provided timeline baseline; it is not independently confirmed as a Git commit author date. GitHub author-date search for 2026-10-01 returned no matching commit in the checked repository.

## Contents

- `index.html` — GitHub Pages entry point for the interactive task board
- `tracker.html` — standalone copy of the interactive task board
- `tasks.json` — task details, evidence notes, and project start-date provenance
- `branches.csv` — live branch names and their mapped task/PR status

## Progress meaning

Progress is the Git workflow stage, not an estimate of effort or code quality. Merged-to-main is 100%, merged-to-integration-branch is 80%, and an open pull request is about 70%. A task with code on main but unclear PR lineage is labeled separately.

## Source and attribution caveats

The current task ownership comes from the current roles document in the supplied ZIP. Branches and PR state were checked on GitHub. The ZIP’s embedded Git checkout is stale at `c57a815` while live `main` is `2cdc54d`; its uncommitted status therefore does not mean those files still need pushing. Uday’s 22 currently assigned files match live `main` or open PR #11 exactly.

Some PR authors differ from the current role assignments. The task cards preserve that distinction instead of treating assignment as proof of authorship. PRs #7–9 are merged into `feature/insight`, not directly into `main`.

The tracker is kept separately from the PranaSync source repository.

