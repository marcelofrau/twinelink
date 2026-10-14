# AGENTS.md - twinelink (meta repository)

Coordination superproject. No source lives here except this file and the
submodule pins. Do not add code to this repo.

## Submodules
- `desktop/` -> twinelink-desktop (C++/Qt6, fork of KDE/kdeconnect-kde)
- `android/` -> twinelink-android (Kotlin/Compose, fork of KDE/kdeconnect-android)
- `docs/`    -> twinelink-docs (project home + OpenSpec store)

## Clone
```
git clone --recurse-submodules https://github.com/marcelofrau/twinelink.git
```

## OpenSpec
```
openspec store register docs
openspec workset open twinelink
```
## Working rules (all twinelink repositories)
- Everything committed is in English (docs, code, comments, commits, PRs).
  The maintainer chats in Portuguese and uses a terse, compressed style.
- OpenSpec-first: every feature/fix is an OpenSpec change (proposal, specs,
  design, tasks) approved before code is written.
- Branches `feat|fix|chore`; Conventional Commits; SOLID; unit tests for new logic.
- Lint/format/static analysis per language; CI must stay green.
- Do NOT rename KDE Connect protocol identifiers (`kdeconnect.*`), the config
  directory or the DBus service (interop with stock KDE Connect).
- No performance claim without a measurement method.
