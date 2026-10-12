# clj-kondo/clj-kondo context
> refreshed 2026-10-12 | upstream default: master @ f2f09c8c5de92e0e9c98ad501e60a57abd45c50b

## Identity & policies
- upstream: clj-kondo/clj-kondo, default branch `master`, primary language Clojure, English-first yes.
- CLA/DCO: none (no CLA bot / DCO in CONTRIBUTING or .github).
- AI-assisted PR policy: unstated (no AI ban found in docs/.github).
- signed commits required: no.
- PR template: `.github/pull_request_template.md` (5 checkboxes: etiquette, dev.md, issue-first, test, CHANGELOG).
- external tracker: github (project board at projects/1).

## Conventions (verified from merged PRs)
- branch naming: `fix-<issue>` dominant, also `perf-*`, `changelog-*`, `graalvm-*`, `pr-<n>`, descriptive kebab.
- commit style: imperative, no conventional-commit prefix required.
- test command: `script/test` (JVM), `CLJ_KONDO_TEST_ENV=native script/test`, `clojure -X:test:test-regression`.
- CI: GitHub Actions (ci.yml, clj-kondo.yml, diff.yml, windows.yml) + legacy CircleCI/AppVeyor badges in README.
- outside PRs do get merged: willcohen, alexander-yakushev, hugoduncan merged recently.

## Maintainer picture
- sole core maintainer: borkdude (very active, merges own PRs daily).
- external contributors merged regularly (small, focused PRs).

## Issue-area health
- dev.md asks contributors to open an issue before non-trivial work; trivial doc/link/typo fixes are low-risk and not gated by issue-first in practice.

## Gap ledger (dedupe — READ FIRST, never re-pick)
- 2026-09-03: docs trivial cleanup PR opened (fix-docs-typos -> PR #2): 8 fixes in 4 files (README empty link, stale --help version, 3 editor-integration typos, stale NixOS nixpkgs link, linters typo).
- 2026-10-12: typo cleanup PR opened (fix-docs-and-comment-typos -> PR #5): 15 fixes in 10 files (doc/dev.md predicable, doc/hooks.md correponding, doc/linters.md overriden + ambigious, doc/types.md misplaced example quote, src/clj_kondo/core.clj 3 stray docstring backticks, analyzer.clj postion/extented/exising, experiments/parallelize-analysis.md parallize, 3 test-description typos). Re-verified live @ f2f09c8; no upstream PR touches these strings. Did NOT re-pick PR #2's strings.

## Mined gaps (discovered, not yet attempted)
- (see current run)
