# clj-kondo/clj-kondo context
> refreshed 2026-09-03 | upstream default: master @ d92d155029301adc552381aae21faa82569700c8

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
- (none yet for this repo)

## Mined gaps (discovered, not yet attempted)
- (see current run)
