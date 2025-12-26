# Changelog

---

## [0.0.1] – 2025-12-26
### Added
- Complete rewrite of the DataServer script for improved performance and maintainability
- Migration from basic DataStoreService usage to PlayerStore to reduce throttling under load
- Centralized server-side handling of player data and persistence

### Fixed
- Weapon spawning via client-controlled remotes
- Grenade duplication exploit
- Audio spam through unvalidated remote events
- Ban player exploit caused by missing server authority checks

---
