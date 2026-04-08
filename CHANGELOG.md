<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# symbols Changelog

## [Unreleased]

## [0.1.0] - 2026-04-07
### Added
- Initial public release of Symbols Icons for JetBrains.
- File and folder icon provider with generated mappings from `vscode-symbols`.
- Automated icon generation pipeline using `deno task build`.
- Icon-provider integration tests covering filename, extension, folder, and fallback behavior.

### Changed
- Normalized generated SVG dimensions for JetBrains tree rendering.
- CI release guards to fail when generated icon assets are out of sync.
