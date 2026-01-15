# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0-beta.5] - 2026-01-15
### Fixed
- **Logging:** Resolved `NameError: name 'XMLParsedAsHTMLWarning' is not defined` that caused the container to crash on startup. (Thanks @rpowel!)
- **Stability:** Bulletproofed warning suppression logic to handle different BeautifulSoup4 versions.

## [1.0.0-beta.4] - 2026-01-12
### Added
- **Dependencies:** Included `lxml` in `requirements.txt` for faster, native XML sitemap parsing.
- **Documentation:** Restored release badges and sanitized README URLs.

## [1.0.0-beta.1] - 2026-01-04
### Added
- Experimental support for Tandoor Recipes.
- Docker and Docker-Compose support.
- Initial curated list of 100+ food blogs.
- Automated duplicate detection for Mealie and Tandoor.

### Fixed
- README formatting and copy-paste compatibility.
