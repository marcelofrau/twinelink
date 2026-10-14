# Twine

Meta repository for **Twine** - an open-source cross-device link with remote
desktop (RDP) and Wake-on-LAN. A hard fork of KDE Connect, Windows-first.

> Twine links your devices. Connect your phone and computer(s): remote desktop,
> wake a sleeping PC, share files and clipboard, mirror notifications.

## Contents (submodules)

| Path | Repository | Role |
| --- | --- | --- |
| `desktop/` | [twinelink-desktop](https://github.com/marcelofrau/twinelink-desktop) | Windows-first desktop client (C++ / Qt6) |
| `android/` | [twinelink-android](https://github.com/marcelofrau/twinelink-android) | Android app (Kotlin / Compose) |
| `docs/` | [twinelink-docs](https://github.com/marcelofrau/twinelink-docs) | Documentation, architecture, requirements, OpenSpec store |

## Quick start

```bash
git clone --recurse-submodules https://github.com/marcelofrau/twinelink.git
cd twinelink
git submodule update --init --recursive
```

Then read the documentation at `docs/`, starting with the
[architecture overview](docs/docs/architecture/overview.md) and the
[roadmap](docs/docs/plan/roadmap.md).

## Where to start

- New here? Read `docs/CONTRIBUTING.md`.
- Designing a feature? Every change is an OpenSpec change (proposal, specs,
  design, tasks) in the repository it modifies.
- Everything committed is in **English**.

## License

Code: GPL-2.0-or-later. Docs: CC BY 4.0. See `docs/LICENSE.md`.
