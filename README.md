# PranaSync project tracker

A standalone task and branch tracker for the PranaSync team. GitHub status snapshot checked 2026-11-10.

## Project timeline

The tracker covers the project from its start. The project start date is **October 1, 2026**, as specified by the user for the date the project was first pushed to the main repository. This is shown as a user-provided timeline baseline; it is not independently confirmed as a Git commit author date. GitHub author-date search for 2026-10-01 returned no matching commit in the checked repository.

## Open the tracker

Open `tracker.html` in a browser. Use the owner/status filters to narrow the cards. Each card lets you change its workflow state; those edits are saved in that browser’s local storage. They do not sync to GitHub.

## Contents

- `tracker.html` — offline interactive task board
- `tasks.json` — task details, evidence notes, and project start-date provenance
- `branches.csv` — live branch names and their mapped task/PR status

## Progress meaning

Progress is the Git workflow stage, not an estimate of effort or code quality. Merged-to-main is 100%, merged-to-integration-branch is 80%, and an open pull request is about 70%. A task with code on main but unclear PR lineage is labeled separately.

## Source and attribution caveats

The current task ownership comes from the current roles document in the supplied ZIP. Branches and PR state were checked on GitHub. The ZIP’s embedded Git checkout is stale at `c57a815` while live `main` is `2cdc54d`; its uncommitted status therefore does not mean those files still need pushing. Uday’s 22 currently assigned files match live `main` or open PR #11 exactly.

Some PR authors differ from the current role assignments. The task cards preserve that distinction instead of treating assignment as proof of authorship. PRs #7–9 are merged into `feature/insight`, not directly into `main`.

The tracker is kept separately from the PranaSync source repository.
