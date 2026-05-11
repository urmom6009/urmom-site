# Changelog

## 2026-05-11

### Changed

- Rebuilt the home page on the shared `BaseLayout` structure with clearer focus areas, active work, and systems status sections.
- Recreated the public systems page with service status cards, infrastructure layer notes, and an embedded Uptime Kuma board.
- Recreated the private admin systems page as a layout-based control-room launchpad with `noindex` metadata.
- Updated the main navigation to include the writing section and moved contact access to the contact ribbon.
- Reworked the home hero, navigation ribbon, and pink/blue accent palette for a cleaner visual system.
- Added a `/contact` redirect to `/about#contact`.
- Expanded shared responsive styling for the rebuilt home, systems, admin, and writing pages.

### Added

- Added a writing page for research notes, systems runbooks, and technical project writeups.

### Removed

- Removed duplicate placeholder route files under `src/pages/projects/index.astro` and `src/pages/research/index.astro`.
