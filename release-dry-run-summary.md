# Release Dry Run Summary

This gist-like summary 기록s the sandbox dry run of the release checklist performed in advance of the first tagged release.

## Repository
- **Repository:** mcpmark-eval-liuhezi/release-check-dryrun (public)
- **URL:** https://github.com/mcpmark-eval-liuhezi/release-check-dryrun
- **Default branch:** main (initialized with README)

## Pull Request
- **PR Number:** #8
- **Title:** Add draft release notes
- **URL:** https://github.com/mcpmark-eval-liuhezi/release-check-dryrun/pull/8
- **Branch:** notes/draft -> main
- **State:** MERGED (merge commit sha 36486d35903ac5a7616297e0620f88bce00ea6e4)
- **Changed files:** The PR diff only touches docs/release-notes.md (added on the notes/draft branch).

## Review Comment Submitted
- **Review type:** COMMENT review (not an approval)
- **Review state returned by API:** COMMENTED
- **Review comment text:** "Checklist item: please confirm the draft entries with the release manager before we cut the release."
- **Review URL:** https://github.com/mcpmark-eval-liuhezi/release-check-dryrun/pull/8#pullrequestreview-5876344513

## CI Workflow
- **Workflow file:** .github/workflows/release-dryrun.yml (name: Release Dry Run, ID 393532134, state: active)
- **Trigger:** workflow_dispatch (manual trigger)
- **Run triggered:** Run #29, run id 43239836435
- **Run URL:** https://github.com/mcpmark-eval-liuhezi/release-check-dryrun/actions/runs/43239836435
- **Status at time of check:** in_progress (queued immediately after triggering; prior runs #25–#28 all completed with conclusion: success)

## Tag Check Result
- **Git tags:** None yet (list_tags returned an empty array []). The repository has no tags at this point, so the next step after this dry run will be to create the first tagged release.

## Notes
- Direct repository creation under the personal account (HeziLiu) was blocked by token scope (403 Resource not accessible by personal access token), so the sandbox repository was created in the accessible organization mcpmark-eval-liuhezi.
- The notifications API was also not accessible with the current token permissions (403), so notification review could not be performed programmatically; this should be checked manually in the GitHub UI before the real release.
- A secret gist could not be created because the personal access token lacks thepokeist scope (POST /gists returns 403); the summary is instead published as a public file (release-dry-run-summary.md) in the repository.
