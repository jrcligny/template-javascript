# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [v1.0.0] - 2024-07-31

### Added 

- Add `Changelog.md` file
- Set recommended VSCode extensions: `github.copilot`, `vscode-pull-request-github`, `dbaeumer.vscode-eslint
- Setup Jest:
	- Set basic Jest configuration with coverage report. Test files are located alongside the source files, following the `*.spec.(e2e|int|unit).js` naming convention.
	- Set VSCode tasks to run Jest tests: `Run tests`, `Run Current Spec File`, `Run Related Spec File`, `Open Coverage Report`
	- Set VSCode launch configurations to run Jest tests: `Debug Jest Tests`
- Set basic GitHub Actions workflows and linting rules