# fu-foo/scoop-bucket

A [Scoop](https://scoop.sh) bucket.

```powershell
scoop bucket add fu-foo https://github.com/fu-foo/scoop-bucket
scoop install sazare     # single-binary FHIR R4 server
scoop install fugantt    # Gantt chart: plan against actual
```

[fhir-sazare](https://github.com/fu-foo/fhir-sazare) — the easiest way to run
FHIR locally.
[fugantt](https://github.com/fu-foo/fugantt) — plan against actual, counted in
working days.

Installing through Scoop also avoids the Windows SmartScreen "Windows protected
your PC" warning you get from a raw browser download: Scoop doesn't tag its
downloads with the Mark-of-the-Web, so `sazare-server.exe` just runs.

The manifest tracks the latest [release](https://github.com/fu-foo/fhir-sazare/releases)
and is refreshed automatically by a daily workflow.
