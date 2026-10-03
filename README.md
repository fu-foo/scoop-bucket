# fu-foo/scoop-bucket

A [Scoop](https://scoop.sh) bucket.

```powershell
scoop bucket add fu-foo https://github.com/fu-foo/scoop-bucket
scoop install sazare          # single-binary FHIR R4 server
scoop install fugantt         # Gantt chart: plan against actual
scoop install fuwinlauncher   # keyboard-driven app launcher
scoop install fuashiato       # records the footprints of your own work
```

[fhir-sazare](https://github.com/fu-foo/fhir-sazare) — the easiest way to run
FHIR locally.
[fugantt](https://github.com/fu-foo/fugantt) — plan against actual, counted in
working days.
[FuWinLauncher](https://github.com/fu-foo/FuWinLauncher) — lightweight
keyboard-driven app launcher. `config.ini` and `skins/` are kept in Scoop's
persist folder, so they survive updates.
[FuAshiAto](https://github.com/fu-foo/FuAshiAto) — records which window was in
front and when there was no input, to local log files. The logs are kept in
Scoop's persist folder, and the running recorder is stopped before an update.

Installing through Scoop also avoids the Windows SmartScreen "Windows protected
your PC" warning you get from a raw browser download: Scoop doesn't tag its
downloads with the Mark-of-the-Web, so `sazare-server.exe` just runs.

Each manifest tracks its project's latest release and is refreshed
automatically by a daily workflow.
