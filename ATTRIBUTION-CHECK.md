# Co-author attribution check

This is a diagnostic experiment, not evidence of collaboration between two independent people. The repository owner states that `almuzahidseyam` and `BUETianBro` are both their accounts. This document was prepared with AI assistance at the owner's request.

## What this experiment checks

1. A commit contains a correctly formatted `Co-authored-by:` trailer, separated from its subject by a blank line.
2. GitHub renders the secondary account as a linked co-author.
3. A pull request merges the commit into the public repository's default branch, `main`.
4. A merge commit preserves the original attributed commit as a parent.

These observations can verify attribution and merge preservation. They do not establish eligibility for an achievement, prove that GitHub counted this PR, or guarantee a badge or tier upgrade. One PR cannot establish the 10/24/48 tier thresholds reported by the community.

## Reproduce the inspection

- Open the pull request's Commits tab.
- Open the documentation commit and inspect both account links.
- After merging, inspect the merge commit and its parent commits.
- Compare the profile achievement history separately; do not infer badge progress from the repository's contributor count.

## Baseline: 2026-10-02

The owner's Private contributions option was already enabled. Pair Extraordinaire was displayed at the base tier; the achievement history linked an older collaboration from 2024. No tier upgrade is claimed by this experiment.

## Reference

[GitHub: Creating a commit with multiple authors](https://docs.github.com/en/pull-requests/how-tos/commit-changes/creating-a-commit-with-multiple-authors)
