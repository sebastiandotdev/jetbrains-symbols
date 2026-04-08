<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# symbols Changelog

## [Unreleased]

## [0.1.2] - 2026-04-08

For stable releases, please refer to [CHANGELOG.md](https://github.com/sebastiandotdev/jetbrains-symbols/blob/main/CHANGELOG.md) for details.

## [0.1.1] - 2026-04-08

### Fixed

- Updated platform target to IntelliJ 2026.1 for full compatibility.
- Lowered `since-build` to 241 (IntelliJ 2024.1+) for broader IDE support.

## [0.1.0] - 2026-04-07

### Added

- Initial public release of Symbols Icons for JetBrains.
- File and folder icon provider with generated mappings from `vscode-symbols`.
- Automated icon generation pipeline using `deno task build`.
- Icon-provider integration tests covering filename, extension, folder, and fallback behavior.

### Changed

- Normalized generated SVG dimensions for JetBrains tree rendering.
- CI release guards to fail when generated icon assets are out of sync.

[Unreleased]: https://github.com/sebastiandotdev/symbols/compare/0.1.2...HEAD
[0.1.2]: https://github.com/sebastiandotdev/symbols/compare/0.1.1...0.1.2
[0.1.1]: https://github.com/sebastiandotdev/symbols/compare/0.1.0...0.1.1
[0.1.0]: https://github.com/sebastiandotdev/symbols/commits/0.1.0
