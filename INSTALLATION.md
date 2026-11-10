# Installation and campaign saves

## Requirements

- DCS World and access to the **Iraq terrain**.
- Flyable modules for the aircraft you intend to use.
- Unit mods that provide the custom types embedded in the mission templates. The supplied mission references:

```text
CHAP_9K720_HE
CHAP_BMPT
CHAP_M1083
CHAP_M1130
CHAP_M142_ATACMS_M48
CHAP_T90M
M1A2C_SEP_V3
```

These mod packages are not bundled with the repository. Use the compatible unit packs required by these types on the server and on clients where required by those packs. This package does not establish a minimum DCS build or a verified mod-version matrix.

MOOSE, MIST and the campaign's supporting scripts are already embedded in the `.miz`; they do not need separate mission-editor loading.

## Install

1. Download `WarZone_IRAQ_IRON87_V3.0.1.miz`.
2. Copy it into the `Missions` directory of your DCS Saved Games profile.
3. Open it in DCS or add it to the dedicated server mission list.
4. Join an aircraft slot or use the available dynamic aircraft interface at a friendly base. Open **F10 → WARZONE MISSIONS** after joining.

The mission uses the Modern configuration. The northern network begins BLUE; Kirkuk, Sulaimaniyah and the southern network begin RED. Some original slots have been reassigned to match the territory in which they are placed: Ka-50 Eagle and Haditha are RED; MiG-29A Mosul and the former RED Delta Ka-50 are BLUE.

## Persistence

The embedded campaign keeps its dedicated internal filename:

```text
Missions\Saves\Modern\WarZone_IRAQ_MODERN_V448_NORTH_BLUE_SOUTH_RED.lua
```

The path is relative to the active DCS Saved Games profile. Persistent saving requires the mission scripting environment to provide the file access used by the campaign (`lfs` and `io`). This repository does not modify your DCS installation or server configuration.

For an ongoing campaign, stop the mission and back up the save before replacing the `.miz`. Keep the existing compatible Iraq save to continue. To start a fresh campaign, stop the mission and move that save to a backup location before restarting. Caucasus campaign saves use a different configuration and should not be substituted.

Zone ownership, sector progress, wallets and surviving shop assets are persistent. AI tempo selections and live AI task assignments are session state. Saved EWRs are redeployed through the open-emplacement placement rules.

## Package integrity

`SHA256SUMS.txt` contains checksums for the exact supplied `.miz` and banner. Verify the downloaded package against the checksum for its version.
