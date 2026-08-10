# Changelog
All notable changes to this project will be documented here.

## [Unreleased]
- Add a CI workflow running yamllint and actionlint over the workflows,
  the `*.yml-template` files, and a community-health file presence check.
- Fix Release Drafter: add the required `template` key to
  `.github/release-drafter.yml` and grant the job `contents: write`.
- Fix CodeQL: analyse `actions` instead of `python`, which this repository
  does not contain.
- Update actions: `github/codeql-action` v3 to v4,
  `release-drafter/release-drafter` v6 to v7, `actions/setup-python` v5 to v7,
  `actions/checkout` v4 to v7, and Python 3.12/3.13 to 3.14.

## [0.1.0] - 2025-10-22
- Initial release.
