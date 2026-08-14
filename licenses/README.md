# Canonical License Texts

These are the source-of-truth license bodies for every [@willtheorangeguy](https://github.com/willtheorangeguy) repository. Each repo carries its own `LICENSE.md` at the root — GitHub only detects a license from the repository itself, so these files are the master copies that get written out, not a replacement for them.

| File | SPDX | Applies to |
| ---- | ---- | ---------- |
| [`MIT.md`](MIT.md) | `MIT` | Code repositories — CLIs, packages, apps, services, scripts, static sites |
| [`CC-BY-4.0.md`](CC-BY-4.0.md) | `CC-BY-4.0` | Content repositories — data sets, notes, archives, written material |

## Canonical Copyright Line

```text
Copyright © 2026 willtheorangeguy
```

Use this exact string. Not `William`, not `William Vandergraaf`, not `(c)`, not a year range.

## Exceptions

These repositories deliberately do **not** use the texts above. Do not normalize them:

| Repository | License | Reason |
| ---------- | ------- | ------ |
| `Chrome-File-Directory` | BSD-2-Clause | Vendored from Chromium; upstream terms |
| `Nginx-File-Directory` | BSD-2-Clause | Vendored from Nginx; upstream terms |
| `Apache-File-Directory` | Apache-2.0 | Upstream terms |
| `stacktower-docker` | Apache-2.0 | Upstream terms |
| `whisper-captions` | MIT, Miguel Piedrafita | Fork; upstream copyright retained |
| `*-Transcripts` | MIT + provenance notice | Code is MIT; transcript text is a derivative of third-party recorded speech and is not ours to relicense |

## Filename

Always `LICENSE.md`, never extensionless `LICENSE`. GitHub detects both, but one convention means one template.
