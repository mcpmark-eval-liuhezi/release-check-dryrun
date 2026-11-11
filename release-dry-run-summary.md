# Release Dry Run Summary

Dry run of the release checklist ahead of the first tagged release.

- **Repository:** mcpmark-eval-liuhezi/release-check-dryrun (public; default branch: `main`)
- **Pull request:** #1 — "Add draft release notes"
  - URL: https://github.com/mcpmark-eval-liuhezi/release-check-dryrun/pull/1
  - PR files check: only `docs/release-notes.md` was touched (1 changed file, +10/−0)
  - Review comment submitted on `docs/release-notes.md` (line 1):
    "Checklist item: please confirm the draft entries with the release manager before we cut the release."
    Review state: COMMENTED (comment review, not approval), verified present via the PR review-comments API (comment id 4355198010).
- **CI workflow:** `.github/workflows/release-dryrun.yml` ("Release Dry Run") — manually triggered via workflow_dispatch.
  - Latest run id: 42938958604 (run #4 on `main`, event: workflow_dispatch)
  - Status at check: completed / conclusion: success
  - URL: https://github.com/mcpmark-eval-liuhezi/release-check-dryrun/actions/runs/42938958604
  - Earlier runs: 42892657913 (run #2, success), 39883395430 (run #1, success)
- **Tag check:** No git tags exist in the repository yet (empty tag list) — expected, first tag will be cut during the real release.
- **Notification check:** Unable to list notifications with the current token (403 Resource not accessible by personal access token); no notification data available to confirm or clear — needs manual check before the real release.
- **Gist fallback:** Secret gist creation is blocked by token scope (403); this file serves as the dry-run summary record.
