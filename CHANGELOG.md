# Change Log
All notable changes to the "vscode-trailingspaces" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

## [0.3.0] - 2019-04-06
### Added
- Allow specific schemes to be ignored.
- Add options to change background and border colors of highlighting.
- Add option to disable status bar message.

### Changed
- Only attach VSCode event listeners if current settings require them.
- Major refactor to simplify the core extension logic.
- Ignore `output` scheme by default

### Fixed
- Fix "Trim on Save" requiring file to be saved twice.
- Fix error when trying to read saved document for non-file schemes.

### Removed
- Remove "Save after Trim" as current VSCode lifecycle for text editor commands does not provide a clean way to implement this feature.
- Remove `deleteInFolder` and `deleteInFolderRecursive` functionality which was experimental.