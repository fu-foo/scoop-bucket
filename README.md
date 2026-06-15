# fu-foo/scoop-bucket

[Scoop](https://scoop.sh) bucket for [fhir-sazare](https://github.com/fu-foo/fhir-sazare) —
a single-binary FHIR R4 server, the easiest way to run FHIR locally.

```powershell
scoop bucket add fu-foo https://github.com/fu-foo/scoop-bucket
scoop install sazare
sazare-server --demo --open
```

Installing through Scoop also avoids the Windows SmartScreen "Windows protected
your PC" warning you get from a raw browser download: Scoop doesn't tag its
downloads with the Mark-of-the-Web, so `sazare-server.exe` just runs.

The manifest tracks the latest [release](https://github.com/fu-foo/fhir-sazare/releases)
and is refreshed automatically by a daily workflow.
