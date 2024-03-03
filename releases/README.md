# Release Phases

## Release Start

This is the day work on the stated release officially starts.

## Enhancements Freeze

All enhancements wishing to be included in the current release **MUST HAVE**
a merged Pull Request to https://github.com/konveyor/enhancements describing
an enhancement that is `implementable`.

Approximately 6 weeks from [Release Start](#release-start).

## Feature Freeze

All features selected for the current release should be merged by this date.
No new features should be accepted after this date. During this time, only
changes targeting the current release should be accepted.

Approximately 6 weeks from [Enhancements Freeze](#enhancements-freeze).

## Code Freeze

This is the day that the release branch (ie. `release-X.Y`) will be created from
`main`. Nothing but the most critical release blockers should be merged after
this date. Changes targeting a future release can now be accepted into the `main`
branch, but this will require repository maintainers to cherry-pick changes into
the release branch.

Approximately 2 weeks after [Feature Freeze](#feature-freeze).

## Release Date

This is the day the release is officially published for public consumption.
