---
title: Setup
description: Setting up the game for the first time.
---

## 1. Obtaining Assets

To obtain game asset files, you can visit the files channel on either the [Telegram Group](https://kdx.nightcord.com.de/general/community) or [Discord Server](https://kdx.nightcord.com.de/general/community). This guide assumes that you have already obtained the files.

## 2. Transferring Assets

The game assets are separate from the program itself. After you downloaded the torrent containing game assets, you should do the following:

1. Start miniserve in StreamingAssets
    - **Windows**: Click on `StreamingAssets/miniserve.exe` and wait 3s.
    - **Mac**: Download the correct file from [GitHub Releases](https://github.com/svenstaro/miniserve/releases/tag/v0.29.0) depending on your system:
        - "aarch64-apple-darwin" if you have a M-series CPU.
        - "x86_64-apple-darwin" if you have an Intel CPU.

        Then, copy it to `StreamingAssets`, open a terminal in `StreamingAssets`, and type:

        ```bash
        chmod +x ./miniserve* && ./miniserve* .
        ```

    - **Linux**: [You know what to do.](https://www.youtube.com/watch?v=FOrineGipnw)
2. Enter the download url in game. It should look something like `http://192.168.1.123:8080`. You can find the ip address of your computer in wifi settings. (This is not the same as your public IP address, and it will most likely start with either `192.168` or `10.0`).
3. Click download.

> **Note**: If miniserve show multiple IP addresses, you should try each of them on your phone/tablet browser until you find the correct one. There should only be one IP address that works.
>
> If no IP address works, your router firewall may be blocking the connection, which is common in university or public networks. You can try to connect your phone/tablet and computer to a mobile hotspot or a different router.

## 3. Game Settings

You can adjust game settings by holding the start ▶️ button on the top right. 

**Latency**

- The default input latency is +1 frame, which matches the official cab. If you consistently have more LATE notes than EARLY notes, you can reduce it to 0.

**Network**

- KanadeDX by default is connected to the AquaDX network. There is a default keychip included in the build, but accounts registered on that keychip will be hidden from the leaderboard.
- If you want to see your scores, go to [https://aquadx.net](https://aquadx.net/) and register an account and obtain your keychip in the "Setup Connection" menu. Then, go to settings before entering the game and replace the default keychip with your keychip. Finally, you can click the AIME button to scan your virtual card and this will register your game profile with the server.