<div align="center">

![Daniel's Frontier : original game-inspired banner](assets/frontier-banner.png)

# Daniel's Frontier

**Current public release: v0.9.4.1** : Windows desktop

[Download the complete game](https://github.com/arusev-fce/DanielsFrontier-Releases/releases/latest/download/DanielsFrontier-Windows.zip) : [Latest patch notes](https://github.com/arusev-fce/DanielsFrontier-Releases/releases/latest)

</div>

Pilot a ship through a persistent shared universe. Fight hostile fleets, travel through portals, mine resources and build equipment that changes how your ship plays.

![Combat, exploration and ship-building banner](assets/frontier-mechanics.png)

## 0.9.4.1 : Equipment art and save hotfix

- New approved equipment, ship, shop-category and skin-theme artwork. Shared icons now appear in shop, inventory, crafting, rewards, hangar and encyclopedia.
- Larger artwork within existing shop slots, with preserved proportions and unchanged button sizes.
- Devices display their actual rarity frames. Existing item names are retained.
- Completion and level-up cues take priority over routine notifications; chat and crafting no longer interrupt each other through one shared voice.
- Portal reward receipts clone with less serialization and allocation while preserving full history and transaction isolation.
- Corrected Arclight guns and preserved faction finishes and weapon origins.
- Unfinished specialist hulls and drones are unavailable for new acquisition. Existing ownership, fitted equipment and saved research are preserved.
- Fixed portal construction checks and exact payment. Missing materials block construction; repeated requests do not charge twice.
- Device crafting tiers now reflect their costs: Defabricator Epic; Cloak and Shield Burst Legendary; Jump Drive Mythic. Costs and ability timings are unchanged.
- Standard 1-Key chests are Epic; Reinforced 2-Key chests are Legendary. Contents odds and key prices are unchanged. Chest tooltips no longer imply an equipment-level requirement for opening.
- Improved nearby enemy weapon sound admission without crowding player fire or changing the approved samples and music.
- Device-ownership quest requirements now reflect legal acquisition levels while preserving existing ownership and earned access.
- Updated level-120 guidance, all seven region entries, device-slot hints and equipment-set availability. Existing encyclopedia search remains available.
- Reduced redundant save writes, corrected retry ordering and improved save diagnostics while preserving durable commits and backups.
- Expedition panels close safely when their player session ends.


## 0.9.4 : Outer Reach and pilot progression

- Explore Sinter Glassworks, Pelagic Shoal and Disputed Meridian, with eight new PvE enemies and regional equipment/materials.
- Pilot progression now spans 120 levels, with level-based access for new progression while preserving existing equipment and earned unlocks.
- Workshop Projects introduce event research, specialist hull crafting and two Epic equipment sets. Specialist hulls currently use existing-model comparators; replacement art is deferred.
- Salvage Frontier adds a Home-sector branch with salvage activities and component rewards.
- Seven existing player ships receive revised hardware, faction finishes and fitted crests.
- Mining areas, ore markers and legacy miner recovery are corrected.
- Devices have dedicated ship-scaled slots below Drones, with existing devices preserved during migration.
- Disputed Meridian branches from Ember Reach; scattered ore sites retain their IDs and investments.
- Levels, stars and refinement require their exact resources; multi-item payments and stock displays are corrected.
- Server roster preparation and threaded model-load shutdown are corrected.


## 0.9.3.4 : Progression and expedition update

- Smoother portal progression: 10-second preparation, one 6-9-second cleared-wave interval, gradual opening rosters and limited reinforcement overlap.
- Revised Normal, Hard and Elite combat budgets. Station defenders return to their objective instead of acquiring a map-wide chase radius; Normal/Hard guardians are less punishing.
- Convoy ships travel together, respond to weapon status effects and have real shields. One movable, minimizable event panel shows the four ships. Surviving shields recover between cleared waves.
- Updated Research, relay, checkpoint and arrival-rift hardware with event lifecycle effects. Combat surfaces and objective resources are prepared before first contact.
- Clearer main-map enemy tiers and smaller ordinary-to-miniboss/boss progression cliffs. Four early new-map encounters use damage objectives before later kill goals.
- Boss Disarm immunity, shorter resisted miniboss interruption and boss slow/shred resistance. Focus and kill-follow-up bonuses reduced without resetting invested skills.
- Revised regional portal entry costs, proportional stabilizer baskets and completion material caches. Each paid gate conserves its reward budget across attempts; most kill Credits are earned on successful completion.
- Regional mining development, revised ten-level fees and once-per-level engineering with cheaper repeat installation materials. Ore buffers pause prospective production and accommodate active gathering goals.
- Workshop upgrades can use owned regional substitutes and limited paid basic supplies. Bulk quotes consume simulated stock correctly and recovery records only physical investment.
- Three optional, expensive advanced-material synthesis recipes unlock through regional visits and prior successful expeditions. Existing helper completions count.
- Remove 29 mandatory Main-story deadlines; preserve objective quantities, quest rewards, Daily/Weekly deadlines and recorded history.
- Targeted future boss/miniboss Credit adjustments. Existing wallets, equipment, stored ore, mining investments, quest histories, skill points and saved layouts remain intact.

- Update compatibility: fix SHA256SUMS.txt collisions when updating older installations. Checksums are published beside the ZIP; game binaries and server version are unchanged.

## 0.9.3.3 : Fleet and reliability hotfix

- All 15 accepted Salvage, Ember and Rift mobs receive their reviewed structural refinements, retaining their baked finish and existing combat rules.
- All seven approved player ships receive corrected UV routing and cleaned geometry.
- Compatible ship meshes are combined to reduce rendering overhead in groups.
- Faction crests remain conditional; existing ship sizes and physical firing points are preserved.
- Session, portal, equipment and reward handling cleaned up without economy changes.
- Private maintenance archives closed server logs and rotates audit receipts without deleting history.
- Existing pilots, progression, settings and HUD layouts are preserved.

## 0.9.3.2 : Music and interface hotfix

- Add Cyberpunk Renaissance, Goliath and Escape Velocity to the approved music roster.
- Choose Adaptive, Chill, Battle or a custom ordered playlist. Six-second crossfades keep music continuous.
- Energy Crossing portal audio, a dedicated level-up cue, unified chat/group cues and Epic-or-better loot notifications.
- Other players can see drone trails; Workshop Escape works across crafting pages and recovery.
- Softened thruster audio responds to acceleration and turns, controlled by Effects volume.
- Distinct chat, Epic, Legendary and Mythic cues; clearer quest and level notifications.
- Repeated critical-hull heartbeat below 10 percent health.
- Fix Escape on Expeditions and Workshop; preserve window positions.
- Extend audio sliders, show the playing track, and remove floating internal enemy phase labels.
- Preserve existing music, startup music at 10 percent, saves and saved HUD layouts.
- Music credits and licenses remain in ESC Help & info / Credits and packaged notices.

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
