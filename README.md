# Log Begone — Silence Annoying Server Console Spam

Log Begone 9minecraft Mod removes unwanted lines from your game and server logs. It acts as a filter that catches annoying text before it ever reaches your console window or log files. The mod works on both regular client games and dedicated servers. It helps server admins read their console easier by hiding connection spam or chatty messages from other installed mods.

Total Silence: Stops matched text lines from showing up anywhere, including the console window and saved log files.

## What this build is

An unofficial rebuild of **AzureDoom**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

This build is released under **LGPL-3.0**. The complete corresponding source ships inside the downloadable file under `META-INF/sources/`, next to the original licence text.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | Fabric, fabric, NeoForge, neoforge |
| 26.2 | Fabric, fabric, NeoForge, neoforge |
| 1.21.11 | Fabric, fabric, NeoForge, neoforge |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/log-begone-9minecraft-mod](https://www.9minecraft.net/log-begone-9minecraft-mod/)

## Credits

Original work by **AzureDoom**. Port and maintenance by 9Minecraft Studios. Licensed LGPL-3.0; the upstream licence text ships inside every build.
