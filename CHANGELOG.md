# Changelog

All notable changes to this project are documented here.
The format is based on [Keep a Changelog](https://keepachangelog.com/),
and this project adheres to [Semantic Versioning](https://semver.org/).

## [1.2.1] - 2026-06-14

### Fixed
- Removed all `!important` declarations; bold and italic now win by selector
  specificity, and the editor cursor is colored via the `--caret-color` variable.
- Added `screenshot.png` and a `screenshot` field to `manifest.json` so the theme
  preview resolves during submission.

## [1.2.0] - 2026-06-14

### Changed
- Split the Paper (Courier) look out into its own standalone theme,
  [Paper Source](https://github.com/Brightwav3/Paper-Source). Coding Agent now
  focuses on its two coding-agent identities: **Claude Code** and **OpenAI Codex**.
- Aligned the `manifest.json` author name and `authorUrl` with the repository.

### Removed
- The **Paper (Courier)** option from the Style Settings *Look* selector and all
  associated `cc-look-paper` styling.

### Added
- MIT license file.
- Expanded README with the looks overview, full feature list, a Style Settings
  reference table, and detailed installation instructions.
- This changelog.

## [1.1.0] - 2026-06-12

### Added
- Paper (Courier) look alongside Claude Code and OpenAI Codex.
- Style Settings controls for background depth, corner radius, font size,
  monospace UI, and the H1 prompt glyph.

## [1.0.0] - 2026-06-11

### Added
- Initial release with Claude Code and OpenAI Codex looks.
