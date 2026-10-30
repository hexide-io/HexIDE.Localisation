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

The packs are being drafted now. HexIDE does not yet have a way to install a pack from here; that arrives with its package format.

## Licence

MIT, as HexIDE is.
