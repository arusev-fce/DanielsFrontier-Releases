# Daniel's Frontier — Technology and Third-Party Notice

Version 0.8.2 - 6 November 2026

## Software and services

Daniel's Frontier is developed primarily in C# with Godot's scene, resource,
rendering and UI systems. The Windows release uses these runtime components:

| Component | Role |
| --- | --- |
| Godot .NET 4.7.2 and GodotSharp | Game engine and managed engine interface |
| .NET 8.0.32 | Client/updater runtime components |
| Microsoft.Web.WebView2 SDK 1.0.4314.35 | Embedded registration verification; the Evergreen browser runtime is installed/updated separately |
| ASP.NET Core / .NET 10.0.13 | Dedicated server |
| Microsoft.Data.Sqlite.Core 10.0.10, SQLitePCLRaw 3.0.5 and SQLite 3.53.4 | Server persistence |

The dedicated server and owner administration tools are separate from the
public client. Their presence in this notice does not mean they are bundled
with the game or available to other players.

Cloudflare supplies network protection/tunnel and Turnstile verification.
Resend delivers account-recovery email. GitHub hosts official client releases
and update metadata. Microsoft supplies WebView2. Contact mail uses the
providers described in the [Privacy Notice](PRIVACY_NOTICE.md).

## Development and ownership

GDScript and shaders support presentation and development checks. Blender is
used for editable art; Python and PowerShell support art automation, testing
and packaging. Git/GitHub support versioning and distribution. Development
tools are not all installed on a player's device or included in the client.

AI tools have assisted coding, research and creative work under human design
and review. The game does not contain a generative-AI player chatbot, and its
runtime does not upload player records to an AI service for model training.

Original game code and creative content remain proprietary to their respective
rights holders. Third-party components retain their own licence terms. Godot's
MIT licence does not make the game's proprietary source open source.

## Licence texts

See LICENSE.txt, THIRD_PARTY_NOTICES.txt and the accompanying
Licenses/Dependencies directory for the applicable texts and attributions.
These notices cover the actual component versions in this release. Third-party
licences do not grant reuse rights in unrelated proprietary game code or art.

Official distribution: [Daniel's Frontier releases](https://github.com/arusev-fce/DanielsFrontier-Releases/releases).
