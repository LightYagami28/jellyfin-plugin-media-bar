# Contributing to Media Bar

Thanks for helping maintain this Jellyfin plugin. This repository is a fork of
IAmParadox27/jellyfin-plugin-media-bar, which is itself based on MakD's
Jellyfin Media Bar. The upstream license is reproduced in `LICENSE.md`.

## Where a change belongs

- Visual or behavioural problems in the media bar content come from MakD's
  project. Report those upstream and do not open an upstream pull request
  without prior approval.
- Plugin settings, packaging, deployment and fork-specific integration belong
  here.
- Read the README before changing installation instructions: it documents the
  required companion plugin and the supported Jellyfin version.

## Development setup

The plugin is a C# project under `src/Jellyfin.Plugin.MediaBar`. Use the .NET
SDK declared by the project file in that directory. From the repository root:

```sh
dotnet build src/Jellyfin.Plugin.MediaBar
```

If a test project is added, run it with `dotnet test` before opening a pull
request. Keep asset changes under `img/` and `src/` and do not commit generated
build output.

## Pull requests

- One coherent change per pull request.
- Describe the change and how you verified it, with the exact commands used.
- Preserve the upstream credits and the license notice.
- No suppressions or skipped checks to make a failing validation pass.

## Commit style

Use short subjects in the form `type: description`, with `type` chosen from
`feat`, `fix`, `docs`, `refactor`, `test` or `chore`.
