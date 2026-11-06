# F10 operations

## Territorial missions

Open **F10 → WARZONE MISSIONS → REQUEST MISSION TYPE**, or use **REQUEST NEW MISSION (RANDOM)**.

| Mission | Objective |
|---|---|
| CAP | Patrol friendly-controlled frontline territory. Neutral zones are not CAP objectives. |
| BARCAP | Remain airborne in the central Qayyarah / Kirkuk air corridor. |
| CAS | Neutralize the assigned enemy frontline zone. |
| SEAD | Destroy the designated enemy air-defense group. |
| STRIKE | Destroy the remaining designated strategic static targets. Sector capture is not required for the strike itself. |

CAP and BARCAP patrol progress requires the requesting player; the objective must be closed through safe return to a friendly base or carrier. Use **CURRENT MISSION** for the assigned objective and **CANCEL MISSION** to release tasking. Territorial missions use coalition-wide state; live AI target assignments below are managed separately per player group.

## AI CONTROL

Open **F10 → WARZONE MISSIONS → AI CONTROL**.

- **Status / current limits** shows player counts, the selected profile and active forces.
- **Operations tempo** offers AUTO, LOW, NORMAL, HIGH, OFFENSIVE and NEW LAUNCHES PAUSED.
- **Request AI reinforcements** requests CAP, CAS, SEAD or ground columns, subject to sector access, ownership, concurrency and available parking.
- Ground-column controls halt or resume existing columns.

Each coalition controls its own settings. Pausing stops new launches while active groups continue. Empty servers suspend new launches.

AUTO limits per coalition:

| Total human players | Combat flights | Ground columns |
|---|---:|---:|
| 1–2 | 3 | 2 |
| 3–4 | 4 | 3 |
| 5–6 | 6 | 3 |
| 7+ | 8 | 4 |

Up to one AWACS and two tankers per coalition are available in addition. Operational conditions can reduce the actual number launched.

## DYNAMIC AI TASKS

1. Open **F10 → WARZONE MISSIONS → DYNAMIC AI TASKS**.
2. Select **Refresh target list**, then an entry in **ENEMY GROUP LIST**.
3. Read **Briefing / position** and select **Accept task**.
4. Use **Active task / F10 track** for the target position and current status.

One task can be assigned per player group, and one group can claim a target. The assigned tracking marker updates every 30 seconds. Destroy all target units; a withdrawal or despawn closes the task without success. A task bonus requires at least one kill credited to the assigned group and is redeemed through safe RTB under the campaign reward rules.

## Shop and logistics

Use the personal coalition command/shop menu to purchase assets and supplies. Deploy supported ground assets to a friendly zone, or choose marker-based physical cargo delivery. Logistics provides helicopter supply, infantry and CSAR operations. MQ-9/JTAC supports enemy-zone and nearby-marker tasking.

EWRs use dedicated open emplacements for both coalitions, including saved assets. Placement requires flat terrain, a 900 m building-free buffer, runway clearance and local obstacle checks. Native mission triggers clear trees only within the selected 180 m emplacement before the radar appears. Buildings are never removed. If no valid site is available, deployment is deferred or refused. EWR cargo may use a safe site near the requested marker; the operational coordinates are announced after deployment.

## Tankers

Open **F10 → Tanker Support → Tanker status** to see which services are active.

| Coalition | Service | Aircraft | Frequency | TACAN |
|---|---|---|---|---|
| BLUE | ARCO 1-1, Erbil | KC-135MPRS, probe/drogue | 251.000 MHz | 45X |
| BLUE | TEXACO 2-1, Mosul | KC-135, boom | 254.000 MHz | 47X |
| RED | TEXACO 1-1, Balad | IL-78M | 257.000 MHz | — |
| RED | ARCO 2-1, Al Asad | IL-78M | 259.000 MHz | — |

AWACS dispatchers are based at Bashur (BLUE) and Baghdad (RED). Check in-mission support status and radio availability before requesting service.
