# Copperleaf Desktop — Release Notes

All notable changes to Copperleaf Desktop are documented here.
Sections are ordered newest first; each released version links back to the
issue tracker entries that shipped with it.

## Unreleased

- Add workspace tab pinning (#1)
- Fix crash when searching with an empty query (#2)
- Improve onboarding checklist wording (#3)
- Prevent duplicate sync jobs after reconnect (#5)
- Support custom keybindings (#11)
- Tighten file permission checks on import (#12)
- Add release channel switch (#13)
- Improve diagnostics bundle (#14)
- Refresh license banner styling (#15)
- Write migration guide for settings v3 (#16)

## v4.2.0 — 2026-09-18

- Restored keyboard shortcuts after the editor rewrite (#142)
- Reduced cold start time on workspaces with more than 10,000 notes (#148)

### Maintenance

- Upgraded the packaging toolchain to Node 22 (#151)
- Dropped support for macOS 12 (#154)

## v4.1.0 — 2026-08-05

- Added multi-window support for notebooks (#118)
- Fixed tab ordering when reopening a session (#121)

### Maintenance

- Replaced the legacy icon set (#126)

## v4.0.0 — 2026-06-22

- Rebuilt the sync engine on the new storage layer (#63)
- Migrated the settings schema to version 3 (#67)

## v3.9.0 — 2026-04-11

- Added command palette search across all notebooks (#34)
- Fixed the export dialog freezing on large selections (#37)
