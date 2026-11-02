# HexIDE.Localisation

Installable UI language packs for [HexIDE](https://github.com/hexide-io/HexIDE).

HexIDE follows Windows' own language tiers:

| Tier | Which languages | Where they live | Support |
|---|---|---|---|
| 1 | Every language Windows setup offers as a full language pack | In the box, in [hexide-io/HexIDE](https://github.com/hexide-io/HexIDE) | Complete: the build fails if a shipped pack misses a key |
| 2 | Every language Windows 11 offers as a Language Interface Pack (Local Experience Pack) | Here, installable | Best effort: coverage is reported, never enforced |

Microsoft's list of both tiers is [Available language packs for Windows](https://learn.microsoft.com/windows-hardware/manufacture/desktop/available-language-packs-for-windows).

## What best effort means

- A tier-2 pack may lag behind HexIDE: a key it doesn't translate yet shows in English, as it would in any pack.
- Translations are machine-assisted and reviewed for structure (keys, placeholders, access keys), not by native speakers, until one volunteers. Corrections from native speakers are very welcome.
- HexIDE marks an installed tier-2 pack as a community pack in its language picker.

## Status

HexIDE can't install a pack from here yet; that arrives with its package format. The drafts below are in `packs/`, one file per language in HexIDE's own pack format, measured against HexIDE's English pack as it stood on 2 November 2026 (949 keys). Still to come: Cherokee (`chr`, hexide-io/HexIDE#2787) and Valencian (`ca-ES-valencia`, a regional override of Catalan, hexide-io/HexIDE#2815).

| Tag | Language | Keys | Notes | Drafted in |
|---|---|---|---|---|
| `af` | Afrikaans | 949 of 949 |  | hexide-io/HexIDE#2778 |
| `am` | Amharic | 949 of 949 |  | hexide-io/HexIDE#2780 |
| `as` | Assamese | 948 of 949 | 1 key missing | hexide-io/HexIDE#2782 |
| `az-Latn` | Azerbaijani, Latin script | 949 of 949 |  | hexide-io/HexIDE#2783 |
| `be` | Belarusian | 949 of 949 |  | hexide-io/HexIDE#2784 |
| `bn` | Bangla | 949 of 949 |  | hexide-io/HexIDE#2785 |
| `bs-Latn` | Bosnian, Latin script | 949 of 949 |  | hexide-io/HexIDE#2786 |
| `cy` | Welsh | 949 of 949 |  | hexide-io/HexIDE#2816 |
| `fa` | Persian | 949 of 949 | in the box through HexIDE 0.4.0 | hexide-io/HexIDE#2817 |
| `fil` | Filipino | 949 of 949 | 68 values still read as English | hexide-io/HexIDE#2788 |
| `ga` | Irish | 949 of 949 |  | hexide-io/HexIDE#2770 |
| `gd` | Scottish Gaelic | 949 of 949 |  | hexide-io/HexIDE#2808 |
| `gu` | Gujarati | 949 of 949 |  | hexide-io/HexIDE#2790 |
| `hi` | Hindi | 949 of 949 | in the box through HexIDE 0.4.0 | hexide-io/HexIDE#2817 |
| `hy` | Armenian | 949 of 949 |  | hexide-io/HexIDE#2781 |
| `is` | Icelandic | 949 of 949 |  | hexide-io/HexIDE#2791 |
| `ka` | Georgian | 949 of 949 |  | hexide-io/HexIDE#2789 |
| `kk` | Kazakh | 949 of 949 |  | hexide-io/HexIDE#2793 |
| `km` | Khmer | 949 of 949 |  | hexide-io/HexIDE#2794 |
| `kn` | Kannada | 949 of 949 |  | hexide-io/HexIDE#2792 |
| `kok` | Konkani | 949 of 949 |  | hexide-io/HexIDE#2795 |
| `lb` | Luxembourgish | 949 of 949 |  | hexide-io/HexIDE#2797 |
| `lo` | Lao | 949 of 949 |  | hexide-io/HexIDE#2796 |
| `mi` | Maori | 949 of 949 |  | hexide-io/HexIDE#2801 |
| `mk` | Macedonian | 949 of 949 |  | hexide-io/HexIDE#2798 |
| `ml` | Malayalam | 949 of 949 |  | hexide-io/HexIDE#2800 |
| `mr` | Marathi | 949 of 949 |  | hexide-io/HexIDE#2802 |
| `ms` | Malay | 949 of 949 |  | hexide-io/HexIDE#2799 |
| `mt` | Maltese | 949 of 949 |  | hexide-io/HexIDE#2771 |
| `ne` | Nepali | 949 of 949 |  | hexide-io/HexIDE#2803 |
| `nn` | Norwegian Nynorsk | 949 of 949 |  | hexide-io/HexIDE#2804 |
| `or` | Odia | 949 of 949 |  | hexide-io/HexIDE#2805 |
| `pa` | Punjabi | 949 of 949 |  | hexide-io/HexIDE#2806 |
| `quz` | Quechua | 949 of 949 |  | hexide-io/HexIDE#2807 |
| `sq` | Albanian | 949 of 949 |  | hexide-io/HexIDE#2779 |
| `sr-Cyrl` | Serbian, Cyrillic script | 949 of 949 |  | hexide-io/HexIDE#2809 |
| `ta` | Tamil | 949 of 949 |  | hexide-io/HexIDE#2810 |
| `te` | Telugu | 949 of 949 |  | hexide-io/HexIDE#2812 |
| `tt` | Tatar | 949 of 949 |  | hexide-io/HexIDE#2811 |
| `ug` | Uyghur | 949 of 949 |  | hexide-io/HexIDE#2813 |
| `ur` | Urdu | 949 of 949 | in the box through HexIDE 0.4.0 | hexide-io/HexIDE#2817 |
| `uz-Latn` | Uzbek, Latin script | 949 of 949 |  | hexide-io/HexIDE#2814 |

## Licence

MIT, as HexIDE is.
