# awe

**Text it, and it does it.**

awe is a sidekick for your computer that you text. Ask for something, and it
gets it done on your own computer, with your memory and your apps, and it asks
before anything that matters.

## Install

macOS and Linux:

```sh
curl -fsSL https://awe.run/install.sh | bash
```

Windows (PowerShell):

```powershell
irm https://awe.run/install.ps1 | iex
```

The installer picks the right download for your computer from
[download.awe.run](https://download.awe.run), checks it against the published
`SHA256SUMS`, and refuses anything that does not match.

## What is here

Each [release](../../releases) carries the ready-to-run bundles for macOS
(Apple silicon and Intel), Linux (x64 and arm64) and Windows (x64), with a
`SHA256SUMS` file. The same files are served from download.awe.run.

## License

The awe programs in these bundles are licensed under the awe End User License
Agreement (included in every bundle as `EULA.md`). Open-source parts carry their
own licenses. Copyright 2026 Awe Labs Inc.

Questions: hello@awe.run · Security: security@awe.run
