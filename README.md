# Operator Mono fonts

Private collection of 32 Operator Mono font files with corrected weight metadata.

| Directory | Files | Variant |
| --- | ---: | --- |
| `fonts/OperatorMono` | 10 | Original Operator Mono |
| `fonts/OperatorMonoLig` | 4 | Ligature variant |
| `fonts/OperatorMonoNF` | 10 | Nerd Font Mono TTF |
| `fonts/OperatorMonoSSm` | 8 | ScreenSmart |

## Weight metadata

| Style | Corrected `OS/2.usWeightClass` |
| --- | ---: |
| ExtraLight / XLight | 200 |
| Light | 300 |
| Book / Regular / Italic | 400 |
| Medium | 500 |
| Bold | 700 |

Italic counterparts use the same weight as their upright styles. Files with
already-correct weights are retained unchanged. Corrections affect only the
weight value and related checksums; glyph outlines, names, ligatures, and other
font table data are preserved.

## Installation

Install the desired files using Font Book on macOS. Avoid enabling an older
copy with the same font name. After replacing fonts, fully quit and reopen Xcode
so it reloads the font data.

`fonts-manifest.json` records each file's PostScript name, family, weight, and
SHA-256 checksum. Original backups are kept locally and are not included here.

## Rights

The fonts retain their original copyrights and licenses, including the embedded
Hoefler & Co. notices. This repository grants no additional font usage or
redistribution rights. Use remains subject to the applicable authorization.
The repository is private, as requested by its owner, who confirmed authorization
to upload these fonts.
