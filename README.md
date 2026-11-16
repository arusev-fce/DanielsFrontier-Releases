<div align="center">

![Daniel's Frontier : original game-inspired banner](assets/frontier-banner.png)

# Daniel's Frontier

**Current public release: v0.9.3** : Windows desktop

[Download the complete game](https://github.com/arusev-fce/DanielsFrontier-Releases/releases/latest/download/DanielsFrontier-Windows.zip) : [Latest patch notes](https://github.com/arusev-fce/DanielsFrontier-Releases/releases/latest)

</div>

Pilot a ship through a persistent shared universe. Fight hostile fleets, travel through portals, mine resources and build equipment that changes how your ship plays.

![Combat, exploration and ship-building banner](assets/frontier-mechanics.png)

## 0.9.3: Audio and multiplayer polish

- Cache player nameplate bounds and reuse remote faction/rank presentation to reduce nearby-player rendering work.
- Close Expeditions, Workshop and device menus on disconnect/logout.
- Remove the internal Engage combat label.
- Add Daily and Weekly reset countdowns with exact reset times in the player device timezone.
- Remove the online flight/combat sentence from ESC; use shared body typography for actions.
- Add four approved adaptive music tracks, starting at 10 percent each launch, with author credits.
- Add selected laser, rocket, impact, explosion, thruster, crafting, quest, loot, chat/group and low-health effects.
- Add approved portal charge, continuous transit and softened arrival release; prevent the visual transition from cutting the tail.
- Include gate playback in combat ducking; preserve bounded voices and stale-event rejection.
- Add Sound settings: master, music, effects and ambience levels and enable switches, music mode and audio defaults.
- Preserve audio preferences and shared checkbox sizing/text scaling.
- Include the movable welcome-back quest reminder and its minimize/Esc behavior from the pending UI fixes.
- Automatically confirm initial main-screen server health on a warmed connection instead of retaining connection-startup latency as its status color.

Existing saves, equipment and UI layouts are preserved. Client, server and admin console are updated together.

Known issue: the reported large combat hitch was not reproduced in bounded profiling; these improvements do not establish that every combat stall is eliminated.

Existing pilots, ships, equipment and earned progress are preserved. Matching client, server and private admin-console packages accompany this release.

## The game

| Combat | Exploration | Build your ship |
| --- | --- | --- |
Fight with lasers, rockets and drones. Watch hull and shield damage as encounters unfold. | Cross sector portals, discover stations and gather ores and supplies. | Equip weapons, generators, utilities and drones. Craft and improve gear using materials you earn. |

Choose a faction, grow your pilot and use the in-game encyclopedia and tutorial to learn the systems. Group expeditions offer shared objectives alongside ordinary sector play.

## Get started

1. Download the [latest Windows ZIP](https://github.com/arusev-fce/DanielsFrontier-Releases/releases/latest/download/DanielsFrontier-Windows.zip).
2. Extract the entire ZIP to a writable folder and run `DanielsFrontier.exe`.
3. Sign in with your pilot account. Use **Check for updates** in game for later releases.

Keep your pilot/save files when updating. Game downloads are public; registration is private and requires an invitation.

The banners above are original illustrations of the game's themes, not gameplay screenshots. Source code, server and owner tools remain private. Daniel's Frontier is proprietary; bundled third-party notices apply. No source-code or asset-reuse licence is granted.

## 0.8.9.11 - Smoother online play and reliable expeditions

- Reduced snapshot traffic and improved server save scheduling.
- More consistent online events, reconnects and combat updates.
- Fixed escort completion, extraction and expedition Aurum/Honor rewards.
- Clearer Statistics, encyclopedia guidance and material icons for batch disassembly.

Existing pilots, equipment and wallets are preserved.
