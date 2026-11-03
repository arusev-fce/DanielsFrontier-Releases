# Daniel's Frontier

### Over and Beyond the Unknown

An original space-combat and exploration game about outfitting your own ship, leaving safe space and discovering what lies beyond the next jump gate.

Fly 3D ships from an angled overhead view. Pick encounters, fight alien threats, collect salvage and return to a station to improve your loadout. The goal is a satisfying journey from a modest starter ship toward a capable fleet, with choices in speed, protection, weapons and drones.

## Download

**[Download the latest Windows build](https://github.com/arusev-fce/DanielsFrontier-Releases/releases/latest/download/DanielsFrontier-Windows.zip)** · [Release notes and older versions](https://github.com/arusev-fce/DanielsFrontier-Releases/releases)

1. Download `DanielsFrontier-Windows.zip`.
2. Extract the entire ZIP into a folder.
3. Run `DanielsFrontier.exe`. Keep the updater and accompanying files beside it.

This is an early test build. Windows desktop is the current target; controls, visuals and balance are evolving.

## What you can try

- **Explore linked sectors:** Home Sector and Verdant Rift have different encounters and linked jump gates, with protected areas around stations/gates.
- **Build your ship:** equip lasers, rockets, shields, engines, utilities and drones. Larger hulls offer more equipment options.
- **Fight and progress:** earn rewards, collect salvage, develop skills and try equipment tiers and drone formations.
- **Make the interface yours:** move/resize HUD panels, navigate with the minimap/atlas and customize the hotbar.
- **Choose how to play:** local offline pilots or the current private online universe.

v0.5.1 adds continuous online player movement with gradual server corrections, an FPS/frame-time/ping display, a textured salvage container and generated title artwork. Internet movement feel and laptop touchpad behavior still need testing; faster downloads are planned.

## Offline or online?

**Offline** uses profiles saved on your PC.

**Online** uses a separate game account and server-owned progression. Existing players choose **Sign in** with their game-account email/password. A private invitation is required only to create a new account. Downloading this public client does not let someone freely register on the private server. Website access and game login are separate.

Offline progress does not transfer into online accounts. Public builds do not provide admin grant commands. No payment system is implemented.

## Updates

Use **Check for updates** in the main menu. v0.5.0 and later include the update workflow; older clients need a complete manual download once.

The game verifies the official download's size and SHA-256 checksum. `FrontierUpdater.exe` waits for the game to close, backs up managed files, installs the update and restarts the game. Local saves remain separate. A complete real-world update cycle remains part of test acceptance.

## The frontier ahead

The long-term vision is a persistent shared PvE universe where friends can hunt, explore and eventually quest together. Plans include a three-sector backbone, procedural portal expeditions, changing sector modifiers and community proposals/voting.

Those are future intentions. Full party/group mechanics, a developed questline and the wider universe are not implemented yet. Current work prioritizes movement, combat readability, UI quality, progression and reliable testing.

## Free-to-play and future open source

The intended direction is **free-to-play and eventually open source**. Test builds are free to download and play. The source repository is currently private and no project-wide open-source license has been selected.

Code, artistic content and branding will have documented licensing boundaries before the source opens. Public availability of these binaries is not a blanket license to reuse code, art or the game name. Godot and bundled dependencies keep their existing terms. Future open-source availability will not expose player data, credentials or private server configuration.

This repository distributes runtime releases and player documentation only. It contains no game-server database, private registration codes or email-service credentials.
