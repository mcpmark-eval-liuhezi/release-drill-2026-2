# Release Checklist

Use this checklist when running a release drill or a real release.

## Pre-release

- [ ] Confirm the release manager on rotation is identified
- [ ] Verify the default branch is green (CI passing on the latest commit)
- [ ] Confirm all merged pull requests for this release are accounted for

## Release

- [ ] Trigger the release workflow manually (`workflow_dispatch`)
- [ ] Watch the workflow run and confirm it completes successfully
- [ ] Note the workflow run id and its final status

## Post-release

- [ ] Record the workflow run id and status in the release record
- [ ] Confirm the release pull request is up to date with the default branch
- [ ] Record the pull request number and the final commit SHA
- [ ] Post the release report as a comment on the parent issue
