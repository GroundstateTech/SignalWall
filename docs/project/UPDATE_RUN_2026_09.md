# September 2026 Update Run

## Scope

This branch is the reviewable stability-and-feature pass for **SignalWall** (Static JavaScript media wall). It intentionally excludes user databases, credentials, private inventory, generated caches, and machine-local configuration.

## Priority checks

- source detection and safe URL handling
- session import/export reliability
- launcher and syntax validation

## Acceptance gate

- A clean checkout passes the repository's automated checks.
- Launch/build instructions match the files actually shipped.
- Existing standalone operation remains independent of Groundstate Admin Center.
- No sample, test, or generated artifact contains personal data or credentials.
- User-owned local state is preserved across upgrades.

## Delivery

Changes remain on `codex/update-run-2026-09-08` until this pull request is reviewed and merged.
