---
title: Issues & FAQ
description: Troubleshooting common issues and bugs.
---

If you are experiencing issues with the game, please check the following list of common issues and solutions. If you are unable to find a solution to your problem, please ask for help in the [Discord Server](https://kdx.nightcord.com.de/general/community) or [Telegram Group](https://kdx.nightcord.com.de/general/community).

## Known Issues

Below are some existing issues that are currently being worked on:

1. Importing assets other than A000 cause a black screen.
2. Some areas may cause the game to crash.
3. Camera may crash on some devices (You can disable camera permissions for now).

## Frequently Asked Questions

**Q: It says dummy.dat, DX_title.dat, or KALEID_BG_240412.dat is missing**

> A: These files are part of the NoVideo torrent. If you are using your own assets and want to delete MovieData, you need to make sure these three files are preserved. If you already transferred the other files, please copy these three files from the NoVideo torrent to the `StreamingAssets/A000/MovieData` folder.

**Q: It says `tree.csv` is missing.**

> A: If you insist on using your own assets, you need to create the `tree.csv` by running [this Python script](/misc/scripts/tree.py) in the `StreamingAssets` folder.

**Q: The game says cannot find A000 even though I've already transferred the assets.**

> A: If you manually transferred the assets instead of using the in-game downloader, you need to manually create a file named `FinishedDownload` in the `StreamingAssets` folder.

**Q: Whenever the game tries to take a picture after I finish the song, the game crashes!**

> A: Disable camera permissions by going into Settings > Apps and Notifications (or Apps, depending on your device maker and ROM) > searching "KanadeDX" and going to "Permissions". Set the Camera permissions to "Don't allow".

**Q: On iOS devices, if I go to a specific area/song/character, it crashes!**

> A: This issue is slowly being resolved and seems to only be a problem on iOS. Try avoiding whatever is making your game crash, or check if you added any unlock flags on your profile that you shouldn't have in AquaDX or your chosen server.

**Q: If I've originally installed the "NoVideo" version of the assets, would it damage anything if I installed the video data over it?**

> A: This isn't particularly tested yet, but it is recommended to redownload from Miniserve (MAKE SURE YOU HAVE ENOUGH FREE SPACE!) to prevent any data corruption. Make sure to also reinitialize your assets for KanadeDX to use in the settings menu.

**Q: How do I change my keychip to save my gameplay on leaderboards?**

> KanadeDX uses a placeholder/dummy keychip to make the game boot with basic necessities and not save any play data, so once you have registered for AquaDX (https://aquadx.net/), go to "Setup Connection", confirm, and copy the keychip number listed (should be something like A###-###########, with the hashtags being randomized numbers or letters.)
> 
> Then, go back to KanadeDX, click the gear icon, and scroll down to "Keychip" (or SeriID in older versions) and paste your keychip ID there.
> 
> DO NOT SHARE YOUR KEYCHIP (or card number) WITH OTHERS! IT IS FOR YOURSELF ONLY AND MAY LEAD TO DAMAGES OR TAMPERED SCORES IF SHARED.

**Q: How do I rotate the game to Portrait orientation for phones?**

> A: Please update to version Canary 250227.0222 or later.

**Q: It crashes when I try to search for the Access Code for my Aime in-game!**

> A: Please update to version Canary 250227.0222 or later.
