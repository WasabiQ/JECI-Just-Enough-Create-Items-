## [Changelog 0.1] - 2025-03-10
### Added
- Updated `build.gradle` with the latest versions of:
  - Fabric API (0.92.3)
  - JEI (15.20.0.106)
  - Mod Menu (7.2.2)
  - Kotlin (1.13.1)
- Organized `build.gradle` with comments for better readability.
- Implemented `JECIClient.kt` as the client-side entry point.
- Began integrating JEI with JECI following official documentation.

### Fixed
- Verified `gradle.properties` to ensure all dependencies match the correct versions.
- Investigated logger issue in `JECI.kt` (`LoggerFactory.getLogger("jeci")`).

### Changed
- Switched preference from Java to Kotlin for cleaner syntax.
- Adjusted understanding of JEI ownership (Mezz → MightyPanda).

### Next Steps
- Debug the logger issue in `JECI.kt`.
- Finalize client-side setup before working on the main logic.
- Continue JEI integration.
