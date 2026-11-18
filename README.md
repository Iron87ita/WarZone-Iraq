![Banner WarZone Iraq](WarZone%20Iraq%20Banner.jpg)

# WarZone Iraq

**DCS World · Iraq · Modern dynamic sector campaign · Version 6**  
Created by **IRON87ITA**.

[Download V6](https://github.com/Iron87ita/WarZone-Iraq/raw/refs/heads/main/WarZone_IRAQ_IRON87_V6.miz) · [Changes in V6](CHANGELOG.md#v6--2026-11-18) · [Install](INSTALLATION.md) · [F10 guide](F10_GUIDE.md) · [Sector map](SECTORS.md)

WarZone Iraq brings the WarZone Caucasus campaign logic to Iraq: a persistent battlefield with **BLUE in the north**, **RED in the south** and a progressive operational front. Both coalitions can request missions, control their own AI tempo, deploy support assets and fight over the next sector.

## The battlefield

| Coalition | Starting territory | Campaign axis |
|---|---|---|
| BLUE / NATO | Mosul, Bashur, Erbil, Tal Afar and the Qayyarah / Makhmur front | **S3 → S4 → S5 → S6**, south toward Baghdad and Al Kut |
| RED / RF | Kirkuk, Sulaimaniyah, central Iraq, the Euphrates corridor and Baghdad | **S3 → S2 → S1**, north toward Mosul and Tal Afar |

**Six sectors and 43 land objectives are active from mission start.** The opening front is **S3 — Qayyarah / Kirkuk**. Secure every zone in a sector and control your coalition’s full axis to win.

Aircraft spawn and recover at friendly land bases and FARPs.

## Features

- F10 territorial missions: **CAP, BARCAP, CAS, SEAD and STRIKE**.
- Dynamic player tasks against newly spawned enemy AI groups, with target briefings and F10 tracking.
- Coalition AI controls: **AUTO, LOW, NORMAL, HIGH, OFFENSIVE**, or pause new launches.
- Requests for AI CAP, CAS, SEAD and ground columns; halt/resume column commands.
- Player-scaled AI activity, staggered air departures and up to four ground columns per coalition.
- AWACS and two tanker services per coalition; combat aircraft depart from available HOT parking.
- Personal shop, physical cargo deliveries, ground units, supplies, EWR and MQ-9/JTAC support.
- Helicopter logistics, infantry and CSAR.
- Persistent sector progress, zone ownership, wallets and surviving purchased assets.
- Original Iraqi strategic complexes, with **55 static targets** integrated into STRIKE tasking.
- Reactive CAP for both coalitions, separate flight and coalition F10 menus, and an extra 10 personal credits per eligible kill or completed task.
- English mission and coalition briefings, plus eight kneeboard pages with dedicated reactive CAP and personal credit references.

### EWR placement

Both BLUE and RED EWRs use dedicated open emplacements. The placement rules require flat land, no scenery buildings within **900 m**, runway clearance and local obstacle checks. Native DCS triggers clear trees only within the selected **180 m** emplacement before creating the radar; buildings are preserved. The rule covers automatic radars, F10 purchases and restored saved EWRs. If no suitable emplacement is available, deployment is deferred or refused. Marker-delivered EWRs use a nearby safe emplacement and report their operational coordinates.

## Quick start

1. Install DCS World, the **Iraq terrain** and the unit mods used by this mission. See [requirements](INSTALLATION.md#requirements).
2. Download [WarZone_IRAQ_IRON87_V6.miz](https://github.com/Iron87ita/WarZone-Iraq/raw/refs/heads/main/WarZone_IRAQ_IRON87_V6.miz) and copy it to your DCS `Missions` folder.
3. Open it in DCS or add it to your dedicated server mission list.
4. Join a coalition and open **F10 → WarZone - Flight → 01 Missions**.

The V6 mission uses the Modern configuration.

## Persistence

With mission file access available, the campaign uses:

```text
Saved Games\DCS\Missions\Saves\Modern\WarZone_IRAQ_MODERN_NORTH_BLUE_SOUTH_RED.lua
```

The actual DCS profile folder may be `DCS`, `DCS.openbeta` or a dedicated-server profile. Back up an existing save before replacing the mission. AI tempo settings and live AI task assignments apply to the current session. See [installation and saves](INSTALLATION.md).

## Package status

K1 AP is the 43rd campaign objective. It starts RED at level 1 in sector S3 and is linked to Kirkuk. See the [English changelog](CHANGELOG.md#v6--2026-11-18) for the F10, reactive CAP, reward and briefing changes.

## Credits and feedback

Campaign and artwork supplied by **IRON87ITA**. Embedded community frameworks retain their original attribution and terms; see [CREDITS.md](CREDITS.md). Report problems through this repository's **Issues**, including the mission version, coalition, relevant sector and a description of what happened.
