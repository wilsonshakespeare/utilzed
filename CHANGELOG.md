# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

And for each point, add semantics:
https://seesparkbox.com/foundry/semantic_commit_messages

For each keypoint, treat like commit messages, follow [Chris Beams' rules](https://chris.beams.io/posts/git-commit/)

## [Unreleased]

## [0.2.4] - 2021-2-13
### Added:
- chore: Update prettier and .vscode/setting.json for standard format
- chore: Update README.md for create-tslibs reference

## [0.2.3] - 2021-2-1
### Added:
- chore: Separate build modules instead of index.js

Hence the following is possible:
```javascript
// to import promise module
import promise from 'utilzed/dist/promise'

// the caveat will be having the need to use dist/
```
## [0.2.2] - 2021-2-1
### Fixed:
- fix: Fix `package.json` dependencies
## [0.2.1] - 2021-2-1
### Added:
- feat: Added `versionCheck` functionality
## [0.2.0] - 2021-2-1
### Changed:
- chore: test files using `src/index` to ensure library usability

### Fix:
- fix: Add missing `/timeconvert` `Format` enum into index using `timeconvert` property

### Removed:
- chore: remove `TimeConvert` property from index

## [0.1.4] - 2021-2-1
### Changed:
- docs: Update README.md from utilized to utilzed
- docs: Update README.md for install instruction
## [0.1.3] - 2021-2-1
### Added:
- docs: Add functions documentation
- docs: Add CHANGELOG.md

### Changed:
- refactor: Rename waitFor to waitForTrue for semantic purpose
- note: since is still new and fresh no point having major version update
  instead use patch
## [0.1.2] - 2021-1-31
### Fixed:
- fix: Add flowgen.js command to npm run prepare so build can generate flow files

## [0.1.1] - 2021-1-31
### Changed:
- chore: Rename utilz to utilzed and fix jsdoc comment because npm package utilz is taken

### Fixed:
- fix: Fix
