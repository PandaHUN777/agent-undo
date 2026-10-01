# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]

### Added

- GitHub Actions CI running pytest on Python 3.10/3.11/3.12 and ruff lint.

### Changed

### Fixed

- Removed unused imports in `agent_undo/rollback.py` (`difflib`, `textwrap`,
  `pathlib.Path`).
- Moved the mid-file `dataclasses` import in `agent_undo/rollback.py` to the
  top of the module, where it belongs.
- Dropped redundant `f` prefixes from f-strings without placeholders and
  wrapped over-long lines in `journal.py` and `rollback.py`.
- Removed an unused `cp_id` local and an unused `pathlib.Path` import in the
  test suite.

## [Initial Release]

- Initial project release
