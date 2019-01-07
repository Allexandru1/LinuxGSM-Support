
<h1 align="center">
  <br>
  <img src="https://github.com/GameServerManagers/LinuxGSM-Docs/raw/master/.gitbook/assets/linuxgsm_colour_logo_workmark_short_384.png" alt="LinuxGSM">
  <br>
  Support
  </h1>
  
# Getting Support Guide

We want to help out server admins as best as we can, however, our time is limited and is best spent on developing LinuxGSM. Please use this guide to help yourself get the correct support.

Help us by researching your issue, posting it in the correct place and provide the correct information to help us to resolve your issue.

## Specific Game Server Issues

If your issue is with the game server and not LinuxGSM you should check out any official game forums. We are not experts in all the game servers, so official game developer forums could provide better support for game server-specific issues.

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
* [LinuxGSM Repository](https://github.com/GameServerManagers/LinuxGSM/issues) - ONLY for LinuxGSM bugs, feature suggestions and code contributions.
* [LinuxGSM-Support Repository](https://github.com/GameServerManagers/LinuxGSM-Support) - General support.

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
* Your Linux distro and version (Ubuntu 16.04 x64).
* Your kernel information ( `uname -a` )
* Your versions for glibc ( `ldd --version` ) and tmux ( `tmux -V` )

The context of your error and the exact outputs.

### Additional Information
Any useful log in `/home/gameserver/log` (use pastebin or equivalent).
Any useful screenshots.
Your basic server hardware (CPU/RAM/Storage).
Any test you have already tried.
Any relevant information you think will help.
