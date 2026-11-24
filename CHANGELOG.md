# Changelog

Notable changes recorded in this fork of IAmParadox27/jellyfin-plugin-media-bar.
The plugin itself is based on MakD's Jellyfin Media Bar. Dated entries come from
the verifiable git history of this repository; upstream release information was
checked against the GitHub Releases of IAmParadox27/jellyfin-plugin-media-bar.
The format follows Keep a Changelog. This fork does not publish its own
versioned releases.

## [Unreleased]

## [2026-10-31] — upstream

### Published release

- The latest upstream release is 3.0.2.0. It adds support for Jellyfin 12.3 and
  12.4 and merges the latest changes from MakD. This release was published
  after the last commit present on the `main` branch of this fork.

## [2026-10-28]

### Upstream sync

- Merged the latest upstream changes from MakD into the fork.

## [2026-10-21]

### Version numbers

- The version number in the repository history was bumped to 6.1.3, the last
  one recorded in this fork. It is not a plugin release number: the latest
  published upstream release is 3.0.2.0, listed above.

## [2026-10-19]

### Earlier version number

- The version number in the repository history was bumped to 6.1.2.

## [2026-10-13]

### Documentation

- Revised the README for the Play Now function and CSS support.

## [2026-10-12]

### Fixed

- Avoided `replaceChildren` for compatibility with older web engines.
- Kept YouTube trailer captions off the home rows.

## [2026-09-15]

### Platform retarget

- Retargeted the project to the current major Jellyfin line.

## [2026-08-28]

### Added

- Multi-choice library selection and filtering in the plugin settings.

## Credits

Upstream work by IAmParadox27 and MakD, with earlier influence from
BobHasNoSoul, SethBacon and TedHinklater. See the README and `LICENSE.md`.
