# Security Policy

## Supported Versions

Security fixes are applied to the tip of `main` in this fork.

| Version | Supported |
| --- | --- |
| `main` (this fork) | :white_check_mark: |
| Older plugin builds | :x: |
| Upstream IAmParadox27/jellyfin-plugin-media-bar | :x: (report here first) |

The plugin injects content into Jellyfin web pages, so reports about script
injection, unsafe Document Object Model (DOM) handling or unexpected network
requests are especially important.

## Reporting a Vulnerability

Do not open a public issue for a security problem. Use the private vulnerability
reporting form in this repository's Security tab and include:

- the plugin build and Jellyfin version you tested;
- the affected file or setting;
- reproduction steps and a proof of concept, if available;
- the impact on the server or on connected clients.

You should receive an acknowledgement within five working days. We will keep
the report private, work on a fix in this fork and coordinate disclosure with
you.

Issues in the injected bar itself originate from MakD's project. We will handle
the fork-side fix first. Once the fix is available on the `main` branch of this
fork, we will relay the details privately to the upstream maintainers. Do not
open pull requests against upstream without written approval from the
maintainers of this fork.
