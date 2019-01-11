
<h1 align="center">
  <br>
  <img src="https://github.com/GameServerManagers/LinuxGSM-Docs/raw/master/.gitbook/assets/linuxgsm_colour_logo_workmark_short_384.png" alt="LinuxGSM">
  <br>
  Support
  </h1>

> Post in this repo for General support; select the [issues](https://github.com/GameServerManagers/LinuxGSM-Support) tab above.

# Getting Support Guide

We want to help out server admins as best as we can, however, time is limited and is best spent on developing LinuxGSM. Please use this guide to help yourself get the correct support.

By researching your issue, posting it in the correct place and provide the correct information you can resolve your issue faster.

## Specific Game Server Issues

If your issue is with the game server and not LinuxGSM you should check out any official game forums. We are not experts in all the game servers, so official game developer forums could provide better support for game server-specific issues. Please esee below for a list of some of the official game channels

## Search Before Posting

### Official Documentation

The LinuxGSM website and docs are full of useful information that covers most LinuxGSM topics.

* https://linuxgsm.com
* https://docs.linuxgsm.com

### Google the Issue

It is likely that someone has come across your issue already. Save yourself time by using Google to search error messages.

"Google is how I learnt and still learn to use BASH and develop LinuxGSM.” - Daniel Gibbs
https://google.com

## Update LinuxGSM

Make sure LinuxGSM is up to date. LinuxGSM is regularly updated and your problem may have already been resolved.

```
./gameserver update-lgsm
```

## Post in the Right Place

Ensure you post the issue in the correct forum.

### Recommended

* [LinuxGSM-Support Repository](https://github.com/GameServerManagers/LinuxGSM-Support) - General support.
* [LinuxGSM Repository](https://github.com/GameServerManagers/LinuxGSM/issues) - ONLY for LinuxGSM bugs, feature suggestions and code contributions.

### Other Support
* [Discord](https://linuxgsm.com/discord)
* [Steam Group](https://linuxgsm.com/steam)

There are many volunteers that may be able to help your issue.

## Post Useful Information

If you have an issue it is vital that you provide as much useful information as possible. This helps us resolve issues quicker. Without it, we simply cannot help. When posting about an issue provide the following:

### Minimum Information
Using the `./gameserver postdetails` command can provide most of the info required to assist.

If that is not available, provide details such as:
* The game server you are running (Rust, Garry's Mod).
* Your Linux distro and version (Ubuntu 18.04 x64).
* Your kernel information ( `uname -a` )
* Your versions for glibc ( `ldd --version` ) and tmux ( `tmux -V` )

The context of your error and the exact outputs.

### Additional Information
Any useful log in `/home/gameserver/log` (use pastebin or equivalent).
Any useful screenshots.
Your basic server hardware (CPU/RAM/Storage).
Any tests you have already tried.
Any relevant information you think will help.

# Official Game Support Channels

Below is a list of some of the offical and best places to get support for game servers.

- [ARK: Survival Evolved](https://survivetheark.com/index.php?/forums/forum/39-server-administration/)
- [ARMA 3](https://forums.bohemia.net/forums/forum/159-arma-3-servers-administration/)
- [Counter-Strike: Global Offensive](https://steamcommunity.com/app/730/discussions/)
- [Counter-Strike 1.6](https://steamcommunity.com/app/10/discussions/)
- [Counter-Strike: Source](https://steamcommunity.com/app/240/discussions/)
- [Day of Defeat: Source](https://steamcommunity.com/app/300/discussions/)
- [Day of Infamy](https://steamcommunity.com/app/447820/discussions/)
- [GoldenEye: Source](https://forums.geshl2.com/)
- [Garry's Mod](https://forum.facepunch.com/f/)
- [Insurgency](https://steamcommunity.com/app/222880/discussions/2/)
- [Killing Floor 2](https://forums.tripwireinteractive.com/forum/killing-floor-2/technical-support-ae/dedicated-server-support-ac)
- [Minecraft](https://www.minecraftforum.net/forums/servers-java-edition/minecraft-server-hosting)
- [Quake 3](https://steamcommunity.com/app/2200/discussions/)
- [Rust](https://forum.facepunch.com/f/)
- [Terraria](https://forums.terraria.org/index.php?forums/)
- [Team Fortress 2](https://steamcommunity.com/app/440/discussions/)
- [Teamspeak 3](https://forum.teamspeak.com/forums/93-TeamSpeak-3-Technical-Discussions-EN-DE)
- [Unreal Tournament 2004](https://www.epicgames.com/unrealtournament/forums/past-unreal-tournament-games/unreal-tournament-2003-2004)
- [Unreal Tournamnet 3](https://www.epicgames.com/unrealtournament/forums/past-unreal-tournament-games/unreal-tournament-3)
- [Unreal Tournament 99](https://www.epicgames.com/unrealtournament/forums/past-unreal-tournament-games/unreal-tournament-%E2%80%9899)
